# XOR-krypteringsdemo – Battleship Edition

Dette er en enkel nettbasert demonstrasjon av XOR-kryptering brukt i vårt bachelorprosjekt ved HVL. Demoen viser hvordan koordinater fra et Battleship-lignende spill blir kryptert før de sendes mellom avsender og mottaker.

## 🎯 Funksjoner
- Velg koordinat (A1–H8)
- Velg krypteringsnøkkel (6 bit)
- Bit-for-bit XOR-animasjon
- Viser original verdi, nøkkel og kryptert resultat
- 100% kjørbart i nettleser (HTML + CSS + JS)

## 🧠 Hvordan det fungerer
Koordinaten (f.eks. B2) konverteres til en 6-bit binær verdi.  
Denne XOR-es med en valgt nøkkel:
