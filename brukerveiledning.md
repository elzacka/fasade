# Brukerveiledning for Fasade

Fasade lager produktbildene App Store viser for iPhone, iPad og Mac: En serie
bilder med samme utseende, riktig størrelse og sømløse overganger.

**Innhold:** [Kom i gang](#kom-i-gang) · [Mal og unntak](#mal-og-unntak) ·
[Overganger](#overganger) · [Plassering](#plassering) · [Tekst](#tekst) ·
[Telefon, Mac og grafikk](#telefon-mac-og-grafikk) · [Bakgrunn](#bakgrunn) ·
[Sjekk serien](#sjekk-serien) · [Lagring](#lagring) ·
[Knapper og snarveier](#knapper-og-snarveier)

| Ord | Betyr |
| --- | --- |
| Bilde | Ett produktbilde i serien: Bilde 1, Bilde 2 og så videre. «Valgte bilder» og «Alle bilder» betyr alltid disse |
| Skjermbilde | Skjermdumpen fra appen, inne i rammen til telefonen eller Macen |

## Kom i gang

1. **Åpne Fasade** fra [lenken](https://elzacka.github.io/fasade/). Vil du kjøre
   den lokalt på Mac eller PC: Last ned ZIP-filen fra GitHub (<kbd>Code</kbd> →
   <kbd>Download ZIP</kbd>), pakk den ut og åpne `fasade.html` i Chrome eller Edge.
2. **Velg format og skriv appnavnet** øverst. Appnavnet blir filnavnet, for
   eksempel `appnavn-1206x2622-1.png`.
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
- Lag ett bilde slik du vil ha det, og velg «Bruk som mal for serien» øverst i
  panelet. Utseendet går ut til bildene som følger malen. Unntak du har laget i
  dem, blir stående.
- Ta av «Følger malen» for et bilde som skal se annerledes ut. Bildet beholder
  utseendet sitt, og endringer i malen når ikke dit. Bildet er merket «Egen» i
  listen. Huker du av igjen, får bildet utseendet fra malen.

## Overganger

- App Store viser bildene side om side med et smalt mellomrom. Et lag kan
  fortsette fra ett bilde til det neste.
- «Fortsetter i nabobildet»: Laget tegnes også i nabobildet, i riktig
  forskyvning. Det er ett lag, så begge delene flytter seg alltid sammen, uansett
  «Endringer gjelder».
- «I sømmen mot forrige» og «I sømmen mot neste» legger laget midt i overgangen.
- Mellomrommet: 4,4 % i App Store på iPhone, 7,3 % i nettleseren, eller «Midt
  imellom». En overgang treffer perfekt bare ett av stedene. For Mac er
  mellomrommet 4,5 % i nettleseren.
- Se nabobildene mens du jobber: Slå på «Vis nabobildene» i «Visning», og velg
  hvor mye du vil se. «Kanten» viser en stripe av bildet på hver side,
  «Naboene» viser hele bildet før og etter, og «Alle» viser hele serien på en
  rad. Du jobber i bildet med ramme rundt. Klikk på et lag i et annet bilde, så
  jobber du i det bildet med det laget valgt.
- Velger du et lag, får de tilsvarende lagene i de andre bildene en svak ramme.
  De følger med når du flytter, skalerer eller formaterer, så lenge «Endringer
  gjelder» står på «Hele serien» eller «Valgte bilder». Med «Bare dette» endrer
  du bare bildet du jobber i.
- Se serien slik App Store viser den: «Stripe under» i «Visning», så «Vis stort».

## Plassering

- Y for en tekst er toppen av første linje. Brytes teksten over flere linjer,
  vokser den nedover, og toppen blir stående. Samme Y gir samme topp i alle
  bildene.
- I en gruppe følger et lag laget over seg: Det holder samme avstand under det.
  Brytes overskriften over en linje til, flytter underteksten seg ned. Flytter du
  underteksten alene, endrer du avstanden.
- Grupperer du lag i et bilde som følger malen, grupperes de samme lagene i de
  andre bildene som følger malen. Det samme gjelder når du løser opp gruppen.
- Når du drar et lag, fester det seg til midten av bildet, til andre lag og til
  margen.
- Det fester seg også der avstanden er lik over og under laget (og til venstre
  og høyre). Mangler det noe på den ene siden, regnes bildekanten.
- Mens du drar, ser du avstanden til naboene i tall. Lik avstand blir grønn.
  Flytter du med piltastene, vises tallene en liten stund etterpå.
- Vil du ha lik avstand for overskrift og undertekst sammen, merker du begge med
  Skift-klikk og drar dem som én blokk.
- «Snapping» i «Visning» slår av og på alt som fester seg. «Snapp til
  støttelinjene» gjelder bare linjene du har slått på under «Støttelinjer».
  Støttelinjene kommer aldri med i bildene du laster ned.
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

## Telefon, Mac og grafikk

- «Velg skjermbilde» i panelet. Ni rammefarger, og størrelse og utsnitt for hver
  telefon.
- Under «Modell» velger du iPhone 17 Pro eller iPhone 18 Pro. Velg modellen du
  tok skjermbildet på, så får rammen riktig Dynamic Island.
- Ta skjermbildene på en iPhone 17 Pro eller 18 Pro. Skjermbilder fra en Pro
  Max passer ikke til rammen, og «Sjekk serien» sier fra.
- «Sjekk serien» ser ikke om du har valgt feil modell. iPhone 17 Pro og 18 Pro
  tar skjermbilder i samme størrelse.
- «+ Grafikk» legger inn en logo eller et symbol. «Ensfarget» farger det i én
  farge.

### Statuslinje

- Under «Statuslinje» i panelet velger du «Behold», «Skjul» eller «Bytt ut».
- «Skjul» dekker statuslinjen med bakgrunnsfargen i skjermbildet.
- «Bytt ut» henter statuslinjen fra et annet skjermbilde du velger. Det må være
  tatt på samme iPhone-modell som skjermbildet i telefonen.
- Fasade kan bare skjule eller bytte ut statuslinjen når bakgrunnen bak den er
  ensfarget. Ellers viser Fasade skjermbildet uendret, og «Sjekk serien» sier fra.

> [!TIP]
> Vil du ha klokken 9.41, full dekning og fullt batteri? Start appen i Simulator
> på samme iPhone-modell som skjermbildene dine, og kjør dette i Terminal:
>
> ```sh
> xcrun simctl status_bar booted override --time 9:41 --dataNetwork wifi --wifiMode active --wifiBars 3 --cellularMode active --cellularBars 4 --operatorName '' --batteryState discharging --batteryLevel 100
> xcrun simctl io booted screenshot statuslinje.png
> ```
>
> Har du flere simulatorer i gang, skriver du navnet på simulatoren i stedet for
> `booted`. Simulator kan ikke vise flymodus, batteriprosenten eller pilen for
> Stedstjenester. Ta skjermbildet på iPhone når du trenger dem.

> [!TIP]
> Bruk små vinkler i «Tilt i 3D». Store vinkler gjør skjermbildet vanskelig å lese.

### Mac

- Velg «Mac» som format øverst. Bildene blir 2880 × 1800 piksler, den største
  størrelsen App Store Connect tar imot for Mac.
- Mac har sin egen serie. Første gang du velger Mac, får serien tekstene og
  utseendet fra serien for iPhone og iPad. Den serien står urørt til du bytter
  tilbake.
- Rammen er en MacBook Air 13 tommer. Velg farge og størrelse i panelet.
- Ta skjermbildet av hele skjermen med <kbd>⇧</kbd> <kbd>⌘</kbd> <kbd>3</kbd>.
  Et skjermbilde fra en MacBook Air 13 tommer passer rammen, uansett
  skjermoppløsning. «Sjekk serien» sier fra når skjermbildet har en annen form
  enn skjermen.
- «+ Mac» legger en Mac inn i alle formater, også ved siden av en telefon.

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
- Skjermbilder som ikke passer til rammen
- Tekst utenfor bildet
- Lag nærmere kanten enn margen
- Svak kontrast mellom tekst og bakgrunn
- Gjennomsiktig bakgrunn
- Overganger som ikke går opp
- En overskrift som blir for liten i søkeresultatet, for iPhone og iPad
- Statuslinjer Fasade ikke kan skjule eller bytte ut
- Grafikk uten bilde
- Mer enn ti bilder i serien

En telefon eller Mac som går ut over kanten, regnes som et bevisst utsnitt.

## Lagring

- Fasade lagrer alt i nettleseren, også bildene. Nettleseren kan slette det,
  for eksempel når du tømmer nettleserdata. Safari kan slette det etter sju
  dager uten bruk. Lagre arbeidet som fil med «Lagre».
- «Lagre» gir filen `<appnavn>-fasade.json`. «Åpne» henter den inn igjen, også
  på en annen maskin.
- Fasade husker oppsettet i hvert format når du bytter mellom iPhone og iPad.
  Mac har sin egen serie, se [Mac](#mac).
- Et prosjekt i formatet iPhone 6,9 tommer blir skalert til 6,3 tommer når du
  åpner det. Det er størrelsen App Store Connect tar imot for iPhone.

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
| Gjør om | <kbd>⇧</kbd> <kbd>⌘</kbd> <kbd>Z</kbd> | <kbd>Skift</kbd> <kbd>Ctrl</kbd> <kbd>Z</kbd> eller <kbd>Ctrl</kbd> <kbd>Y</kbd> |
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
