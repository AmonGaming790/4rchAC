# 🛡️ 4rchAntiCheat

Egyedi, látványos kitiltási rendszer Minecraft (Spigot/Paper) szerverekhez, interaktív visszaszámlálóval és ASCII art grafikával.

---

## ✨ Funkciók

* **Pixel Art Ikon:** Egyedi, keretes felkiáltójel grafika a ban képernyőn.
* **Élő Visszaszámláló:** A játékosok másodpercre pontosan látják a hátralévő időt a csatlakozási ablakban.
* **Auto-Cleanup:** A lejáró kitiltásokat a rendszer automatikusan feloldja belépési kísérletkor.
* **Dinamikus Konfiguráció:** Automatikusan generálódó `config.yml` a szerver prefixének testreszabásához.
* **Időkezelés:** Egyszerűsített parancsok másodperc (`s`), perc (`m`), óra (`h`) és nap (`d`) támogatással.

---

## 🛠️ Parancsok és használat

| Parancs | Leírás | Példa |
| --- | --- | --- |
| `/ban` | Játékos kitiltása | `/ban Amon202394 "indok" {idő}` |
| `/unban` | Kitiltás feloldása | `/unban Amon202394` |

*Megjegyzés: Az indoknál a szóközök helyett használj alulvonást, vagy a rendszer összefűzi a szavakat az utolsó (idő) paraméterig.*

---

## ⚙️ Beállítások (`config.yml`)

A plugin első indításkor létrehozza a mappáját és a konfigurációt:

```yaml
# 4rchAntiCheat konfiguráció
# Használj & karaktereket a színezéshez!
prefix: "&94rch&bAntiCheat"

```

---

## 📥 Telepítés

1. Másold a fordítás után kapott `.jar` fájlt a szerver `plugins` mappájába.
2. Indítsd el a szervert a `config.yml` legenerálásához.
3. Szükség esetén módosítsd a prefixet, majd használd a `/reload` parancsot vagy indítsd újra a szervert.

---

## 💻 Technikai részletek

* **Verzió:** 1.21+ (Paper/Spigot)
* **Nyelv:** Java 21

---

## 👤 Fejlesztő

Készítette: **Amon202394**
