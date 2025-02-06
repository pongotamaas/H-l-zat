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
![ipconfig](https://github.com/user-attachments/assets/b7428cb1-9ced-4501-8741-fca4f0b760b9)


## 2. Az aktuális IP-cím eldobása
Parancs: [<span style="color: blue; font-weight: bold;">`ipconfig /release`</span>]
![ipconfig-release](https://github.com/user-attachments/assets/956a0833-6965-48e5-939a-1e3ffce41234)

## 3. Új IP-cím kérése
Parancs: [<span style="color: blue; font-weight: bold;">`ipconfig /renew`</span>]
![iprenew](https://github.com/user-attachments/assets/2a9aa41a-58ee-43ea-9ce2-cd4f21bbfae8)


## 4. A routing tábla megjelenítése
Parancs: [<span style="color: blue; font-weight: bold;">`netstat -a`</span>]
![netstat-a](https://github.com/user-attachments/assets/03b46189-a225-438f-853e-0408ac570a68)


## 5. A microsoft.com szerver elérhetőségének tesztelése
Parancs: [<span style="color: blue; font-weight: bold;">`ping microsoft.com`</span>]
![microsoft](https://github.com/user-attachments/assets/7655731f-188f-4121-a056-47ac3f161cf0)


## 6. Az www.ipon.hu szerver felé vezető útvonal lekövetése
Parancs: [<span style="color: blue; font-weight: bold;">`tracert www.ipon.hu`</span>]
![ipon](https://github.com/user-attachments/assets/3c9d749b-0633-4859-ab3d-23c6e5a77bfa)


## 7. Használt portok listázása
Parancs: [<span style="color: blue; font-weight: bold;">`netstat -f`</span>]


## 8. Hálózati kapcsolatok megjelenítése
Parancs: [<span style="color: blue; font-weight: bold;">`netsh interface show interface`</span>]


## 9. DNS-beállítások aktualizálása
Parancs: [<span style="color: blue; font-weight: bold;">`ipconfig /flushdns`</span>]
![flushdns](https://github.com/user-attachments/assets/f4716a5a-b0fc-4b65-bb03-1e1bd89438b6)

## 10. Csatolt hálózati meghajtók megjelenítése
Parancs: [<span style="color: blue; font-weight: bold;">`net use`</span>]
![netuse](https://github.com/user-attachments/assets/86297e9f-c176-48e4-bf32-f1f7a8519a92)

## 11. A www.ipon.hu tartománynév és IP-cím megjelenítése
Parancs: [<span style="color: blue; font-weight: bold;">`nslookup www.ipon.hu`</span>]
![nslookpup-ip](https://github.com/user-attachments/assets/27eda2c6-eb41-47b1-accc-ed797fb96dfd)


## 12. Telefon rákapcsolódva a Wi-Fi-re

## 13. Telefon pingelése laptopról

## 14. Router konfigurációk


## Összegzés
