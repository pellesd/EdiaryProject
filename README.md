# EdiaryProject
 BME VIK Bsc Szakdolgozat Projekt 

## Backend kipróbálása:
A backend kódja a backend nevű mappában található. Mivel az appsettings.json-ben a jelszavak át lettek írva, így ezt lokálisan futtatni nem lehet, viszont az azure-ra telepített verzióját és a webszerverhez készített Swagger UI-t az alábbi webcím alatt lehet megtalálni kb. 2023.02.01-ig: https://nlenaplo.azurewebsites.net/. Ennek kipróbálásához tanulóként a StudentAuth tag alatt található studentauth/login végponton, tanárként pedig a TeacherAuth tag alatt található teacherauth/login végponton kell egy lent megadott felhasználónév-jelszó párossal bejelentkezni. A válaszul kapott JSON-ből a JWT tokent ki kell másolni, és az oldal jobb felső sarkában található "Authorize" feliratú gomb megnyomása után "Bearer " prefixxel ellátva be kell illeszteni a tokent, és leokézni. Ezután a token minden kérésünkhöz automatikusan hozzá fog adódni. Tanárként a Teacher és a Basic tag alatti végpontokat tudjuk elérni, tanulóként pedig a Student tag alatti összes végpontot, a Basic tag alatt pedig a GET /canteen/{date} és a GET /ping végpontokat érhetjük el.


## Android
Az Android alkalmazások kipróbáláshoz az AndroidStudent illetve AndroidTeacher mappákban lévő projekteket kell az Android Studioba betölteni és futtatni. Az alkalmazás legenerált .apk állományai a github linken érhetőek el a TeacherAPK illetve StudentAPK mappákban. Ezeket Androidos készülékre másolva és telepítve az applikációk egyből kipróbálhatóak.

A github linken a Dokumentáció mappában a Dolgozat pdf változata és az alkalmazás képernyőképei is láthatóak.

### Néhány tanulói felhasználó:
felhasználónév: 42265899104 (osztályfőnöke gulyasatti)
jelszó: 3230

felhasználónév: 25958027690
jelszó: 3568

Néhány tanári felhasználó:
felhasználónév: balrich
jelszó: asd

felhasználónév: gulyasatti
jelszó: asd
