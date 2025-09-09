# Verziókezelés git

- helyi repo létrehozása:
    > git init 
- ellenőrzés: milyen fájlok változtak(az előző verzióhoz képest)
    > git status
- előkészítjük (stage=színpad) az új verziót, minden fájlt amiben történt módosulás:
    > git add .
- ellenőrzünk:
    > git status
- felhasználó név beállítása:
    > git config user.name ...
- email cím beállítása:
    > git config user.email ...
- az új verzó megszületése:
    > git commit -m "first commit"