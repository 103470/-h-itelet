## Rendszeterv

### 1, A rendszer célja
 A rendszer célja, hogy a felhasználó teher és költségmentesen készíthessen kérdőívet.
 Fontos, hogy a felhasználó könnyen el tudjon igazodni a felületen, ezért egy minimalista felhasználói felületet kap a program.
 Egyetlen szerepkör van a program használatánál, a felhasználó, de ez csak a kérdőív elkészítéséhez szükséges funkciókhoz ad hozzáférést
 a program működésének megváltoztatásához, a kódhoz nem fér hozzá közvetlenül.  <br>
 Az alkalmazás webes felületen lesz elérhető, ezért arra törekszünk, hogy minél több böngészővel legyen kompatibilis.

### 2, Projekt terv
 A projektet weblapra fejlesztjük front- és backend segítségével. Az elkülönített feladatokon más-más emberek dolgoznak.  <br>
 Frontend fejlesztése HTML/CSS segítségével  <br>
 Frontend felelős: Kémeri Martin (SSR0TI) -HTML, CSS és oldal dizájn  <br>
 A feladat célja, hogy egy letisztult, könnyen kezelhető, igényes weblapot nyújtson a felhasználó számára.  <br>

 Backend felelős: Magos Balázs (JJ3NZ0) -PHP és tesztelés  <br>
 Feladata a háttérben működő programok megírása, PHP kód, és az eredmény kiértékelés.  <br>
 
 Ütemtervünk, amelyet sikeresen tartottunk:  <br>
 2022.09.14 Brainstorming
 2022.09.20 Követelmény és funkcionális specifikációk elkészítése
 2022.09.21 Első látványtervek megvalósítása
 2022.10.03 Rendszerterv elkészítése
 2022.10.08 Kódolás és az alkalmazás tesztelése
 2022.10.10 Release modell létrejötte
 
 Mérföldköveink:  <br>
 Feedback-formunk személyreszabhatóvá tétele a weboldalon keresztül 
 Országos ismeretségre törés (15 000 felhasználó)
 

### 3,Követelmények
 - Webes megvalósítás.
 - A rendszer fejlesztése HTML/CSS valamint PHP segítségével történik.
 - A weblap felépítése, valamint dizájnolása a HTML/CSS nyelv implementálásával valósítandó meg.
 - A weboldal használatához egy egyszerű böngészőre van szükség.
 - Megszakításmentes felhasználói élmény.
 
### 4,Üzleti folyamatok modellje

![ábra drawio](https://user-images.githubusercontent.com/113610538/193619940-d47416ba-3dfd-4a4d-81cf-11d8c93a24e7.png)

 
### 5, Funkcionális terv
 Rendszerszereplők:  <br>
 Felhasználó: Rendszerünknek nincs más szereplője, csak a felhasználó, mert nincs értelme több, pl. egy admin szereplő
 hozzáadásának, A felhasználó adatok megadásával tudja szerkeszteni a kérdőívet.

### 6, Fizikai környezet
 A rendszer fejlesztése HTML/CSS valamint PHP segítségével történik.
    A weblap felépítése, valamint dizájnolása a HTML/CSS nyelv implementálásával valósítandó meg.
 A weboldal használatához egy egyszerű böngészőre van szükség.
 A rendszer bármilyen operációs rendszeren és böngészőben haszálható lesz, valamint telefonról is.

### 7, Architecturális terv
 A rendszerhez mindössze egy webböngészőre van szükség, amely képes PHP kódot futtatni. 
 Mivel az egész a kliens oldalon fut, akár a HTML fájl megnyitásával futtatható az alkalmazás.

### 8, Teszt terv
 Az alkalmazás elkészítése során szükség van a folyamatos tesztelésre. Tesztelni kell a gombok működését, valamint az adatok változásait

 Unit teszt: 2022.10.03: Metódusok működése és működésének biztosítása teszt során megtörtént és hiba nélkül lefutott.
 - Magos Balázs Alpha teszt: 2022.10.01: A projektet leteszteltük Mozilla Firefox, Google Chrome és Microsoft Edge környezetben, kisebb vizuális torzulással de működését megőrizte.
 - Kémeri Martin, Magos Balázs Béta: 2022.10.03: A projekt letesztelése különböző böngészőkben, különböző felbontásokban és telefonon, kisebb vizuális torzulás de a funkciók működése megmaradt.

### 9, Telepítési terv
 Az alkalmazás futtatásához egy általános felhasználású böngészőre van szükség, nem igényel külön telepítést.

### 10, Karbantartási terv
 Az alkalmazás bővítési lehetőségét fenntartjuk.

### 11, Implementációs terv
 A felület HTML és CSS nyelven fog készülni valamint PHP-t is felhasználunk az alkalmazás készítéséhez.  <br>
 A jobb átláthatóság és a továbbfejleszthetőség érdekében elkülönítve szeretnénk kezelni ezeket a technológiákat és utólag kapcsoljuk össze őket.  <br>
