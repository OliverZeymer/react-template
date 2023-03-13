# Opgave Titel - Oliver

Elev: Oliver Zeymer

Hold: WU07

Uddannelse: Webudvikler

&nbsp;

##### Table of Contents  
[Beskrivelse](#beskrivelse)  
[Kode Eksempler](#kode)
[Build Tool](#build)
[Frameworks](#frameworks)
[Libraries](#libraries)
## Beskrivelse

Velkommen til min eksamensopgave! I dette repository har jeg lavet min eksamensopgave med build toolen Vite og en masse andre ting, læs videre for at lære mere om hvordan man kører projektet, min tech-stack og hvordan jeg har overvejet mine valg :)

## Getting Started

1. Klon projektet ned på din egen maskine.
2. Kør kommandoen `npm install` og vent på at alt er blevet installeret korrekt.
3. Få developer serveren op og køre i terminalen:

```bash
npm run dev
```

4. Til sidst hvis Vite ikke allerede har gjordt det for dig, åben http://localhost:5173 i browseren, og så er vi i gang! :)

&nbsp;

# Kode Eksempler:

## #1


Skriftligt forklaret

## #2


Mundtligt forklaret


&nbsp;

# Build Tool

## **Vite**

Vite tilbyder en hurtigere developer experience med sin lynhurtige build time og hurtige reaktionsevne. Vite bruger en moderne og optimeret development process ved hjælp af ES modules, hvilket resulterer i at det er meget hurtigere end CRA. Dette betyder, at development processsen er mere effektiv og smooth, da man som udvikler kan se ændringerne i real time mens man arbejder.

# Frameworks

## **React.js**

For mig var der to muligheder, enten at skrive i frameworket **Next.js** eller **React.js**. Jeg valgte at bruge React da det er det framework som jeg har mest erfaring med og fordi da jeg gjorde mig overvejelser om projektbeskrivelsen og kravene, tænkte jeg at jeg højest sandsynligt ikke ville gøre brug af Next's ekstra funktionaliteter alligevel (så som Server Side Rendering og SEO).

React stiller en masse forskellige ting til rådighed som for eksempel et stort community som gør det rigtig nemt at finde problemløsninger, stort udvalg af npm pakker, og det er rigtig nemt at genanvende forskellige komponenter så jeg slipper for at gentage kode jeg allerede har skrevet.

Derudover kan man med React lave en single page applikation hvilket vil sige at man ikke er nødt til at genindlæse en helt ny html side hver gang man skifter side, hvilket gør din applikation hurtigere og får den til at føles mere smooth.

&nbsp;

## **TailwindCSS**

Jeg har valgt at bruge Tailwind som mit CSS framework da jeg synes det er helt klart den bedste og mindst tidskrævende måde at skrive CSS på. I modsætning til normale CSS filer som vi kender, styler man med Tailwind direkte når man skriver sin jsx kode ved hjælp af predefinerede klasser, hvilket jeg synes er super smart og hjælper mit workflow rigtig meget.

Der er også andre meget populære CSS frameworks som for eksempel Bootstrap. Bootstrap har meninger om hvordan tingene skal se ud, og man har mindre frihed til at lave noget der ser unikt ud hvorimod med Tailwind kan man lave lige hvad man kunne have lyst til på sin egen måde, så det er derfor jeg har valgt Tailwind frem for Bootstrap.

&nbsp;

# Libraries

## **Framer-motion**

Det var nok ikke helt behøvet i et projekt på denne størrelse men jeg er blevet virkelig glad for framer-motion og vil gerne vise at jeg kan finde ud af det, jeg bruger det i stort set alle mine projekter.

I stedet for at lave CSS animationer som vi kender, gør Framer-motion det virkelig nemt ved at man bare kalde sit element for eksempel `<motion.div>`, og derefter give elementet en masse props der fortæller hvordan det skal animeres.

Ligesom TailwindCSS sparer det en virkelig meget tid og kode. Der skal altså ikke meget til for at lave nogle simple men smukke animationer, især hvis man allerede har nogle prædefinerede motion variants fra et andet projekt så er det virkelig nemt at sætte det op.

## **React-router**

React router gør det muligt at navigere siden ved hjælp af at bytte alle de viste komponenter ud hvilket gør det til en single page applikation. Single page applikationer gør applikationen meget hurtigere da man ikke genindlæser et helt nyt html dokument hver gang man navigerer på siden. SPAs giver også en bedre user experience da man ikke ser siden refreshe hver gang man navigere og giver en mere smooth oplevelse.

## **Axios**

Jeg har valgt at bruge axios til mine HTTP requests. Med axios frem for bare at lave et normalt fetch kald er formateringen til json allerede indbygget i det. Axios giver en rigtig god developer experience da jeg personligt synes at kodestrukturen er nemmere at forstå og læse. Axios giver også en bedre user experience i forhold til Cross-browser compatibilty, det vil sige at axios tager sig selv af at få requesten til at virke på meget gamle systemer/browsere hvor man med fetch manuelt skal ind og tjekke på det.

## **React-Toastify**

Jeg har valgt at bruge React-Toastify fordi det er en simpel og effektiv måde at implementere notifikationer og feedback til brugeren. Biblioteket er let at bruge og tilbyder virkelig meget reusability, så det nemt kan integreres i eksisterende projekter. Det er virkelig let at tilpasse udseendet og animationerne, så det passer til applikationens design og branding. React-Toastify et velkendt og veldokumenteret bibliotek, som har et aktiv og støttende community, som kan hjælpe med eventuelle spørgsmål eller problemer, der måtte opstå under implementeringen.

## **Lucide-react**

Jeg har valgt at bruge Lucide-React ikoner i stedet for React-Icons fordi Lucide-React ikoner tilbyder et mere moderne og minimalistisk design. Lucide-React ikoner er mere tilgængelige og lette at forstå, da de er baseret på symboler og ikoner, der er let genkendelige for brugerne. Fra hvad jeg har kunne undersøge er Lucide-React ikoner lettere og mere optimerede end React-Icons, hvilket betyder, at applikationen vil blive hurtigere og mere effektiv.

&nbsp;

# Valgfrie opgaver ?

- A
- B
- C

&nbsp;

# Projekt perspektivering

Hvis jeg skulle skalere dette projekt, ville jeg -

Hvis jeg skulle forbedre applikationen ville jeg -
