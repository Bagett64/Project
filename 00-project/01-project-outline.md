---
name: Horváth Ákos
neptun: ED9MVQ
id: 2026-OG-05
github: https://github.com/Bagett64
github_project: https://github.com/Bagett64/Project
---
# Multi-agent szimuláció emergens viselkedés vizsgálatára

Az emergens viselkedés olyan globális minta vagy struktúra, amely egyszerű, helyi szabályok szerint működő egyedek kölcsönhatásából alakul ki, anélkül hogy bármelyik egyed ismerné az egész rendszert. A projekt egy verziókezelt, paraméterezhető multi-agent szimulációs alkalmazás megvalósítása, amely ezeket a jelenségeket (csoportosulások, mozgási minták, globális struktúrák) megfigyelhetővé és mérhetővé teszi. A szimulációs motor Java backendben fut, a megjelenítést TypeScript alapú webes frontend végzi, a kettő szigorúan elkülönül. A kiindulási modell a Boids (madárraj) viselkedés, amelyet a Vicsek-modell és a ragadozó–préda modell egészít ki az összehasonlításhoz. A projekt végére a felhasználó paramétereket állíthat, modellt választhat, a futást real-time vagy batch módban indíthatja, és mért értékekkel követheti a kialakuló emergens mintákat.

## Célok

- **Elsődleges cél:** Nagyszámú ágenst kezelni képes, paraméterezhető szimulációs alkalmazás elkészítése, amely emergens viselkedést tesz megfigyelhetővé és mérhetővé.
- **Célfelhasználók / érintettek:** Emergens rendszerek iránt érdeklődő hallgatók és akik szeretik a látványos szimulációkat
- **Mérhető sikerkritériumok:**
  - A Boids, a Vicsek és a Wa-Tor modell is futtatható, paraméterei a felületen állíthatók.
  - Legalább egy emergens mutató számolható és megjeleníthető (pl. rendparaméter, csoportméret, populációarány).
  - Real-time és batch futtatási mód is elérhető, a batch futás eredménye elmenthető.
  - A fontosabb szabályokra automatizált tesztek futnak sikeresen.
- **Korlátok:** Java backend, TypeScript/webes frontend PixiJS renderer; a szimulációs logika elkülönül a megjelenítéstől; Git-alapú repó; titkos kulcsok, tokenek és személyes adatok nem kerülhetnek a repóba; localhost futtatás elegendő.

## Hatókör

### Benne van a hatókörben

- Szimulációs motor Java-ban, a megjelenítéstől független logikával.
- Boids modell (szétválasztás, igazodás, összetartás szabályai) mint kiindulási pont.
- Vicsek-modell és ragadozó–préda (Wa-Tor) modell az összehasonlításhoz.
- Paraméterezhető ágensek és szabályok (ágensszám, sebesség, érzékelési sugár, szabálysúlyok stb.).
- Webes frontend az ágensek megjelenítéséhez és a paraméterek állításához.
- Real-time és nem-real-time (batch) futtatási mód.
- Mérőszámok az emergens viselkedés számszerűsítésére.
- Automatizált tesztek a fontosabb szabályokra.
- Verziókezelt repó, dokumentált futtatás.

### Nincs benne a hatókörben

- Éles (production) üzemeltetés vagy felhőalapú telepítés.
- Felhasználókezelés, bejelentkezés.
- Gépi tanulással tanuló ágensek.
