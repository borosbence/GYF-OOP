# Gyakorló feladatok - OOP
OOP Gyakorlati feladatok

**1. feladat**

Írj osztályt, ami egy Macska objektumot valósít meg.
* A macska adattagjai a következőek legyenek: név (*string*), súly (*double*), éhes -e (*boolean*).
* Két konstruktort is készíts az osztályhoz. Az egyik általános legyen, ami minden adattagot a konstruktor paraméterlistájából állít be, illetve egy másik, ami az első két adattagot a konstruktor paraméterlistájából kapja, és alapértelmezetten éhes a macska legyen.
* Az osztálynak legyen egy eszik metódusa, ami egy *double* értéket vár (étel mennyisége), és egy *boolean*-el tér vissza (sikeres volt-e az etetés). Ha a macska éhes, az etetés sikeres, és a súlya nőjön az étel mennyiségével. A macska ezután ne legyen éhes. Ha a macska nem éhes, az etetés nem sikeres.
* Az osztálynak legyen egy *void* futkos metódusa, ami nem vár paramétert. A macska súlya csökkenjen 0.1-el, és ha nem volt éhes, akkor éhezzen meg.
* Készíts *toString* metódust az osztályhoz.
* A main metódusban hozz létre két macskát a két különböző konstruktorral, és próbáld meg megetetni őket. Az etetés sikerességéről írj információt konzolra.
* Mindkét macska futkosson, és utána írd ki szövegesen az objektumokat.

**2. feladat**

Készítsen osztályt, mely tárol egy szöveget, és a szöveget képes nagybetűsen, kisbetűsen kiírni. Tudjon szövegrészre rákeresni, ki tudja írni, hogy egy szövegrész hányszor fordul elő. Egy példány tartalmazza Móricz Zsigmond: „A török és a tehenek” című versét. Keressük meg benne hányszor szerepel benne a tehén szó és ragozott változatai.

**3. feladat**

Írj osztályt, ami egy *stringet* tárol. Ezt példányosításkor a konstruktorban kapott paraméter segítségével állítsa be. Az osztálynak legyen egy saját függvénye. A függvény adjon vissza egy olyan *stringet*, amiben a tárolt adattag minden betű karakterét ’?’ *karakterre*, és minden szám karakterét * karakterre cseréli.

