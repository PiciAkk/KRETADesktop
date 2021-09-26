# KRETADesktop
Nativefier alapú asztali kliens a KRÉTA e-napló rendszerhez.

## Használati útmutató:
- Töltsd le a futtatható fájlt
  - Letöltheted GitHub releaseként
    - Menj el a [GitHub releasek szekciójába](https://github.com/piciakk/KRETADesktop/releases/latest)
    - Keresd ki a számodra megfelelő platformot
    - Töltsd le a zip fájlt
    - Csomagold ki
  - Kibuildelheted magadnak
    - Nyiss meg egy parancssort 
    - Klónozd le ezt a repo-t
    ```bash
    git clone https://github.com/piciakk/KRETADesktop
    ```
    - Telepítd fel az NPM-et, és a Node-ot (ha még nem tetted meg)
    - Telepítsd fel a Nativefier modult az NPM segítségével
    ```bash
    npm install -g nativefier
    ```
    - Telepítsd fel a `build-tools` szoftvercsomagot
    - Ugorj az újonnan klónozott mappába
    ```bash
    cd KRETADesktop
    ```
    - Buildeld ki
    ```bash
    make
    ```
    - Keresd meg a platformodnak megfelelő mappát
- Lépj a letöltött/kibuildelt mappába
- Futtasd a programot
- Válaszd ki az iskoládat
- Írd be a belépési adataidat
- Használd a Krétát, pont mint a böngésződben
