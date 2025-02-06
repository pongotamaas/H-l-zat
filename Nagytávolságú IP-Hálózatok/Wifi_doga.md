# Jegyzőkönyv: Hálózati konfiguráció és tesztelés

## Bevezetés

Ez a jegyzőkönyv a Linksys router beállítását és a hozzá kapcsolódó hálózati eszközök tesztelését dokumentálja. A feladat során IP-címek kezelése, routing tábla megtekintése, ping tesztek és egyéb hálózati parancsok alkalmazása történt.




## Eszközök
A tesztelés során a következő eszközökkel dolgoztam:
- **Linksys router**: A hálózat központi irányítósz
- **Catalyst 2950 switch**: A hálózati eszközök közötti kapcsolatot biztosította.erveként szerepelt.
- **Mobiltelefon**: Ezzel csatlakoztam a Linksys routerhez, hogy a laptop és a többi eszköz között pingelni tudjak.
- **ThinkPad laptop**: A teszteléshez használt számítógép, amelyről a ping tesztek és egyéb parancsok futtak.
## 1. A számítógép IP beállításainak lekérdezése
Parancs: [<span style="color: blue; font-weight: bold;">ipconfig`</span>]



  



## 2. Az aktuális IP-cím eldobása
Parancs: [<span style="color: #00FF00; font-weight: bold;">`ipconfig /release`</span>] `ipconfig /release`




## 3. Új IP-cím kérése
Parancs: `ipconfig /renew`







## 4. A routing tábla megjelenítése
Parancs: `netstat -a`

## 5. A microsoft.com szerver elérhetőségének tesztelése
Parancs: `ping microsoft.com`


## 6. Az www.ipon.hu szerver felé vezető útvonal lekövetése
Parancs: `tracert www.ipon.hu`


## 7. Használt portok listázása
Parancs: `netstat -f`


## 8. Hálózati kapcsolatok megjelenítése
Parancs: `netsh interface show interface`


## 9. DNS-beállítások aktualizálása
Parancs: `ipconfig /flushdns`


## 10. Csatolt hálózati meghajtók megjelenítése
Parancs: `net use`


## 11. A www.ipon.hu tartománynév és IP-cím megjelenítése
Parancs: `nslookup www.ipon.hu`

## 12. Telefon rákapcsolódva a Wi-Fi-re

## 13. Telefon pingelése laptopról

## 14. Router konfigurációk


## Összegzés
