## Funkcionális Specifikáció



### 1. Áttekintés

Egy olyan szerver oldali alkalmazást fejlesztünk, ami az interneten elterjedt kérdőívekre hasonlít a felhasználók számára ingyenesen, regisztráció mentesen, valamint a személyes adatok felhasználása nélkül.  <br>
Lehetőségünk van ezt a felületet szélesebb körben terjeszteni, megismertetni és gyakoroltatni azokkal akiknek nem lenne könnyen elérhető módja erre. Az alkalmazást bármikor el lehet érni letöltésmentesen a böngészőből, valamint mivel szerveroldalon fut, így a szerver erőforrásai kerülnek felhasználásra.



### 2. Jelenlegi helyzet

A megrendelő szeretne egy letisztult oldallal rendelkező, ingyenes, letöltést nem igénylő Feedback Form-ot, amely a megadott válaszokat egy adatbázisban tárolja el.  <br>
A rendszer lehetőséget nyújt a felhasználók számára, hogy megosszák véleményüket a megrendelővel, aki a felhasználók válaszai alapján szeretne fejleszteni a meglévő weboldalát.

### 3. Jelenlegi üzleti folyamatok modellje

Manapság léteznek olyan Feedback Form-ok amleyek kitöltéséhez regisztráció szükséges, ami kedvezőtlen azok számára akik nem szeretnék megosztani a személyes információikat ezekkel az oldalakkal, félve attól,<br>
hogy azok jogtalanul kerülnek felhasználásra. <br>
Másrészről megtalálhatóak olyan Feedback Form-ok is amelyek bár regisztrációt nem ,de néhány személyes adatot igényelnek a kitöltéshez ami a fent említett problémához vezethet.


![Jelenlegi_uzleti_foly_abra drawio](https://user-images.githubusercontent.com/113610538/194552763-813b0e2a-818a-455b-bbe7-afb936a80cd3.png)


### 4. Igényelt üzleti folyamatok modellje

Azért, hogy egy komfortosabb és kölcsönös érjünk el a felhasználókkal, egy olyan kérdőív szolgáltatást hozzunk létre, ami:
- Nem igényel letöltést, így nem áll fenn a lehetőség hogy valaki a tárolt adatokhoz hozzáférjen 
- Nem igényel előzetes regisztrációt, így a személyes adataink biztonságban maradnak
– Szerver oldalon fut a szolgáltatás, így a szerver erőforrásai kerülnek felhasználásra, nem a felhasználóé.
- Az felhasználó által közölt válaszok egy adatbáziban kerülnek tárolásra, aminek segítségével a megrendelő meg tudja később tekinteni az adott válaszokat.


![Igenyelt_uzleti_foly_abra drawio](https://user-images.githubusercontent.com/113610538/194552734-c2448268-adb2-44a8-b495-c4d4e0c3e141.png)


### 5. Használati esetek

A projektünk teljesen ingyenes és nem igényel regisztrációt, így nem zárjuk ki a felhasználók nagy részét és adataikat sem tesszük ki semmiféle veszélynek.  <br>
Egy könnyen kezelhető, letisztult, átlátható dizájnnal megfelelünk a kor követelményinek, valamint eleget teszünk a könnyű felfoghatóság és átláthatóság feltételeinek is,  <br>
a szerveroldalon történő működésnek köszönhetően a szerver erőforrásai kerülnek felhasználásra.



### 6. Funkció-követelmény megfeleltetés

K0: A felület kialakításának köszönhetően jól átlátható, a szöveg beírására szolgáltatott részben le van írva melyik kérdésre kell válaszolni, így még a számítógép világában nem jártas személyek számára sem okozhat nehézséget a kitöltés<br>
K1: A válaszok adatbázisban történő eltárolása végett választottuk a szerver oldali alkalmazás lehetőségét, mivel így el biztonságosan eltudjuk tárolni az adatokat amit a felhasználó később megtekinthet, felhasználhat.<br>
K2: A adatbázisban a jövőben létrehozhatók újabb részak amiben adatot tudunk tárolni, amihez a kódban történő változtatásokat hozzá tudjuk csatolni, így minden adat arra a részre kerül ahová tartoznia kell.


### 7. Képernyőterv

![asd drawio](https://user-images.githubusercontent.com/113610538/191433773-89816925-c2ef-4b96-9857-d7128a57db61.png)


### 8. Fogalomszótár

Feedback-Form: Visszajelző űrlap
Data-leak: Adatszivárgás
