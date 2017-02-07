# CSS Secrets[1]

## 5.25 - Fancy Ampersands
Contrast between sans-serif font and an ampersand. Current technique
is pretty messy.

Font declaration also works **per-character** basis. Font only
avaliable for a couple of characters. This applies for both
local and embedded fonts.

Adding an extra font creates another HTTP request and it is a
hassle to create a font file. (Legal issues)

`local()` function for local font names. You need a descriptor using
a unicode range to only get the characters you want.

`"&".charCodeAt(0).toString(16); // returns 26`

**Multiple characters are allowed** seperated by a comma.
**Italic Serif fonts** have nicer ligatures.

## 6.32 - De-emphasize by Dimming
Dim everything behind an element.
**Pseudo-element solution** to elimenate the need for an extra HTML element.
.dimmed class moet je dan toevoegen via JavaScript.

**Box-shadow solution**
Create large shadow in hacky way. `1 vmax` is the same as 1vh and
1vw. Mostly used for position fixed elements.

**Backdrop solution**
Dialog has default overlay through User Agent Stylehseet. Easiest way
but limited browser support.

## 6.33 - De-emphasize by Blurring.
More realistic then dimming, it creates depth. Blur filter. You have to
use an extra HTML element, otherwise whole body becomes blurred.
Use `main` element. You can animate CSS filters.

Good idea to combine dimming and blurring; add contrast and brightness to filter.
If browser doesn't support CSS filters, no fallback.

## 7.36 - Intrinsic sizing

Let width adjust to the content. New width and height keywords.
Min-content; *This keyword gives us the width of the largest unbreakable element inside the box*

## 7.40 - Vertical centering
**Inline element**; text-align center. **Block element** margin; auto.
Transform in percentages; styles it relative to width and height of element but
is has some cavaets.

* vw is relative to the viewport width. Contrary to many expectations, 1vw stands for 1% of the viewport width, not 100%.
* Similarly to vw, 1vh represents 1% of the viewport height.
* 1vmin is equal to 1vw if the viewport width is smaller than the height, otherwise it is equal to 1vh.
* 1vmax is equal to 1vw if the viewport width is larger than the height, otherwise it is equal to 1vh.

**Flexbox solution**
Is the best solution. Flexbox in modern browsers is pretty good.

[1]: http://proquestcombo.safaribooksonline.com.rps.hva.nl:2048/book/web-development/css/9781449372736/chapter-5dot-typography/ch05lev1sec06_html
