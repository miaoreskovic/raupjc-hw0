# raupjc-hw0
#Pitanje 1:
Nakon dodavanja class library-a kao reference i pokretanja build operacije
u folderu su nastale dvije nove datoteteke ClassLibrary1.dll i ClassLibrary1.pdb.
Nakon uklanjanja .dll datoteke i pokretanja .exe datoteke, aplikacija se neće izvršiti
već izbaci pogrešku. Zato što aplikacija ovisi o ClassLibrary1.dll datoteci 
(main klasa Hw0 aplikacije koristi metodu MyConsole klase koja se nalazi u ClassLibrary1).
Kako bi se aplikacija mogla koristiti poslala bih .exe i .dll datoteku.

#Pitanje 2:
Konzolna aplikacija je koristila novu verziju class library asemblija, odnosno
prikazala je novi string. Zato što konzolna aplikacija ovisi o class library 
projektu i pokretanje konzolne aplikacije(a prije toga build) automatski pokreće i
class library projekt.

#Pitanje 3:
Build proces se uspješno izvršio, prije samog build procesa odvilo se restoranje
NuGet packagesa. Package direktorij ponovo sadrži NodaTime paket.
