# iviKeya

Az **iviKeya** a telefon kamerájával vonalkódokat és QR-kódokat olvas be, majd az adatokat a párosított Windows-gépre küldi. A PC-n futó [iviKeyw](https://github.com/ivisofthu/iviKeyw) a kódot az aktív ablakba gépeli, például Excelbe vagy készletkezelő programba.

## Telepítés

Android 7.0 vagy újabb rendszer szükséges.

1. [Töltsd le az iviKeya APK-t](https://github.com/ivisofthu/iviKeya/releases/download/v1.0.4-test/iviKeya-1.0.4-test.apk) a telefonodra, majd nyisd meg.
2. Ha az Android kéri, engedélyezd a telepítést az APK megnyitásához használt böngésző vagy fájlkezelő számára. Csak megbízható forrásból telepíts; a készülék biztonsági védelmét ne kapcsold ki.
3. Indítsd el az alkalmazást, és engedélyezd a kamerahasználatot.
4. Add meg az e-mail-címedet és a készülék nevét, majd írd be az e-mailben kapott ellenőrzőkódot. Az aktiváláshoz internetkapcsolat szükséges.

Minden készülékhez külön licenc tartozik; ugyanaz az e-mail-cím több készülékhez is használható. Az újonnan regisztrált készülék 7 napos próbaidőt kap. Internet nélkül legfeljebb 3 napig használható, az érvényes licenc lejáratáig. Hosszabbítással kapcsolatban: [ivisoft@ivisoft.hu](mailto:ivisoft@ivisoft.hu).

A licencoldali frissítéssel lekérhető a meghosszabbított jogosultság. Ehhez nem kell új APK-t telepíteni.

## Párosítás a PC-vel

1. Telepítsd és indítsd el a Windows-gépen az [iviKeyw](https://github.com/ivisofthu/iviKeyw) programot. Az ablakát az óra melletti tálcaikonról nyithatod meg.
2. A telefon és a PC ugyanahhoz a megbízható helyi hálózathoz csatlakozzon.
3. Jelenítsd meg a PC-n a párosítási QR-kódot, és olvasd be a telefon Beállítások oldalán.
4. A párosított eszközök oldalán válaszd ki a kívánt PC-t. A készülékhez tartozó megjegyzést a telefonon is szerkesztheted.

## Olvasás és kézi bevitel

- **Kézi olvasás:** a SCAN gomb indítja a kamerát. Beolvasás után a kamera a beállított idő elteltével leáll.
- **Pultszkenner:** folyamatos olvasás, külön indítás/leállítás gombbal. Az azonos kód újraolvasásához vedd ki azt a képből.
- **EAN / UPC / QR / ALL:** a kamera bal oldalán választható kódszűrő. Az ALL a támogatott többi formátumot, például a Data Matrix kódot is engedi.
- **1x / 2x:** kameranagyítás, a készülék képességeitől függően.
- **S1–S4:** a PC-n beállított slot kiválasztása. A prefix/suffix műveleteket a Windows-programban szerkesztheted; a telefonon a PC adatainak frissítésével kérheted le őket.
- **Kézi gombok:** a számok, műveleti jelek, BSP, ENT és nyilak azonnal továbbítódnak. A kamera működése és a függőben lévő küldés alatt a gombok inaktívak. Az ADD gomb jelenleg nem használható.

A zöld keret a kód felismerését jelzi. A sikeres küldést jelző hang csak a PC visszaigazolása után szólal meg, ha a hangjelzés engedélyezett. Küldési hiba esetén ellenőrizd a célprogramot; nincs automatikus újraküldés.

## Beállítások és frissítés

A Beállítások oldal **Olvasó beállításai** részében kapcsolható a hang és a rezgés, a képernyő ébren tartása, valamint a kézi olvasás utáni 0/2/5 másodperces kameraleállítás. Ezek automatikusan mentődnek. A kézzel módosított PC-kapcsolati adatokat a Mentés gombbal rögzítsd.

A Névjegy/Frissítés oldalon érhető el a frissítéskeresés. A letöltött APK telepítését az Android rendszerablakában jóvá kell hagynod. Frissítéshez lehetőleg a meglévő alkalmazásra telepíts; az eltávolítás törölheti a helyi párosításokat és a licencazonosságot. Telepítési ütközés esetén kérj segítséget az eltávolítás előtt.

## Biztonság és kapcsolat

A telefon–PC adatátvitel HTTP-t használ, nem titkosított. Csak megbízható helyi hálózaton használd, internetes porttovábbítás nélkül. A párosítási kulcsot ne oszd meg illetéktelennel. A PC-n mindig ellenőrizd az aktív ablakot és a célmezőt.

**iviSoft / Duncsák Mihály egyéni vállalkozó**  
[ivisoft.hu](https://ivisoft.hu) · [ivisoft@ivisoft.hu](mailto:ivisoft@ivisoft.hu)

A külső összetevők licencinformációi az alkalmazás Névjegy oldaláról érhetők el. A kiadásnál SHA-256 ellenőrzőösszeg is található. A saját alkalmazás forráskódja nem része a letöltésnek.
