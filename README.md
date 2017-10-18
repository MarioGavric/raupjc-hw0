# raupjc-hw0

#Pitanje 1:
Nakon dodavanja class library-a U bin/Debug folderu se mogu naci 2 nova file-a, MyConsole.dll i MyConsole.pdb
Program has stopped working, could not load file or assembly 'MyConsole' se javlja nakon brisanja .dll class library-a, iz razloga sto nije moguce ucitati funkicje koje koristimo iz MyConsola
Uz .exe file moram ukljuciti i sve .dll fileove svih eksternih klasa koje smo koristili

#Pitanje 2:
Samom izmjenom u klasi bez buildanja se pokretanjem .exe filea koristi stari kod, tj. ispisuje stari string, ali cim se opet builda konzolna aplikacija se printa novi string

#PItanje 3:
Build proces se normalno izveo, bez poresaka, te se u package direktoriju ponovno nasao NodaTime folder
