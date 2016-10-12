# JMBAG
0036472859

# Pitanje 1
Nakon dodavanja class library reference u bin/debug folderu konzolne aplikacije možemo primjetiti dvije nove datoteke: "ClassLibrary1" i "ClassLibrary1.dll". 
U slučaju brisanja prethodno navedene dll datoteke, program nam pri pokretanju javlja grešku s opisom da ne može pronaći class library datoteku koja je potrebna za normalno izvršavanje programa.
Da bi aplikacija bila funkcionalna potrebne su 3 datoteke: "ClassLibrary1.dll", "KonzolnaAplikacija" i "KonzolnaAplikacija.exe".

# Pitanje 2
U slučaju kada se class library projekt ne prevodi aplikacija koristi staru verziju class library asemblija što znači da promjene neće biti vidljive.

# Pitanje 3
Ispisalo se "Pero: Hello World".

# Pitanje 4
U bin/debug folderu se pojavila datoteka s imenom "PeroClassLibrary.dll".

# Pitanje 5
Nakon brisanja originalnog dll-a aplikacija i dalje radi zbog toga što se u bin/debug folderu projekta nalazi istovjetna datoteka koja se koristi za buildanje.

# Pitanje 6
Aplikacija se uspješno buildala i u folderu "packages" se opet pojavio "NodaTime" folder.