# Tehtava5

TuotekuvastoApp on simppeli ASP.NET Core web sovellus joka toimii tuote luettelona. 
HomeController.cs hakee tuote tiedot products.json tiedostosta ja palauttaa View:n tuotteista.
Product.cshtml tekee tuotteista HTML tiedoston joka näyttää tiedot sille säädetyssä muodossa.

Ominaisuuksiin kuuluu
-Näyttää listan tuotteista nimillä, kuvauksilla, hinnoilla ja kuvilla.
-Käyttää Newtonsoft.Json kirjastoa deserialoisimaan (deserialize) tuote tietoja JSON tiedostoista.
-Dynaaminen tuotteiden näyttö Razor View:n avulla 

Asennus
1. Kloonaa arkisto
2. Asenna riippuvuudet (Newtonsoft.json kirjasto)

Käyttö
1. Suorita sovellus (dotnet run)

