# Ett pass – elevspel för vårdord

Webbspel där elever i vård- och omsorgsutbildningen tränar ord och begrepp genom ett arbetspass i hemtjänsten. Fungerar på Chromebook, dator och mobil. Ingen inloggning och ingen datainsamling. Framsteg sparas bara lokalt i webbläsaren.

- `index.html` – hela spelet. Innehållet (uppdrag, ord, förklaringar) ligger i objektet `PASS` högst upp i skriptet.
- `bilder/` – illustrationer i WebP-format.

## Skillnaden – ord som ligger nära varandra

Mappen `skillnaden/` är ett eget spel för de svårare och mer abstrakta begreppen. Eleven tränar på skillnaden mellan ord som ligger nära varandra, till exempel symtom/tecken och kurativ/palliativ.

- **Läge 1 – Sortera:** läs en situation och välj vilket av två ord som passar.
- **Läge 2 – Fyll i:** välj rätt ord i rätt form i en mening.
- **Läge 3 – Välj exemplet:** läs ett ord och välj den situation som passar.

En grupp öppnas i nästa läge när eleven har högst ett fel på första försöket. Lägg till `#larare` sist i adressen för att öppna alla grupper.

Innehållet ligger i objektet `GRUPPER` högst upp i skriptet i `skillnaden/index.html`.
