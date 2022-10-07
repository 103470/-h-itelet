## Követelmény Specifikáció



### 1. Áttekintés

Egy olyan szerver oldali alkalmazást fejlesztünk, ami az interneten elterjedt kérdőívekre hasonlít a felhasználók számára ingyenesen, regisztráció mentesen, valamint a személyes adatok felhasználása nélkül.  <br>
Lehetőségünk van ezt a felületet szélesebb körben terjeszteni, megismertetni és gyakoroltatni azokkal akiknek nem lenne könnyen elérhető módja erre. Az alkalmazást bármikor el lehet érni letöltésmentesen a böngészőből, valamint mivel szerveroldalon fut, így a szerver erőforrásai kerülnek felhasználásra.



### 2. Jelenlegi helyzet

A megrendelő szeretne egy letisztult oldallal rendelkező, ingyenes, letöltést nem igénylő Feedback Form-ot, amely a megadott válaszokat egy adatbázisban tárolja el.  <br>
A rendszer lehetőséget nyújt a felhasználók számára, hogy megosszák véleményüket a megrendelővel, aki a felhasználók válaszai alapján szeretne fejleszteni a meglévő weboldalát.

### 3. Vágyálom rendszer

A csapatunk célja, hogy létrehozzunk egy olyan alkalmazást, amely ingyenes, regisztrációmentes és letisztult felület, amely könnyen kezelhető bármely felhasználó számára.  <br>
Többfajta kérdéstípus is szerepel az alkalmazásunkban ami lehetővé teszi a megrendelő számára akár azt is, hogy egyes kérdésekre csak az általa megadott válaszlehetőségek egyikével lehessen válaszolni.

### 4. Funkcionális követelmények

Az alkalmazás funkcionálisan nem bonyolult. Egy böngészőre van szükség ami támogatja a Php-t. <br>
Letöltést nem igényel, a webes felületen könnyen kezelhető. A felhasználó miután befejezte a kitöltést, az általa megadott válaszok rögzítésre kerülnek a befejezés gomb lenyomása után.

### 5. Rendszerre vonatkozó törvények, szabványok, ajánlások

A project az általunk tervezett egyszerű kialakítás alapján készült. Mivel ingyenes nem igényel pénzes hozzájárulást, így nem sorolható a profitáló alkalmazások közé. <br>
Az előbbiek által nem ütközik jogszabályba.

### 6. Jelenlegi üzleti folyamatok modellje

Manapság léteznek olyan Feedback Form-ok amleyek kitöltéséhez regisztráció szükséges, ami kedvezőtlen azok számára akik nem szeretnék megosztani a személyes információikat ezekkel az oldalakkal, félve attól,<br>
hogy azok jogtalanul kerülnek felhasználásra. <br>
Másrészről megtalálhatóak olyan Feedback Form-ok is amelyek bár regisztrációt nem ,de néhány személyes adatot igényelnek a kitöltéshez ami a fent említett problémához vezethet.


### 7. Igényelt üzleti folyamatok modellje

Azért, hogy egy komfortosabb és letisztult felület jöjjön létre, egy olyan kérdőív szolgáltatást hozzunk létre, ami:
- Nem igényel letöltést, így nem áll fenn a lehetőség hogy valaki a tárolt adatokhoz hozzáférjen 
- Nem igényel előzetes regisztrációt, így a személyes adataink biztonságban maradnak 
– Szerver oldalon fut a szolgáltatás, így a szerver erőforrásai kerülnek felhasználásra, nem a felhasználóé.
- Az felhasználó által közölt válaszok egy adatbáziban kerülnek tárolásra, aminek segítségével a megrendelő meg tudja később tekinteni az adott válaszokat.


### 8. Követelmény lista

K0: A felület letisztult, könnyen kezelhető legyen.
K1: A válaszokat egy adatbázisban kell eltárolni, amit később áttekintve,a megrendelő a válaszok alapján fejleszteni tudja meglévő weboldalán.
K2: Az alkalmazáshoz a jövőben hozzáadható legyen több, esetleg új kérdéstípus.


### 9. Fogalomszótár

Survey-questioner: Kérdőív angolul
Data-leak: Adatszivárgás
