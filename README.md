# Versija-0.2

Tai Versijos 0.1 papildymas.  
Atsakius į klausimą "Ar norite patys įvesti patys įvesti studento duomenis(t), ar norite, kad jie būtų nuskaityti iš failo (n)?: " t, programa darys viską ką daro Versija 0.1 ir dar galima papildomai pasirinkti ar iškart žinoma kiek bus studentų, ar ne.  
Jei atsakoma taip (t), reikia įrašyti kiek bus studentų, ir tiek studentų duomenų įvesti.  
Jei atsakoma ne (n), gale kiekvieno studento duomenų įrašymo reikia atsakyti į klausimą "Ar norite pridėti dar vieną studentą? "  
Jei atsakoma taip (t), iš pradžių vėl įrašomi sekančio studento duomenys.  
Jei atsakoma ne (n), sekantis studentas nepridedamas ir programa toliau daro, ką darė Versija 0.1.  
### Versija 0.2  
Atsakius į pirmą klausimą "n", programa nuskaito duomenis iš failo "kursiokai.txt".   
Faile yra studento vardas, pavardė, namų darbų pažymiai ir egzamino balas.  
Programa viską nuskaito ir iškart apskaičiuoja galutini balą su mediana ir su vidurkiu.  
Toliau programa išveda studento vardą, pavardę ir galutini balą su vidurkiu ir su mediana.  
# Versija-0.3  
Tai yra Versija0.2 isskirstyta papildomai i funkcija.cpp ir funkcijos.h failus.  
funkcijos.h faile yra aprasytos funkcijos, kurios yra funkcija.cpp faile, taip pat aprašytos naudojamos bibliotekos.  
funkcija.cpp faile yra visos funkcijos.  
mainv3.cpp faile yra int main() funkcija.  
### Paleidimas: 
g++ -o test test5.cpp funkcija.cpp  
./test  
# Versija-0.4  
Versija-0.4 turi papildomą funkciją - sugeneruoti studentų failus, juos nuskaityti, ir suskaičiavus galutinį balą su vidurkiu išskirstyti studentus į du atskirus failus: "Galvotukus.txt" ir "Vargsiukus.txt".  
Norint paleisti naują funkciją, į patį pirmą klausimą  "Ar norite patys irasyti duomenis (t), ar norite, kad jie butu paimti is failo (n), ar kad duomenu failai butu sugeneruoti? (k): " reikia atsakyti "k".  
Tuo met klausiama vartotojo kiek jis norėtų sugeneruoti failų, įvedamas skaičius turi priklausyti intervalui [1;5].  
Tada vartotojas įveda pirmo failo studentų skaičių ir namų darbų skaičių.  
Tada programa išveda kiek užtruko sukurti šį studentų failą, kiek užtruko sukurto failo nuskaitymas, kiek užtruko studentų rūšiavimas į "Galvotukus" ir "Vargsiukus" ir kiek užtruko studentų duomenų išvedimas į "Galvotukus.txt" ir "Vargsiukus.txt".  
### Paleidimas:
g++ -o test mainv4.cpp funkcijos4.cpp  
./test  
# Versija-0.5
