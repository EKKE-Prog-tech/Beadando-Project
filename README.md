# LBT_PI154G2 Beadandó

## Első nézet: Hotel szobáinak kezelése
### Singleton Konténerosztály 
Egy Singleton tökéletes a szobák adatainak tárolására és központosítására, így elkerülhető, hogy több példány jöjjön létre ugyanazon adatokról.

### Prototype Design Pattern 
A hotel szobáinak létrehozásához. Ezzel könnyedén létre lehet hozhni az alap szobatípusokat, majd klónozhatod őket, hogy minimális erőfeszítéssel generálhass új szobákat, egyedi tulajdonságokkal.

### További Design Pattern ötletek:

### Decorator Design Pattern
A szobák attribútumainak kiterjesztésére, például extra szolgáltatások hozzáadására (pl. minibár, panoráma kilátás).

### Observer Design Pattern 
Használható arra, hogy értesítést lehessen küldeni a program különböző részeinek, amikor például egy szoba státusza (pl. foglalt vagy szabad) megváltozik.

## Második nézet: Foglalások kezelése
### Singleton Konténerosztály
Egy Singleton tökéletes a foglalás adatainak tárolására és központosítására, így elkerülhető, hogy több példány jöjjön létre ugyanazon adatokról.

### Factory Design Pattern
A Factory minta alkalmazható arra, hogy dinamikusan lehessen létrehozzni különböző típusú foglalásokat (pl. standard, luxus vagy hosszabb távú foglalás).

### További Design Pattern ötletek:

### Strategy Design Pattern
Használható az eltérő árképzési stratégiák vagy foglalási szabályok kezelésére.

### Command Design Pattern
Hasznos lehet a foglalások kezelésére, például módosításokra vagy törlésre, egyértelműen definiált parancsokkal.

## Felület és navigáció
A lapozó gombok a nézetek közötti váltáshoz. Az egyszerűség kedvéért megvalósítható a navigáció egy Mediator Design Pattern segítségével, amely közvetítőként működik a különböző nézetek között.
A grafikus felületen elkülönítve lesznek a szobák és azok kezelést, foglalható szobákat lehet hozzáadni különböző paraméterekkel, és a foglalások kezelése, amik kihatással lesznek a szobák foglaltságára.
