# webtech2

Oktatási Nyilvántartó Rendszer

Mielőtt elindítaná az applikációt, szükség lesz egy MySQL szerverre és azon belül egy "enaplodb" nevű adatbázisra.

Az adatbázis bejelentkezéshez, ha szükséges, meg kell változtatni a bejelentkezési felhasználónevet és jelszót a enaplo > src > main > resources > application.properties nevű fájlban az alábbi sorok javításával.
<b>spring.datasource.username</b>=<i>felhasználónév</i></br>
<b>spring.datasource.password</b>=<i>jelszó</i>

--- RUN ---
<b>Back-end: enaplo > mvn spring-boot:run</b> </br>
<b>Front-end: enaplo-app > ng serve</b>

Alapesetben 4 felhasználó léphet be (felhasználónév/jelszó):
Rendszergazda: admin/admin
Tanár: tanár(1-9)/tanár (kivéve tanár2 és tanár3)
Igazgató: tanár(2-3)/tanár
Tanuló: tanuló(1-20)/tanuló
