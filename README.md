# Elevspel – vård och omsorg

Webbspel där elever i vård- och omsorgsutbildningen tränar ord och begrepp. Fungerar på Chromebook, dator och mobil. Ingen inloggning och ingen datainsamling. Framsteg sparas bara lokalt i webbläsaren.

Framsida: https://katzbagel.github.io/elevspel/

- `index.html` – framsidan där eleven väljer spel. Spelen listas i objektet `SPEL` högst upp i skriptet. Ett nytt spel läggs i en egen mapp och får en rad där.

## Ett pass – ett arbetspass i hemtjänsten eller på särskilt boende

Adress: https://katzbagel.github.io/elevspel/ett-pass/

- `ett-pass/index.html` – hela spelet. Innehållet ligger högst upp i skriptet: `PLATSER` (arbetsplatser, brukare, rum) och `FALL` (situationerna). Lärarläge: lägg till `#larare` i adressen.
- `ett-pass/bilder/` – illustrationer i WebP-format.

## Skillnaden – ord som ligger nära varandra

Adress: https://katzbagel.github.io/elevspel/skillnaden/

Mappen `skillnaden/` är ett eget spel för de svårare och mer abstrakta begreppen. Eleven tränar på skillnaden mellan ord som ligger nära varandra, till exempel symtom/tecken och kurativ/palliativ.

- **Läge 1 – Sortera:** läs en situation och välj vilket av två ord som passar.
- **Läge 2 – Fyll i:** välj rätt ord i rätt form i en mening.
- **Läge 3 – Välj exemplet:** läs ett ord och välj den situation som passar.

En grupp öppnas i nästa läge när eleven har högst ett fel på första försöket. Lägg till `#larare` sist i adressen för att öppna alla grupper.

Innehållet ligger i objektet `GRUPPER` högst upp i skriptet i `skillnaden/index.html`.
