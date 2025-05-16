# 🎸 Přenosný kytarový zesilovač na baterie

**Školní projekt – jednoduchý bateriový zesilovač pro elektrickou kytaru**

Tento projekt popisuje stavbu přenosného zesilovače napájeného z Li-ion baterií typu 18650. Cílem je vytvořit jednoduchý, ale funkční zesilovač pro elektrickou kytaru, který lze provozovat bez připojení k elektrické síti. Používají se běžně dostupné moduly, což z projektu dělá ideální volbu pro začátečníky nebo studenty.

## 🔋 BMS modul (Battery Management System)

Pro bezpečné používání tří sériově zapojených Li-ion článků (3S konfigurace) je použit BMS modul s proudovou ochranou 10 A. Tento modul zajišťuje:

- ochranu proti přebití a podbití článků,
- vyvažování napětí mezi jednotlivými články během nabíjení,
- ochranu proti zkratu nebo nadproudu.

Modul je zapojen mezi baterii a napájení celého systému, včetně koncového zesilovače.

## 🎛️ Tone control modul (NE5532)

Pro úpravu zvuku je použit tónový předzesilovač s čipem NE5532. Tento modul nabízí základní úpravy zvuku včetně:

- hlasitosti (volume),
- basů (bass),
- středů (mid),
- výšek (treble).

Jedná se o stereo modul, ale pro kytarový signál postačí jeden kanál. Modul zároveň zajišťuje dostatečné zesílení vstupního signálu z kytary pro další zpracování.

## 🔊 Koncový zesilovač (TPA3118)

Zvuk ze tone modulu je zesílen pomocí digitálního koncového zesilovače s čipem TPA3118. Tento mono zesilovač:

- pracuje s napájecím napětím 12–24 V (napájeno z baterie přes BMS),
- nabízí výkon až 60 W,
- má vysokou účinnost (třída D),
- je vhodný pro malé i středně velké reproduktory.

V případě vyššího výkonu je vhodné doplnit chladič nebo ventilaci.

## 🔉 Reproduktor

Použitý reproduktor by měl odpovídat výstupu zesilovače. Doporučuje se:

- impedance 4 Ω nebo 8 Ω,
- výkon alespoň 20 W (ideálně 30–60 W),
- zapojení přes svorky nebo pájené spoje.

Lze použít vestavěný i externí reproduktor podle preferencí.

## ⚙️ Základní propojení (kabeláž)

Jednotlivé moduly jsou propojeny standardními vodiči, ideálně s dostatečným průřezem pro napájení (např. 0.5–1 mm²) a stíněnými kabely pro audio signál (např. mezi kytarovým vstupem a tone modulem). Délky a způsob zapojení závisí na konkrétní skříni nebo konstrukci zesilovače.

---

## 🎯 Shrnutí

Projekt přenosného zesilovače je ideální pro začínající bastlíře a studenty. Využívá běžně dostupné a cenově dostupné moduly a poskytuje základní zkušenosti s:

- prací s Li-ion napájením a ochranou,
- zpracováním a zesilováním analogového audio signálu,
- základními principy akustiky a zesilovací techniky.

Zesilovač je vhodný pro domácí cvičení, nahrávání nebo venkovní hraní bez nutnosti připojení do sítě.

