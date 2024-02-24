# KlassePunten

Maak een applicatie om de gegevens in te lezen, de punten te verwerken
en de resultaten terug weg te schrijven.

![](./media/image1.png)

Je maakt voor deze toepassing eerst de (basis)klasse **PuntenAdmin** met
volgende [eigenschappen]{.underline}:

-   **Familyname** - string.

-   **Firstname** -- string.

-   **Gender** - string .

-   **Email** -- string.

-   **Score** -- integer (behaalde punten)

-   **TotalScore** -- integer (puntentotaal)

De klasse Punten bevat volgende [methods]{.underline}:

-   Constructor **PuntenAdmin** in 2 vormen: één zonder parameters
    waarbij een lege klasse gecreëerd wordt en één met 6 parameters (de
    6 eerder beschreven eigenschappen).

-   **Percent --** float (berekent het behaald percentage vb. 72,50%)

-   **Grade** -- string (geeft "Geslaagd" als je min. 80% hebt anders
    "Niet geslaagd")

![Afbeelding met tekst, schermopname, scherm, software Automatisch
gegenereerde beschrijving](./media/image2.png)

![Afbeelding met tekst, elektronica, schermopname, scherm Automatisch
gegenereerde
beschrijving](./media/image3.png)

De knop *Inlezen* leest o.b.v. een OpenFileDialog een bestand in. Van
elk record in dit bestand wordt een instance gemaakt van de klasse
PuntenAdmin. Elk object dat je aanmaakt voeg je toe aan een List\<\> van
het type PuntenAdmin.

De knop *Verwerken* gaat een CSV bestand wegschrijven met 3 velden:
achternaam+voornaam (gescheiden door een spatie), percentage en
geslaagd.

De locatie en naam van het bestand wordt gevraagd in een SaveFileDialog.
Wanneer het bestand al bestaat wordt gevraagd of dit overschreven mag
worden.

![Afbeelding met tekst, schermopname, Lettertype, software Automatisch
gegenereerde
beschrijving](./media/image4.png)

Na het correct wegschrijven wordt een bericht getoond.

![Afbeelding met tekst, schermopname, Lettertype, software Automatisch
gegenereerde
beschrijving](./media/image5.png)

De knop *Nalezen* laat een bestand openen met een OpenFileDialog scherm
en toont dit in het tekstvak.

![Afbeelding met tekst, schermopname, scherm, software Automatisch
gegenereerde beschrijving](./media/image6.png)
