# Jegyzőkönyv: Hálózati konfiguráció és tesztelés

## Bevezetés

Ez a jegyzőkönyv a Linksys router beállítását és a hozzá kapcsolódó hálózati eszközök tesztelését dokumentálja. A feladat során IP-címek kezelése, routing tábla megtekintése, ping tesztek és egyéb hálózati parancsok alkalmazása történt.




## Eszközök
A tesztelés során a következő eszközökkel dolgoztam:
- **Catalyst 2950 switch**: A hálózati eszközök közötti kapcsolatot biztosította.
- **Linksys router**: A hálózat központi irányítószerveként szerepelt.
- **ThinkPad laptop**: A teszteléshez használt számítógép, amelyről a ping tesztek és egyéb parancsok futtak.
- **Mobiltelefon**: Ezzel csatlakoztam a Linksys routerhez, hogy a laptop és a többi eszköz között pingelni tudjak.
## 1. A számítógép IP beállításainak lekérdezése
Parancs: `ipconfig`
<details>
  <summary>Kép megtekintése</summary>

  

</details>

## 2. Az aktuális IP-cím eldobása
Parancs: `ipconfig /release`
<details>

  <summary>Kép megtekintése</summary>


</details>

## 3. Új IP-cím kérése
Parancs: `ipconfig /renew`
<details>

  <summary>Kép megtekintése</summary>


</details>

## 4. A routing tábla megjelenítése
Parancs: `netstat -a`
<details>

  <summary>Kép megtekintése</summary>


</details>

## 5. A microsoft.com szerver elérhetőségének tesztelése
Parancs: `ping microsoft.com`
<details>

  <summary>Kép megtekintése</summary>


</details>

## 6. Az www.ipon.hu szerver felé vezető útvonal lekövetése
Parancs: `tracert www.ipon.hu`
<details>

  <summary>Kép megtekintése</summary>


</details>

## 7. Használt portok listázása
Parancs: `netstat -f`
<details>

  <summary>Kép megtekintése</summary>


</details>

## 8. Hálózati kapcsolatok megjelenítése
Parancs: `netsh interface show interface`
<details>

  <summary>Kép megtekintése</summary>


</details>

## 9. DNS-beállítások aktualizálása
Parancs: `ipconfig /flushdns`
<details>

  <summary>Kép megtekintése</summary>


</details>

## 10. Csatolt hálózati meghajtók megjelenítése
Parancs: `net use`
<details>

  <summary>Kép megtekintése</summary>


</details>

## 11. A www.ipon.hu tartománynév és IP-cím megjelenítése
Parancs: `nslookup www.ipon.hu`
<details>

  <summary>Kép megtekintése</summary>


</details>

## 12. Telefon rákapcsolódva a Wi-Fi-re
<details>
  <summary>Kép megtekintése</summary>

</details>

## 13. Telefon pingelése laptopról
<details>
  <summary>Kép megtekintése</summary>

</details>

## 14. Router konfigurációk
<details>
  <summary>Kép megtekintése</summary>

</details>

<details>
  <summary>Kép megtekintése</summary>

</details>

<details>

  <summary>Kép megtekintése</summary>

</details>

## Összegzés
