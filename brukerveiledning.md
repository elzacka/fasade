# Brukerveiledning for Fasade

Fasade lager produktbildene App Store viser: En serie bilder med samme utseende,
riktig størrelse og sømløse overganger.

**Innhold:** [Kom i gang](#kom-i-gang) · [Mal og unntak](#mal-og-unntak) ·
[Overganger](#overganger) · [Plassering](#plassering) · [Tekst](#tekst) ·
[Telefon og grafikk](#telefon-og-grafikk) · [Bakgrunn](#bakgrunn) ·
[Sjekk serien](#sjekk-serien) · [Lagring](#lagring) ·
[Knapper og snarveier](#knapper-og-snarveier)

| Ord | Betyr |
| --- | --- |
| Bilde | Ett produktbilde i serien: Bilde 1, Bilde 2 og så videre. «Valgte bilder» og «Alle bilder» betyr alltid disse |
| Skjermbilde | Skjermdumpen fra appen, inne i telefonrammen |

## Kom i gang

1. **Åpne Fasade** fra [lenken](https://elzacka.github.io/fasade/). Vil du kjøre
   den lokalt på Mac eller PC: Last ned ZIP-filen fra GitHub (<kbd>Code</kbd> →
   <kbd>Download ZIP</kbd>), pakk den ut og åpne `fasade.html` i Chrome eller Edge.
2. **Velg format og skriv appnavnet** øverst. Appnavnet blir filnavnet, for
   eksempel `appnavn-1320x2868-1.png`.
3. **«+ Legg til bilder»**: Du får ett bilde per skjermbilde du velger.
4. **«Innhold»**: Skriv overskrift og undertekst for hvert bilde.
5. **Juster**: Klikk på et element i bildet og endre det i panelet til høyre.
6. **«Sjekk serien»**: Klikk på et funn for å gå til det.
7. **«Alle bilder»** laster ned serien som PNG-er, klare for App Store Connect.
   «Last ned» tar bare bildet du står i.

## Mal og unntak

- Utseendet ligger i en mal for hele serien. Endrer du en farge i ett bilde,
  endres den i alle.
- Tekst og skjermbilder hører til hvert bilde og følger aldri malen.
- «Endringer gjelder» øverst i panelet bestemmer hvor en endring havner:

| Valg | Endringen gjelder |
| --- | --- |
| Hele serien | Alle bildene. Standard |
| Bare dette | Bildet du står i |
| Valgte bilder | Bildene du krysser av for, og alltid bildet du står i |

- Et unntak blir stående selv om du endrer malen. Panelet viser hva som avviker.
- «Følg malen igjen» fjerner unntaket. «Legg laget i malen» gjør det til ny
  standard for hele serien.

## Overganger

- App Store viser bildene side om side med et smalt mellomrom. Et lag kan
  fortsette fra ett bilde til det neste.
- «Fortsetter i nabobildet»: Laget tegnes også i nabobildet, i riktig
  forskyvning. Det er ett lag, så begge delene flytter seg alltid sammen, uansett
  «Endringer gjelder».
- «I sømmen mot forrige» og «I sømmen mot neste» legger laget midt i overgangen.
- Mellomrommet: 4,4 % i App Store på iPhone, 7,3 % i nettleseren, eller «Midt
  imellom». En overgang treffer perfekt bare ett av stedene.
- Se overgangene mens du jobber: «Vis overgangene» i «Visning».
- Se serien slik App Store viser den: «Stripe under» i «Visning», så «Vis stort».

## Plassering

- Når du drar et lag, fester det seg til midten av bildet, til andre lag og til
  margen.
- Mens du drar, ser du avstanden til naboene i tall. Lik avstand blir grønn.
- Støttelinjer og snapping slår du av og på i «Visning». Støttelinjene kommer
  aldri med i bildene du laster ned.
- Merk flere lag med Skift-klikk eller ved å dra en ramme rundt dem. Klikker du
  på et lag i en gruppe, merkes hele gruppen.

## Tekst

- Dobbeltklikk på en tekst for å skrive rett i bildet.
- Marker ord for å gi dem egen farge, vekt, størrelse eller tusj i verktøylinja
  som dukker opp. Finjuster under «Uthevede ord» i panelet.
- «Plate bak teksten» passer til merknader oppå skjermbildet. Platen vokser med
  teksten.
- «Systemfont» er SF på Mac og systemskriften på PC.

> [!TIP]
> For stor avstand mellom ordene? Monospace-skrifter som DM Mono har et nesten
> tre ganger så bredt mellomrom. Sett «Ordavstand» til 50–60 %.

## Telefon og grafikk

- «Velg skjermbilde» i panelet. Ni rammefarger, og størrelse og utsnitt for hver
  telefon.
- «+ Grafikk» legger inn en logo eller et symbol. «Ensfarget» farger det i én
  farge.

> [!TIP]
> Bruk små vinkler i «Tilt i 3D». Store vinkler gjør skjermbildet vanskelig å lese.

## Bakgrunn

- Ensfarget, gradient, bilde eller gjennomsiktig. Gjennomsiktig blir hvit når du
  laster ned, fordi App Store Connect ikke godtar gjennomsiktighet.
- «Strekkes over serien»: Én bakgrunn over hele serien, og hvert bilde viser sin
  del.
- «Bruk bakgrunnen i»: Velg hvilke bilder bakgrunnen gjelder.

## Sjekk serien

Sjekken finner:

- Eksempeltekst som står igjen
- Bilder med samme overskrift
- Skjermbilder med for lav oppløsning
- Tekst utenfor bildet
- Lag nærmere kanten enn margen
- Svak kontrast mellom tekst og bakgrunn
- Gjennomsiktig bakgrunn
- Overganger som ikke går opp
- En overskrift som blir for liten i søkeresultatet

En telefon som går ut over kanten, regnes som et bevisst utsnitt.

## Lagring

- Fasade lagrer alt i nettleseren, også bildene.
- «Lagre» gir filen `<appnavn>-fasade.json`. «Åpne» henter den inn igjen, også
  på en annen maskin.
- Bytter du mellom iPhone og iPad, husker Fasade oppsettet i hvert format.

> [!IMPORTANT]
> Lagringen følger adressen. Lenken og en lokal fil har hver sin lagring. Flytt
> arbeid mellom dem med «Lagre» og «Åpne».

## Knapper og snarveier

| Symbol | Gjør |
| --- | --- |
| ↑ ↓, og ← → i stripa | Flytter bildet eller laget frem eller bak |
| ⧉ | Dupliserer |
| ✕ | Sletter |
| Prikken ved et lag | Skjuler laget uten å slette det |

| Gjør | Mac | PC |
| --- | --- | --- |
| Angre | <kbd>⌘</kbd> <kbd>Z</kbd> | <kbd>Ctrl</kbd> <kbd>Z</kbd> |
| Gjør om | <kbd>⇧</kbd> <kbd>⌘</kbd> <kbd>Z</kbd> | <kbd>Skift</kbd> <kbd>Ctrl</kbd> <kbd>Z</kbd> |
| Kopier, klipp ut, lim inn | <kbd>⌘</kbd> <kbd>C</kbd> <kbd>X</kbd> <kbd>V</kbd> | <kbd>Ctrl</kbd> <kbd>C</kbd> <kbd>X</kbd> <kbd>V</kbd> |
| Dupliser | <kbd>⌘</kbd> <kbd>D</kbd> | <kbd>Ctrl</kbd> <kbd>D</kbd> |
| Merk alle lag | <kbd>⌘</kbd> <kbd>A</kbd> | <kbd>Ctrl</kbd> <kbd>A</kbd> |
| Grupper | <kbd>⌘</kbd> <kbd>G</kbd> | <kbd>Ctrl</kbd> <kbd>G</kbd> |
| Løs opp gruppen | <kbd>⇧</kbd> <kbd>⌘</kbd> <kbd>G</kbd> | <kbd>Skift</kbd> <kbd>Ctrl</kbd> <kbd>G</kbd> |
| Fet, kursiv, understrek | <kbd>⌘</kbd> <kbd>B</kbd> <kbd>I</kbd> <kbd>U</kbd> | <kbd>Ctrl</kbd> <kbd>B</kbd> <kbd>I</kbd> <kbd>U</kbd> |
| Skriv i valgt tekst, avslutt | <kbd>Enter</kbd>, <kbd>Esc</kbd> | <kbd>Enter</kbd>, <kbd>Esc</kbd> |
| Flytt litt, flytt mer | Piltast, <kbd>⇧</kbd> + piltast | Piltast, <kbd>Skift</kbd> + piltast |
| Slett | <kbd>⌫</kbd> | <kbd>Delete</kbd> eller <kbd>Backspace</kbd> |
| Dra uten snapping | Hold <kbd>⌥</kbd> | Hold <kbd>Alt</kbd> |

Kopier og lim inn virker også mellom bildene og mellom to vinduer. Et bilde fra
utklippstavla blir et grafikklag. Høyreklikk gir de samme valgene i en meny.
