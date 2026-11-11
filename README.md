Fordítás

1. Mi az a fordítóprogram?
A fordítóprogram olyan számítógépes program, amely egy programozási nyelven megírt forráskódot egy másik kódformára alakít át.

A forráskód feldolgozása.
A szintaktikai és szemantikai hibák ellenőrzése.
A forráskód átalakítása.
A tárgykód előállítása.

2.A fordítás folyamata:
Forráskód
Lexikai elemzés
Szintaktikai elemzés
Szemantikai elemzés
Köztes kód előállítása
Optimalizálás
Célkód / tárgykód

4.Mit ellenőrizhet egy fordító?

Szintaktikai ellenőrzés:
- Helyes-e a nyelvtani szerkezet?
- Megvannak-e a zárójelek?
- Helyesen szerepelnek-e az utasítások?
Szemantikai ellenőrzés:
- Érvényesek-e a műveletek?
- Megfelelőek-e a típusok?
- Helyesen használjuk-e a változókat és függvényeket?
Mit mondj hozzá?

5.Python-példa: a forráskód:
def osszead():
    a = 10
    b = 5
    eredmeny = a + b
    return eredmeny

print(osszead())

A program feladata:
- Két szám összeadása.
- Az eredmény visszaadása.
- Az eredmény megjelenítése.

Python (CPython)
Python-forráskód (.py):
Lexikai és szintaktikai feldolgozás
AST (absztrakt szintaxisfa)
Bájtkód előállítása
Python virtuális gép végrehajtja a bájtkódot

A programfordítási folyamat vizsgálata

1. A projekt célja
A projekt célja a programfordítás folyamatának megismerése és részletes vizsgálata. A kutatás során két megközelítést szeretnék összehasonlítani:
A hagyományos fordítási folyamatot egy C nyelvű programon keresztül.
A Python forráskód feldolgozását és bájtkódra fordítását a CPython működésén keresztül.
A cél annak megértése, hogy a forráskódból milyen lépéseken keresztül jön létre a végrehajtható program, és milyen különbségek vannak a két megközelítés között.

2. Vizsgálati kérdések

Hagyományos fordítás
Milyen lépésekből áll a fordítási folyamat?
Mit végez a lexikai, szintaktikai és szemantikai elemzés?
Mi az a köztes reprezentáció?
Milyen szerepe van az optimalizálásnak?
Mi a gépfüggetlen és gépfüggő fordítás közötti különbség?
Mi a tárgykód és a linkelés szerepe?
Hogyan jön létre a futtatható program?
Python és CPython
Hogyan dolgozza fel a Python a forráskódot?
Mi az AST (absztrakt szintaxisfa)?
Hogyan készül a Python-bájtkód?
Hogyan vizsgálható a bájtkód a dis modul segítségével?
Mi a Python virtuális gép szerepe?
Miben különbözik a Python bájtkódja a natív gépi kódtól?
Összehasonlítás
Milyen közös lépései vannak a két folyamatnak?
Miben térnek el egymástól?
Miért van szükség a különböző végrehajtási megoldásokra?

3. A gyakorlati vizsgálat
Mindkét nyelven egy egyszerű összeadó programot fogok vizsgálni.
A program két számot ad össze, majd megjeleníti az eredményt.
A C-változatnál a GCC fordítót, a Python-változatnál a CPython működését fogom megvizsgálni.

4. A vizsgálat módszere
A fordítási folyamat lépéseinek szakirodalmi feldolgozása.
A hagyományos fordítás egyes lépéseinek gyakorlati megfigyelése.
A Python AST és bájtkód vizsgálata.
A két folyamat eredményeinek összehasonlítása.
A tapasztalatok és kísérletek dokumentálása.

5. Tervezett feladatok
A két fordítási folyamat áttekintő ábrájának elkészítése.
Szakirodalom és dokumentáció gyűjtése.
A konkrét programok elkészítése.
Kísérletek végrehajtása.
A megfigyelések dokumentálása.
A két megközelítés összehasonlítása.
Az eredmények összefoglalása.
