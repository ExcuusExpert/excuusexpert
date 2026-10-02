# ExcuusExpert

## Eigen Groq API-sleutel gebruiken

Bezoekers kunnen lokaal een profiel maken met hun naam en eigen Groq API-sleutel. Het profiel en de smoesgeschiedenis (maximaal 30 items) worden in `localStorage` van die browser bewaard; ze synchroniseren niet met andere apparaten. De sleutel wordt rechtstreeks naar Groq gestuurd, niet naar de website. Hij staat lokaal niet versleuteld opgeslagen, dus gebruik deze optie niet op een gedeeld apparaat.

Zonder sleutel blijven de vaste onderwerpen werken met de ingebouwde generator. Voor AI-generatie bij vaste onderwerpen of een zelfgekozen onderwerp is een geldige Groq API-sleutel nodig.

De API wordt rechtstreeks vanuit de browser aangeroepen, dus een serverfunctie is niet nodig. Profiel verwijderen wist de naam en sleutel; de geschiedenis kan apart worden gewist. De sleutel blijft zichtbaar voor de gebruiker die hem invoert en voor browserontwikkelaarstools.