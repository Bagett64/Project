
Name: Horváth Ákos Neptun: ed9mvq id: 2026-OL-05
# Emergens viselkedési minták vizsgálata egyszerű szabályokon alapuló multi-agent szimulációban

# A brief értelmezése
A projekt lényege az, hogy alacsony paraméteres ágensek egyszerű viselkedési tulajdonságokkal felruházva, nagyobb csoportokban történő interakció és emergens viselkedés vizualizációja, vizsgálata és elemzése.
Ezeket az egyszerű tulajdonságokat a felhasználó egyszerűen állíthatja és paraméterezheti. A szimuláció reprodukálható legyen, ezért a véletlenszerű működés seed segítségével kontrollálható.

# Miért én lennék alkalmas erre a projektre?
Mindig is érdekeltek a különböző agentek interakciói egymással. Nagyon érdekesnek találom azt, hogy elindul a szimuláció és "maguktól" életre kelnek a ágensek, illetve, hogy minimális szabályrendszerrel milyen komplex viselkedési formákat lehet megfigyelni.
AI irányba szeretném vinni a tanulmányaimat azért is vettem fel pluszban szabadon választható tantárgyként az SAP-Learning-et, ahol ugyanúgy AI-al és ágensekkel fogok foglalkozni.
Ez a szakdolgozat téma lehetőséget kínál arra, hogy olyan területen tudjak fejlődni, amivel szívesen dolgozok és fejlesztek. Továbbá a cég, ahol készülök megcsinálni a szakmai gyakorlatot is ilyen agent területtel foglalkozik és így jól illene a CV-mbe.

# Releváns tapasztalat és előzmények
Tanulmányaim során tanultam C#-ot, aminek objektumorientált tulajdonságaival könnyű skálázhatóságot és stabil hátteret tud majd biztosítani a szimulációhoz. Kísérleteztem már Pythonban egyszerű grafikával játékot csinalni a Pygame könyvtárral. Majd itt is keresek egy alkalmas jól terhelhető render könyvtárat például Raylib. Sok videót nézeten már hasonló ágenseknek a működéséről és különböző érdekes projektek kivitelezéséről. 

# Tervezett megközelítés
Elsőként elkészítem a logikai motort C#-ban, ami teljesen független lesz a vizualizációtól. A logikai motor működését automatizált unit tesztekkel ellenőrzöm.
Nagyon fontos a skálázhatóság és a minimális intelligencia, hogy nagy mennyiségű ágens is tudjon futni egyidejűleg.
A felhasználó a szimuláció megkezdése előtt vagy közben is akár beállíthatja az ágensek alapvető viselkedését egy GUI-n keresztül.
Amikor a felhasználó véget vet a szimulációnak akkor utána készül egy részletes jelentés az ágensek viselkedéséről, amit akár .xlsx formátumba is konvertálhat további adatfeldolgozásra.

#  Kezdeti terv
1. Kiválasztok viselkedési szabályrendszereket. Legalább kettő, de inkább több elvet dolgozok ki például madárraj szimuláció.
2. Különféle mérőszámokat fogalmazok meg ami alapján alaposan beállítható és mérhető az ágens csoport viselkedése.
3. Elkészítem a szimulációs modelt grafika nélkül
4. Automata tesztek készítése
5. Seed alapú beállítási lehetőség, hogy a szimuláció megismételhető legyen
6. Grafikus felület megalkotása és implementálása
7. Összehasonlító mérések kiértékelése

# További információ
Az elejétől fogva a publikus Git repóban fogom vezetni a projekt haladását, ahol semmilyen érzékeny személyes adatot nem fogok megosztani.


