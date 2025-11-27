Edzésnapló alkalmazás
Készítette: Szűcs Bence FCYOFY

Rövid leírás:
Az Edzésnapló egy  grafikus alkalmazás, amely lehetővé teszi
edzések rögzítését, mentését, betöltését és grafikonon történő megjelenítését.

A felhasználó megadhatja az edzés dátumát, típusát és mennyiségét. Az adatok egy
JSON fájlba kerülnek mentésre. A program matplotlib segítségével vonaldiagramot
készít az edzésmennyiségek alakulásáról.

Használt modulok:
 - tkinter
 - matplotlib.pyplot
 - datetime 
 - json 
 - os 
 - saját modul: szb_edzesmodul.py

Függvények:
 - szb_load_sessions
 - szb_save_sessions
 - szb_stats

Osztályok:
 - SZBTrainingEntry
