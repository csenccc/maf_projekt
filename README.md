# maf_projekt

A programunk egy síkbarajzolható gráf játék.

A program leírása:

Első lépésben megkérdezi a felhasználótól, hogy mekkora gráfot szeretne. Itt három opcióból lehet választani.
Ezután generál egy síkbarajzolható gráfot. A gráf generálása a következőképpen történik: random generál csúcsokat a vásznon, majd behúz nem túl kis/nem túl nagy szögeket bezáró éleket, amennyiben azok nem metszik az addig behúzottakat. A "nehézség" azt szabályozza, hogy hányszor próbál új élet behúzni. A síkbarajzolható gráf csúcsait elmozgatja random helyekre, így készül el a felhasználó által kapott gráf.

Azon a gráfon, amelyet a felhasználó kap, narancssárgával vannak jelölve azok az élek, amelyek metszenek egy másikat, szürkével a már kibogozott élek. Egy csúcsra kattintva lehet azt mozgatni, újbóli kattintással pedig letenni a kívánt helyre. A bal felső sarokban elhelyezkedő "Feladod?" gombra kattintva a gráf "kibogozza magát", vagyis visszatér az összekeverés előtti síkbarajzolt állapotába.

Amennyiben nem nyomta meg a felhasználó a "Feladod?" gombot, és sikerült síkbarajzolnia a gráfot, megjelenik a képernyőn egy "Gratulálunk! :)" felirat.

A játék végén van lehetőség újra játszani.

Használati útmutatók:

A program sikeres futtatásához szükséges telepíteni a py5 csomagot, illetve az első cellában szereplő többi csomagot importálni. A játék elindításához csak sorban le kell futtatni a cellákat, bármilyennemű inputot a vásznon kell majd bevinni.

!!! FONTOS: az első cellában szerepel a %gui osx parancs. Ez a Mac-hez kell, valószínűleg más rendszerben ki kell kommentelni.

Jó szórakozást! :)
