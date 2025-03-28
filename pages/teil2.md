---
layout: image
image: /evolution.png
backgroundSize: 80%
class: bg-white  font-bold text-7xl tracking-tight text-center
title: evolution
---

<div class="-mt-6 p-2 bg-white text-blue-6">Evolution</div>
<div class="mt-77 p-2 bg-white text-blue-6">macht uns krank ?</div>

---
layout: image-right
image: /essen.avif
clicks: 3
---

## Ernährung

<br>

<div v-click=1 class="relative mb-10 makronaehrstoff">
  <el-hand-right v-if="$clicks === 3" class="absolute top-8 left-60 motion-translate-x-loop-25 motion-blur-in-sm size-10 mt-7 ml-10 text-yellow-5" />

### Makronährstoffe

- Proteine - Eiweiß
- Kohlenhydrate
- Fette

</div>

<div v-click=2>

### Mikronährstoffe

- Vitamine
- Mineralien <span class="ml-6 text-sm">Kochsalz, Kalium, Calcium, Magnesium</span>
- Spurenelemente

</div>

<style>
.slidev-vclick-prior.makronaehrstoff {
  opacity: 1.0 !important;
}
</style>

---
layout: image-right
image: /baustoffe.webp
---

# Proteine = Eiweiß

<span class="*:size-12 *:mx-2">
  <twemoji-cut-of-meat />
  <emojione-v1-fish />
  <fluent-emoji-flat-glass-of-milk />
  <twemoji-cheese-wedge />
  <emojione-egg />
  <twemoji-beans />
  <img src="/walnut.png" class="inline-block align-top"/>
</span>

<br>
<br>

### Baustoff

#### kann nicht gespeichert werden

<br>
<v-clicks>

- Reparatur
- Organe, Muskeln, Knochen, Gelenke, Haut
- Antikörper
- Enzyme
- Hormone
- Transport

</v-clicks>

---
layout: image-right
image: /papier.avif
---

## Kohlenhydrate

<div class="*:size-12 *:m-2" >
  <emojione-baguette-bread />
  <emojione-croissant />
  <emojione-pancakes />
  <noto-cooked-rice />
  <emojione-spaghetti />
  <emojione-hamburger />
  <emojione-pizza />
  <twemoji-banana />
  <streamline-emojis-candy />
  <img src="/ketchup.png" class="inline-block align-top"/>
  <noto-beverage-box />
  <img src="/cola.png" class="inline-block align-top"/>
</div>

<br>
<br>

### Brennstoff

#### Schnell verfügbare Energie

#### Speicherbar

<v-clicks depth="2">

- Leber (kurzfristige Energie ca 90 Min)
- Fett (langfristig)

</v-clicks>

---

<div class="grid grid-cols-2 gap-4">

<div>

## Fett

<br>

<v-click>

### gesättigte Fettsäuren

</v-click>

<div class="flex justify-between mb-20">
  <div v-click=1 class="flex space-x-2xl *:size-12">
    <img class="size-12" src="/butter2.png"/>
    <noto-v1-bacon/>
    <emojione-avocado/>
    <twemoji-coconut/>
  </div>
  <div>
    <span v-click class="mr-10">Brennstoff</span><br>
    <span v-click v-mark.underline.red="3">Vitamine</span>
  </div>
</div>

<v-click at=4>

### ungesättigte Fettsäuren

</v-click>

<div class="flex justify-between">
  <div v-click=4  class="flex space-x-2xl *:size-12">
    <img src="/olive-oil.png"/>
    <openmoji-olive/>
    <emojione-v1-sunflower/>
    <twemoji-fish/>
  </div>
  <div v-click=5 class="mr-10 pt-4">Chemikalien</div>
</div>

</div>

<div>
  <img src="/kohle.webp" class="h-60"/>
  <img src="/putzmittel.avif" class="h-54 mt-4"/>

</div>
</div>

---
layout: image-right
image: /transfette.avif
---

## Transfette <emojione-v1-black-skull-cross-bones class="ml-6"/>

<v-clicks>

- Pommes, Chicken Wings, Krapfen
- Sonnenblumenölmargarine
- Chips, Cornflakes
- Wurst
- Fertigsuppen
- Müsliriegel
- Cappuccino-Pulver
- <span v-mark.underline.red="8">Fertiggerichte</span>

</v-clicks>

<!--
In Dänemark dürfen Lebensmittel bereits seit 15 Jahren nicht mehr als zwei Prozent Transfette enthalten. Seitdem ist die Zahl der Herzerkrankungen laut einer Studie deutlich zurückgegangen, um etwa 700 Todesfälle pro Jahr. In Deutschland gibt es derzeit keine gesetzlichen Regelungen für Transfette in Lebensmitteln.
-->

---

## Eiweiß - Proteine

<span class="*:size-12 *:mx-2">
  <twemoji-cut-of-meat />
  <emojione-v1-fish />
  <fluent-emoji-flat-glass-of-milk />
  <twemoji-cheese-wedge />
  <emojione-egg />
  <twemoji-beans />
  <img src="/walnut.png" class="inline-block align-top"/>
</span>

<v-clicks>

- Baumaterial
- ca 20 % der Körpermasse
- ca 50.000 verschiedene Eiweißstoffe im menschlichen Körper
- Grundbausteine sind die 20 Aminosäuren
- davon 9 Aminosäuren <span v-mark.underline.red="5">unentbehrlich</span> !
  > Weizen fehlt es an der <span class="text-red-300 font-bold">Lysin</span><br>
  > Hülsenfrüchten mangelt es an <span class="text-red-300 font-bold">Methionin</span>
- Aufnahme behindert durch Magenschutztabletten
- tgl ca 300 g Eiweiß recycled
- überschüssige Eiweiße werden verbrannt

</v-clicks>

<img src="/darm_eiweiss.jpg" class="abs-br w-130 p-4"/>

---
layout: two-cols
title: AS Mangel
---

## <emojione-baguette-bread mr-4/> Lysin-Mangel

- Wachstumsstörungen bei Kindern
- Kollagenmangel
- erhöhte Infektanfälligkeit
- Übelkeit
- Müdigkeit und Konzentrationsschwäche
- rote Augen
- Haarausfall
- beeinträchtigte Proteinsynthese

## Essentielle Aminosäuren

Lysin, Methionin, Isoleucin, Leucin, Phenylalanin, Threonin, Typtophan, Valin, Histidin

::right::

## <twemoji-beans mr-4/>Methionin-Mangel

- Wassereinlagerungen
- erhöhte Infektanfälligkeit
- erhöhtes Arteriosklerose-Risiko
- Neigung zu Haarausfall
- Verschlechterung bestehender Allergien
- eingeschränkte Entgiftungsfunktion

---

## Kohlenhydrate

<div class="*:size-12 *:m-2" >
  <emojione-baguette-bread />
  <emojione-croissant />
  <emojione-pancakes />
  <noto-cooked-rice />
  <emojione-spaghetti />
  <emojione-hamburger />
  <emojione-pizza />
  <twemoji-banana />
  <streamline-emojis-candy />
  <img src="/ketchup.png" class="inline-block align-top"/>
  <noto-beverage-box />
  <img src="/cola.png" class="inline-block align-top"/>
</div>
<br><br>

### Natürlich vorkommende Kohlenhydrate

<img src="/gute-kh.webp" class="abs-bl w-110 m-6 ml-10"/>
<img src="/verdauung_kohlenhydrate.jpg" class="abs-br w-110 m-6 mr-10"/>

---

## Kohlenhydrate

<div class="*:size-12 *:m-2" >
  <emojione-baguette-bread />
  <emojione-croissant />
  <emojione-pancakes />
  <noto-cooked-rice />
  <emojione-spaghetti />
  <emojione-hamburger />
  <emojione-pizza />
  <twemoji-banana />
  <streamline-emojis-candy />
  <img src="/ketchup.png" class="inline-block align-top"/>
  <noto-beverage-box />
  <img src="/cola.png" class="inline-block align-top"/>
</div>
<br>

### Raffinierte Kohlenhydrate

#### Zucker = Mehl

<img src="/raffinierte-kh.jpg" class="abs-bl w-93 m-6 ml-10"/>
<div class="relativ">
  <img src="/verdauung_zucker.jpg" class="abs-br w-110 m-6 mr-10"/>
  <!-- <fluent-emoji-cross-mark class="absolute size-10" /> -->
</div>

---

## Kohlenhydrate

<div class="flex mt-8 mb-4">
  <div class="text-2xl myt-4 mr-2">
    Kurze Geschichte des Zuckers
  </div>
    <img src="/wuerfelzucker.png" class="inline-block align-top"/>
</div>

<v-clicks>

- galt lange Zeit als äußerst rar und kostbar
- Kolonialzeit: Zuckerrohr aus Mittel- und Südamerika
- späten 18. Jahrhundert: Rübenzucker
- zweite Hälfte des letzten Jahrhunderts: industrielle Massenfertigung
  - gleichzeitig Supermärkte und Fast-Food-Ketten
  - immer mehr zuckerhaltige Fertigprodukte und Getränke
- 70er: High Fructose Corn Sirup
- Zuckerkonsum pro Kopf: 1850 <span v-mark.underline.red="7">8g Zucker</span> - Heute im Durchschnitt <span v-mark.underline.red="8">100g am Tag</span>

</v-clicks>

  <img src="/zucker.jpg" class="abs-tr w-110 m-6 mr-10"/>

---
clicks: 7
---

## Kohlenhydrate<span class="ml-4 space-x-2"><emojione-baguette-bread class="size-12"/><img src="/wuerfelzucker.png" class="inline-block align-top size-12"/></span>

### <br>Zucker

<v-clicks>

- bevorzugte Energiequelle <twemoji-thinking-face class="size-8 ml-2" />
- kann Gewebestrukturen schädigen<br>
  -- karamellisieren (HbA1c)

</v-clicks>

### <br>Insulin

<v-clicks>

- Masthormon
- schleust Zucker in die Zelle
- fördert die Bildung von Fett
- verhindert den Fettabbau

</v-clicks>

<img v-if="$clicks >= 2" src="/Apfel-Karamell.png" class="abs-tr w-50 mt-14 mr-70"/>
<img v-if="$clicks >= 2" src="/rezeptor.png" class="abs-tr w-45 mt-14 mr-20"/>
<img src="/insulinrezeptor.jpg" class=" abs-br w-100 m-6 mr-20" v-if="$clicks === 7" />

---

## Kohlenhydrate<span class="ml-4 space-x-2"><emojione-baguette-bread class="size-12"/><img src="/wuerfelzucker.png" class="inline-block align-top size-12"/></span><br><br>

<oui-dot class="text-green-500 absolute text-3xl left-10 top-44" v-click="1" />
<oui-dot class="text-yellow-500 absolute text-3xl left-10 top-78"  v-click="2"/>
<oui-dot class="text-red-500 absolute text-3xl left-10 top-94"  v-click="3" />

### moderater Zucker- und Mehl-Konsum<img src="/wuerfelzucker.png" class="inline-block align-top size-6 ml-2"/><br>

<v-click>

- Nüchtern Insulin und Blutzucker im Normbereich<br>
  <span class="ml-4">= gesund</span>

</v-click>

### <br>erhöhter Konsum<img src="/wuerfelzucker.png" class="inline-block align-top size-6 ml-2"/><img src="/wuerfelzucker.png" class="inline-block align-top size-6 ml-2"/><img src="/wuerfelzucker.png" class="inline-block align-top size-6 ml-2"/>

<v-click>

- nüchtern-Insulin<mdi-arrow-up-thin class="text-xl" /> (bis 10x) Blutzucker normal<br>
  <span class="ml-4">= Prä-Diabetes <span v-mark.underline.red="2">(viele Jahre unentdeckt)</span></span>

</v-click>
<v-click>

- nüchtern-Insulin<mdi-arrow-up-thin class="text-xl" /> -Blutzucker<mdi-arrow-up-thin class="text-xl" /> <br>
  <span class="ml-4">= Diabetes</span>

</v-click>

<div class="abs-br">
  <el-arrow-up v-if="$clicks >= 2" class="absolute text-blue-500 top-40 left-70 size-12 motion-translate-y-loop-25"/>
  <img src="/insulin_kurve.png" class=" w-95 mr-20 mb-20" />
</div>

---

## Kohlenhydrate<span class="ml-4 space-x-2"><emojione-baguette-bread class="size-12"/><img src="/wuerfelzucker.png" class="inline-block align-top size-12"/></span>

## Prä-Diabetes

<div class="grid grid-cols-2 gap-4">
<div>

### <span class="text-red-300">Symptome</span>

<v-clicks>

- Gewichtsverlust oder Gewichtsabnahme
- Heißhunger
- Schwäche
- Müdigkeit
- Erhöhte Neigung zu Infektionen (Haut, Genitale, Harnwege)
- Verzögerte Wundheilung

</v-clicks>

</div>
<div>

### <span class="text-red-300">Folgen</span>

<v-clicks>

- Bluthochdruck
- Fettstoffwechselstörungen
- Arterienverkalkungen
- Diabetes

</v-clicks>

</div>
</div>

---
layout: image-right
image: /zuckersucht.avif
backgroundSize: 120%
---

## Kohlenhydrate<span class="ml-4 space-x-2"><emojione-baguette-bread class="size-12"/><img src="/wuerfelzucker.png" class="inline-block align-top size-12"/></span><br><br>

### Raffinierte Kohlenhydrate<br> führen zur<br><span class="text-red-400">körperlichen und<br>seelischen Abhängigkeit</span><br><br>

<v-clicks>

- ### Dopamin-Ausschüttung
- ### Insulin<mdi-arrow-up-thin class="text-2xl" /> blockiert Fettabbau<br><span v-mark.underline.red="2">Unterzucker</span>

</v-clicks>

---
layout: image-right
image: /intervallfasten.jpg
backgroundSize: 100%
---

## Kohlenhydrate<span class="ml-4 space-x-2"><emojione-baguette-bread class="size-12"/><img src="/wuerfelzucker.png" class="inline-block align-top size-12"/></span><br>

## Lösung aus der Zuckerfalle?

<v-clicks>

- ### Problem erkennen
- ### raffinierte Zucker meiden
- ### keine Angst vor Fetten
- ### Intervallfasten

</v-clicks>

  <img v-if="$clicks === 4" src="/intervallfasten2.jpg" class="abs-bl w-100 ml-18" />

---
layout: image
image: /panik.jpg
backgroundSize: 150%
clicks: 1
title: Fette
---

<div v-if="$clicks === 1" class="abs-br mr-20 mb-16 !text-(shadow-lg 9xl) motion-preset-[pop slide-up focus] motion-delay-100 motion-preset-shake motion-delay-50">Fette</div>

---

## Fette<span class="ml-4 space-x-2"><img class="size-12 inline" src="/butter2.png"/><noto-v1-bacon/><emojione-avocado/><twemoji-coconut/></span><br><br>

<img src="/butter.jpg" class="abs-tl w-80 mt-30 ml-14" />
<img src="/Öl.jpg" class="abs-tl w-80 mt-81 ml-14" />
<img src="/fettsaeure_ges.jpg" class="abs-tr w-120 h-45 mt-30 mr-14" />
<img src="/infachungesaettigte.jpg" class="abs-tr w-120 h-45 mt-81 mr-14" />
<span class="abs-tr text-red-500 mr-30 mt-20 text-2xl font-bold">Fettsäuren</span>
<span class="abs-tr text-red-500 mr-30 mt-30 text-2xl font-bold">gesättigt</span>
<span class="abs-tr text-red-500 mr-30 mt-81 text-2xl font-bold">ungesättigt</span>
<span class="abs-tr text-red-500 mr-30 mt-118 text-2xl font-bold">mehrfach ungesättigt</span>

---

## Fette<span class="ml-4 space-x-2"><img class="size-12 inline" src="/butter2.png"/><noto-v1-bacon/><emojione-avocado/><twemoji-coconut/></span><br><br>

<img src="/Übersicht-Fettsäuren.jpg" class="abs-tl w-180 mt-30 ml-14" />
<span class="abs-tr text-red-500 mr-10 mt-45 text-2xl font-bold">Brennstoff</span>
<span class="abs-tr text-red-500 mr-12 mt-75 text-2xl font-bold">essentiell</span>

---

## Cholesterin

<img src="/vgl_trigl_chol.jpg" class="abs-tl w-180 mt-30 ml-14" />

---

## Cholesterin

- wird in der Leber produziert
- notwendiger Baustein der Zellmembran
- unverzichtbar bei der Verdauung
- Grundbaustein bei der Hormonproduktion
- Bildung von Vitamin-D
- das Gehirn besteht zu 25% aus Cholesterin

---
layout: image
image: /1961.jpg
backgroundSize: 40%
title: Keys
---

---

### Die Cholesterinhypothese

<v-clicks>

- 1913: Nikolai Anitschkow Kaninchen-Versuch mit tierischer Nahrung
- 1950er: in den USA sterben bald eine halbe Million Menschen jedes Jahr an einem Herzinfarkt
- 1955: US-Präsident Dwight D. Eisenhower einen Herzanfall, den er knapp überlebt
- Ancel Keys (University of Minnesota): Diet-Heart-Hypothesis<br>
  -> Vergleich vom Fettkonsom in 6-7 Länder in 2 Studien<br>
- George Mann: Framingham-Heart-Study<br>
  -> Massai-Krieger (Fleisch, Milch und Rinderblut) trotzdem keine Gefäßerkrankungen
- 1970er: John Yudkin (University of London)<br>
  sieht raffinierte Kohlenhydrate, insbesondere Zucker als das Hauptproblem
- 1980 Dietary Guidelines (allen Menschen wird eine fettarme Ernährung empfohlen)<br>
  - Margarine statt Butter, Fettarme Milch, Joghurt, Quark und Käse
  - Seefisch und Nüsse werden zu "Dickmacher"
  - Vermehrter Einsatz von raffinierten Speiseölen (reich an Omega-6 Fettsäuren) und Zucker
- 2007 Professor Gardner A to Z Study - Low-Carb-Diät<br>
  - Cholesterin stieg, Trigyceride halbiert, Gewichtsabnahme, Blutdruckabnahme

</v-clicks>

---
layout: image
image: /Übergewicht-in-den-USA.jpg
backgroundSize: 70%
---

## Die Cholesterinhypothese

---

## Lipoproteine

<v-clicks>

<img src="/fett_wasser.jpg" class="abs-tl w-100 mt-20 ml-14" />
<img src="/Aufbau-Lipo.jpg" class="abs-bl w-100 mb-3 ml-14" />
<img src="/lipoproteine.webp" class="abs-tr w-110 mt-20 mr-14" />

</v-clicks>

---

## Lipoproteine

### Kreislauf

<img src="/Lipoproteinen.jpg" class="abs-tl w-100 mt-31 ml-14" />
<img src="/bad_lp.png" class="abs-tr w-117 mt-28 mr-14" />

---

## Lipoproteine

### Labortests

<v-clicks>

<img src="/chol1.jpg" class="abs-tl w-105 mt-45 ml-14" />
<img src="/chol2.jpg" class="abs-tr w-105 mt-20 mr-14" />
<img src="/chol3.jpg" class="abs-br w-105 mb-20 mr-14" />

</v-clicks>

---
layout: image
image: /lp_test.png
backgroundSize: 50%
---

## Lipoproteine

---

## Lipoproteine

### Einfluss der Ernährung

<v-clicks>

<img src="/choldiät1.jpg" class="abs-tl w-105 mt-35 ml-14" />
<img src="/choldiät2.jpg" class="abs-tr w-105 mt-35 mr-14" />
<img src="/choldiät3.jpg" class="abs-bl w-105 mb-20 ml-14" />
<img src="/choldiät4.jpg" class="abs-br w-105 mb-20 mr-14" />

</v-clicks>

---

## Lipoproteine

<span>Zuckerreiche Ernähung</span>

<v-clicks>

<img src="/ldl_typb.jpg" class="abs-tl w-90 mt-30 ml-14" />
<img src="/gef_wand_1.jpg" class="abs-tr w-90 mt-30 mr-14" />
<img src="/oxy_ldl2.jpg" class="abs-bl w-90 h-51 mb-5 ml-14" />
<img src="/gef_wand_2.jpg" class="abs-br w-90 mb-5 mr-14" />

</v-clicks>

---

## Lipoproteine

<img src="/chol_plaque.jpg" class="abs-tl w220 mt-25 ml-14" />

---
layout: two-cols
image: /sonnenblumenöl.webp
backgroundSize: 90%
---

### mehrfach ungesättigte Fettsäuren

#### Pflanzenöle

<img src="/sonnenblumenöl.webp" class="abs-bl w-90 mb-5 ml-14" />

::right::

<fluent-color-warning-16 class="text-xl abs-tr mt-42 mr-125" />

| Öl             | Linolsäure | Omega 6/3 |
| -------------- | ---------- | --------- |
| Erdnussöl      | 28%        | 182:1     |
| Distelöl       | 70%        | 160:1     |
| Traubenkernöl  | 70%        | 135:1     |
| Sonnenblumenöl | 66%        | 120:1     |
| Kürbiskernöl   | 50%        | 110:1     |
| Maiskaimöl     | 60%        | 50:1      |
| Sesamöl        | 45%        | 22:1      |
| Olivenöl       | 10%        | 10:1      |
| Sojaöl         | 55%        | 8:1       |
| Weizenkeimöl   | 50%        | 7:1       |
| Walnussöl      | 50%        | 4:1       |
| Leinenöl       | 50%        | 3:1       |
| Hanföl         | 50%        | 3:1       |
| Rapsöl         | 20%        | 3:1       |
| Reiskleieöl    | 30%        | 1:3       |

<style>
th, td {
  font-size: 12px;
  padding: 6px;
  text-align: left;
}
tr:nth-child(n+1):nth-child(-n+6) {color: LightPink}
</style>

---
layout: image
image: /Omega3.jpg
backgroundSize: 90%
title: mehrfach us FS
---

<div class="bg-white abs-tl h-25 w-35 mt-9 ml-100" />
<div class="text-black abs-tl mt-9 mx-60 px-2 text-3xl bg-yellow-200 text-bold">mehrfach ungesättigte Fettsäuren</div>

---
layout: image
image: /ox-LDL.jpg
backgroundSize: 70%
title: ox-LDL
---

---
layout: two-cols
---

# Zusammenfassung

## Gefäßgesundheit

Ernährung

<v-clicks>

- <gg-arrow-down class="size-6 text-red-400" />raffinierte Kohlenhydrate <span class="ml-4 space-x-2"><emojione-baguette-bread class="size-8"/><img src="/wuerfelzucker.png" class="inline-block align-top size-8"/></span><br>
- <gg-arrow-down class="size-6  text-red-400" />raffinierte Pflanzenöle<twemoji-sunflower class="ml-4 size-8"/>

- Vorsicht mit pflanzlichen Ölen <img src="/olive-oil.png" class="ml-2 mb-1 size-6 inline"/>
  - Anreicherung im Körper
  - Oxidation bei Licht und Sauerstoff
- keine Angst vor gesättigten Fetten <img class="size-8 ml-2 inline" src="/butter2.png"/>
- Vorsicht bei Fertignahrung <emojione-pizza class="ml-4 size-6" />

</v-clicks>

::right::

<img src="/suppe1.jpg" class="abs-tr w-60 mt-20 mr-80" />
<img src="/suppe2.jpg" class="abs-tr w-60 mt-20 mr-14" />

---
layout: center
class: text-center text-6xl
---

# <span class="text-6xl">Gesundheit</span>

<div class="text-3xl m-8">ist</div>

# <span class="text-6xl">Eigenverantwortung</span>

---
layout: image
image: /lege.png
backgroundSize: 70%
title: Lege klärt auf
---

---
layout: image
image: /ernährungsdocs.png
backgroundSize: 70%
title: Ernährungsdocs
---

---
layout: image
image: /Kochen-mit-Familie.jpg
backgroundSize: 70%
title: Kochen mit Familie
---
