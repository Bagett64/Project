---
title: "Emergens viselkedés vizsgálata multi-agent szimulációval"
project_outline: "[[00-project/01-project-outline]]"
---

<!-- @slide Címoldal -->

# Emergens viselkedés vizsgálata multi-agent szimulációval

<!-- @gap 3 -->

<!-- @set-align left -->
<!-- @set-width 60% -->

Szerző: **Horváth Ákos**

Neptun: **ED9MVQ**

Témavezető: **Gábor Oláh**

Projektazonosító: **2026-OL-05**

---

<!-- @slide Probléma -->

# Probléma

<!-- @set-align left -->
<!-- @set-width 75% -->

- Az emergens viselkedés (csoportosulás, mozgási minták, globális struktúrák) egyszerű helyi szabályokból jön létre, ezért elméletben nehezen követhető
- A megértéshez látni és mérni kell, hogyan változik a globális viselkedés a paraméterek hatására
- Kevés az olyan egyszerű, paraméterezhető eszköz, amely a megfigyelést és a mérést egyben kínálja

---

<!-- @slide Célfelhasználók -->

# Célfelhasználók

<!-- @set-align left -->
<!-- @set-width 75% -->

- **Hallgatók**, akik az emergens viselkedést és a multi-agent rendszereket tanulják
- **Oktatók**, akik élő demóval szeretnék szemléltetni a jelenséget
- **Kutatók és fejlesztők**, akik különböző modelleket hasonlítanának össze

---

<!-- @slide Tervezett hatókör -->

# Tervezett hatókör

<!-- @set-align left -->
<!-- @set-scale 75% -->
<!-- @columns 2 5 -->

## Benne van

- Szimulációs alkalmazás, paraméterezhető szabályú ágensekkel
- **Boids** és **Wa-Tor** összehasonlítás
- **Java** backend, a megjelenítéstől elkülönítve
- **TypeScript + PixiJS** webes frontend
- **Real-time** és **batch** futtatási mód
- Mérhető mutatók, automatizált tesztek

<!-- @col-break -->

## Nincs benne

- Felhőalapú üzemeltetés
- Többfelhasználós működés

---

<!-- @slide Kezdeti felhasználói utak -->

# Kezdeti felhasználói utak

<!-- @set-align left -->
<!-- @set-width 75% -->

1. **Megfigyelés:** a Boids szimuláció indítása real-time módban, a raj követése a webes felületen
2. **Kísérletezés:** a szabályparaméterek módosítása, a globális viselkedés változásának megfigyelése
3. **Mérés:** batch futtatás nagyobb ágensszámmal, a mért mutatók kiértékelése
4. **Összehasonlítás:** modellváltás és az emergens minták összevetése

---

<!-- @slide Következő lépések -->

# Következő lépések
  
<!-- @set-align left -->
<!-- @set-width 75% -->

- Kutatás: multi-agent rendszerek és a modellek áttekintése
- **PixiJS** alaposabb megismerése
- A webes **UI** megtervezése
- Teszttervek a fontosabb szabályokhoz
