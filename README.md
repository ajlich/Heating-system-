# Heating-system-
U ovom projektu su korištene fizičke komponente poput breadboard-a, kablova, DHT11 senzora, led diode, NodeMcu, otpornik i LCD ekran. Dakle, DHT11 senzorom se mjeri 
trenutna temperatura i vlažnost u zraku, potom se te informacije šalju preko NodeMcu-a na arduino gdje setujemo podatke na firebase da bi ih web stranica mogla getati i 
ispisivati. Suštinski firebase služi za komunikaciju između arduina i web stranice. Potom korisnik na web stranici postavlja željenu temperaturu, te se taj podatak
šalje na firebase da bi arduino mogao getati željenu temperaturu. Nakon toga se ispituje, da li je željena temperatura veća od trenutne i ako je ishod istinit u tom 
slučaju će se led dioda upaliti (odnosno upalio bi se sistem za zagrijavanje), a u suprotnom se neće ništa desiti tj. led dioda će ostati ugašena.

link firebase-a : 
https://console.firebase.google.com/u/0/project/ajlaproject/database/ajlaproject-default-rtdb/data
