# College 1

CSS secrets book aanschaffen.

**Eindopdracht** Een responsive pagina maken met de aangeleverde componenten uit de pattern library
met in elk geval de opgegeven technieken.

**Beoordeling** hedendaagse browser maar tevens op een willekeurige
oude browser. (Old devices)

**Voor donderdag** lezen hoofdstuk 1 CSS secrets. Handgeschreven
aantekeningen. Geen mondeling overhoring over hoe flexbox werkt.

Bruikbaar; de verwachting van de gebruiker.

---

## Flexbox

* Geen echte layout mogelijkheden
* Tabellen / Inline / Floats etc.
* Nog wel eens buggy

Eigenlijk eerste manier om organische layouts te maken.
Level 24 froggy; met css grid layout aan de slag.

## DRY / Styleguide
Don't repeat yourself. Je gaat fouten maken als je in herhaling valt.
Elementen / componenten die vaak voorkomen, class? Pagina analyseren
welke stukken komen steeds terug? Geen zaken toevoegen die je al had.
Evenals teamwerk; team kan werken met jouw componenten.

Levende styleguide; stuk html met alle componenten van je website.
Kijken in het overzicht, als het er al is kan je het toevoegen.
Verschillende tools om een styleguide te maken, levend.

## Preprocessor

Vertaling van CSS (Sass, less) Alternatieve syntax waar css uitrolt.
Code over het algemeen veel meer dry dan vanilla css. CSS heeft nu ook
variables. Als je zo'n tool gebruikt is het wel een commitment, vooral
voor teamgebruik. Leeft die tool ook zo lang? Onzeker. Tools inzetten
naar keuze, bewust. Nooit afhankelijk van worden, altijd kunnen overstappen.
Als je losgaat met Sass, documenteer het goed.

## Relative Units

* %, vw, vh,
* max-width: 100% op img, object, video
* background-size cover
* flexbox; pas als laatst media queries

## Prefixes

Zet daar een tool voor in. Auto-prefixer. Tool pakken die prefixes
ervoor zet. Steeds minder nodig.

## Select op attributen ipv classes

Style te koppelen op basis van attributen, geen class toevoegen.
Class disabled, telt niet. Semantische waardes gebruiken om iets te stylen.
Je hoeft geen namen te bedenken. Welke attributen zijn er beschikbaar voor een element?

## Oude browsers

* virtualbox
* ubuntu
* open device lab bij Frontlab
* browserstack

## De Opdracht

Hoe moet ik dit nou vormgeven? Oefenen en kijken naar andere huisstijlen.
Geen copy-paste. Probeer zelf te maken. Zijn twee losse vakken dus plan,
kan je niet combineren. Styleguide bijhouden moet / mag.

# College 2

Maak productiecode, ben ik iets aan het leren. Anders ken je alleen nog maar de class selector. Beperking opleggen. Flexbox gaat alleen over dingen naast elkaar zetten. CSS grid is bedoelt voor ordenen, ook onder elkaar. Flexbox voor compenenten (navigation) maar CSS grid meer voor lay-out.

## Mobile-first
* Let op device features.
* Generic Styles
* Layout optimaliseren per viewport.
* Begin klein en ga dan schalen.

Desktop first content is gemaakt om de schermruimte te vullen. Krimpen is minder makkelijk. Vergrote (mobile-first) is makkelijker. Desktop first
vergeet je al snel ook de 4k schermen, omdat je vanaf een fixed point terug gaat werken. informatie die je hebt op ee mooiere layout te plaatsen. Plak niet een a4'tje op je scherm.

## Content als uitgangspunt
* Werk op elk device
* Vormgeving is afhankelijk van content

## Generic style
* Losse componenten van style te voorzien. KLeine kleuren. Maar HTML moet al goed zijn.
* Dan pas met de layout aan de slag. Eerst styles dan layout.
* Meeste devices zitten inbetween (tussen dekstop en mobile)
