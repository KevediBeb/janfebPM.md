# Januari-Februari TP Projekt PM

Kevin Tornéus, 2025-02-21

## Inledning

Syftet med detta arbete var att jag skulle testa att göra valfritt program i programmeringsspråket c++, eftersom att det var något nytt för mig. Detta skulle pågå från slutet av Januari till Februari och arbetades på cirka 2 gånger i veckan. 

## Bakgrund

Programmet som skapades var en recreation av tärningsspelet "Drop Dead" då jag efter några lektionerns tid inte fick c++ support att fungera till visual studiop och när jag väl lyckades visste jag inte vad jag tänkte göra. Jag sökte därefter på Google på olika tärningsspel som finns och valde sedan ett som lät relativt simpelt. 

Det första som jag sedan testade var att försöka få ett tärningskastssystem att fungera, alltså att kunna generera ett slumpmässigt tal mellan 1-6 och sedan skriva ut det i konsollen. Till hjälp under detta arbete hade jag w3schools c++ genomgångar samt använde jag mig av gamla forum osv. Jag märkte dock fort att programmet alltid skrev ut samma siffra varenda gång programmet startades upp igen. Detta undersöktes ytterliga och jag fick sedan reda på att c++ program kommer att alltid få fram samma slumpmässiga resultat eftersom att programmet utgår ifrån ett "seed" värde som bestämmer hur allting ska hända i förhand. Hur detta oftast löstes enligt tidigare dokumentation var att i början av programmet manuellt sätta sitt seed till antalet sekunder som har passerat sedan 1970 eftersom att det alltid kommer garantera ett annorlunda seed varje gång. Detta hade kunnats ta som ett tecken att c++ inte riktigt var gjort för detta typ av program i och med att det var uppenbart att seed funktionaliteten inte skulle användas på detta sätt. 

Med seed problemet löst fortsatte jag att arbeta på själva spelet utan några större problem, mycket i c++ liknar även språk som java och c# i denna kontext, förutom den största skillnaden som är hur in och output hanteras med cin och cout.

Enligt reglerna i Drop Dead så ska varje spelare slå 5 tärningar och addera summan av dessa förutom om tärningen visar 2 eller 5, i detta fall ska tärningen igonreras och ta bort inför nästa kast. Detta fortsåtter till spelaren har slut på tärningar och sedan går spelet vidare till nästa spelare. Jag började därför med att simulera en runda av spelet för att sedan i början av programmet låta användaren skriva in spelarantal och spelarnamn för att sedan loopa rundan för alla.


![NTI Gymnasiet Umeå Logo](https://raw.githubusercontent.com/jensnti/Webbprojekt/master/mallar/nti_logo_white_umea.svg)

## Positiva erfarenheter

Här beskriver du vad som har gått bra i ditt projekt och analyserar varför. Hur ska du upprepa framgångarna.



## Negativa erfarenheter

Här beskriver du det som du anser har gått mindre bra med ditt projekt och analyserar hur du kan undvika detta i framtida projekt.

## Sammanfattning

Här redovisar du dina slutsatser, erfarenheter och lärdomar. Reflektera över din produkt och dess/dina utvecklingsmöjligheter.
Vad kan vidareutvecklas och finns det utrymme att bygga vidare på projektet.