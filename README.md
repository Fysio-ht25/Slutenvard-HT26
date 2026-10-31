# Fysioterapi i slutenvård – datum och övningar

Fysioterapi i slutenvård (1FY027), HT26. Startsidan leder till en sida per KTC (NKS Solna, Södersjukhuset, Karolinska Huddinge, Danderyds sjukhus) med dess VFU-platser, KTC-vecka, viktiga datum och kalenderfil. Vid skillnad gäller schemat i Canvas.

- **Övningar:** processen och ICF, fortsätt, anpassa eller avbryt, KMT, patientområden, etik.
- **Tema:** mörkt som standard, ljust via knappen uppe till höger.
- **Integritet:** sidorna har inga textfält. Det enda som sparas, i din egen webbläsare, är om du valt ljust tema. Inga cookies. Inga namn på personal eller kurskamrater och inga patientuppgifter.

## Bygga

Datum och lokaler finns i `platser.py`, övningarna i `ovningar.py`. Kör sedan:

```
py -X utf8 build.py
```

Redigera aldrig `.html` eller `.ics` för hand.
