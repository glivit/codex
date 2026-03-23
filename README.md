# Codex Asbestinventaris Generator

Interactieve tool voor het genereren van professionele codex-documenten (asbestinventaris) conform de Codex Welzijn op het Werk en het OVAM-inspectieprotocol.

## Gebruik

Open `index.html` in een browser of bezoek de live versie op GitHub Pages.

Vul het formulier in met:
- Opdrachtgever en administratieve gegevens
- Situering en zones van het gebouw
- Plannen (upload plattegronden)
- Asbesttoepassingen met automatische OVAM-materiaalscore berekening
- Niet-asbestverdachte materialen
- Beperkingen van het onderzoek

Klik op "Genereer Codex (.docx)" om een volledig Word-document te downloaden.

## OVAM Materiaalscore

De tool berekent automatisch de materiaalscore per asbesttoepassing:

`((A + B) x C x D) x E`

- A = Categorie van gebondenheid (1-3)
- B = Asbestsoort (1-3)
- C = Afschermingsgraad (0.5-6)
- D = Toestand materiaal (1-10)
- E = Asbestconcentratie (1 of 1.6)

## Deployment

Dit is een volledig standalone HTML-bestand (geen server nodig). Werkt via GitHub Pages, Netlify, of lokaal.
