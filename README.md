# Stanko Inventura

Besplatni alat tvrtke [Logiko d.o.o.](https://logiko.hr) za cikličku inventuru, u dvije samostalne web aplikacije koje rade u pregledniku:

- `ciklicka-inventura.html` – planer: učitava popis artikala (Excel/CSV), raspoređuje brojanja po pravilu A=6, B=2, C=1 s ravnomjernim dnevnim opterećenjem, validira raspored i izvozi Excel.
- `brojanje.html` – mobilna aplikacija (PWA) za kontrolno brojanje: učitava godišnji plan, skenira bar kod, bilježi pronađene količine, izvozi CSV/Excel.

Svi podaci obrađuju se lokalno u pregledniku; ništa se ne šalje na poslužitelj.
