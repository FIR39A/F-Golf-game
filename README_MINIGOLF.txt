
==============================
🎯 2D MiniGolf – F# Projekt
==============================

Ez egy F# nyelven írt 2D-s minigolf játék, ami Windows Forms alapon készült, és több pályát, akadályokat, ütés-számlálót, valamint hanghatást is tartalmaz.

🔧 Követelmények:
------------------------------
✔ .NET Framework 4.7.2 vagy újabb  
✔ Visual Studio (ajánlott F# támogatással)  
✔ `hit.wav` fájl a projekt gyökerében (ütéshanghoz)  

📁 Fájlstruktúra:
------------------------------
- `Program.fs` — A játék főprogramja (grafika, logika, események)  
- `hit.wav` — A labdaütés hangja  

🕹 Funkciók:
------------------------------
✅ 5 különböző pálya, fokozatosan nehezedő akadályokkal  
✅ Ütésszámláló pályánként  
✅ Játék végén statisztika  
✅ Csak álló labda lökhető  
✅ Vizuális iránynyíl színátmenettel  
✅ Hanghatás minden ütéskor  
✅ Vibrálásmentes megjelenítés (`DoubleBuffered` panel)  

▶ Indítás:
------------------------------
1. Helyezd el a `hit.wav` fájlt a projekt mappájába.
2. Nyisd meg a `Program.fs` fájlt Visual Studio-ban.
3. Futtasd a projektet (`Ctrl + F5`).

📌 Megjegyzés:
------------------------------
Ha a `hit.wav` fájl nem található vagy hibás, a játék tovább működik hang nélkül.

🎉 Jó játékot kívánunk!
