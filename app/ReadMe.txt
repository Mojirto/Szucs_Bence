Edzésnapló alkalmazás
Készítette: Szűcs Bence

Rövid leírás:
Az Edzésnapló egy Python nyelven készült grafikus alkalmazás, amely lehetővé teszi
edzések rögzítését, mentését, betöltését és grafikonon történő megjelenítését.
A felhasználó megadhatja az edzés dátumát, típusát és mennyiségét. Az adatok egy
JSON fájlba kerülnek mentésre. A program matplotlib segítségével vonaldiagramot
készít az edzésmennyiségek alakulásáról.

Használt modulok:
 - tkinter (grafikus felület)
 - matplotlib.pyplot (grafikonok)
 - datetime (dátumkezelés)
 - json (adatfájl kezelés)
 - os (fájlműveletek)
 - saját modul: szb_edzesmodul.py

Függvények:
 - szb_load_sessions(filename)
 - szb_save_sessions(filename, sessions)
 - szb_stats(sessions)

Osztályok:
 - SZBTrainingEntry

Futtatás:
 - A szükséges csomagok telepítése: pip install -r requirements.txt
 - A program indítása: python main.py