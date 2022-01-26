# Ledarpanel

När man loggar in som ledare för en nod eller DCP omdirigeras man till en ledarpanel. I ledarpanelen hittar man följande:

- Mina noder (endast om användaren är en ledare i minst en nod)
- DCP skickat
- Överblick av DCPer
- MPP sparad

![Leader panel](pics/panel.png)

## Mina noder

En nod är en organisatorisk enhet, t.ex. avdelning, sektion, projekt, arbetsgrupp. Noder länkas i en struktur där en nod kan ha en eller flera undernoder, t.ex. en hierarkisk organisation. En nod kan vara permanent eller tidssatt, det vill säga, ha ett slutdatum.

Användaren kan under "Mina Noder" se alla noder för vilket användaren är ledare för.

Varje nod har en status. Nodens status kan vara utkast, aktiv eller stängd.

När användaren vill stänga en nod är det nödvändigt att alla undernoder kopplat till noden stängs och alla MP:s kopplas ifrån noden.

För att redigera en nod, tryck på de tre prickarna vid nodens namn och sedan på "redigera".

För mer information om hur man redigerar en nod: [Klicka här](edit_node.md){ .md-button .md-button--primary}

För att öppna och få mer utförlig information om en nod så kan man trycka på "Öppna" istället för redigera. För mer information om noder: [Klicka här](node.md){ .md-button .md-button--primary}

### Visa nodstruktur

Med den här funktionen kan användaren se den grafiska nodstrukturen från vald nod. Följande exempel visar konsultföretaget HighValue med olika team och för Team Digital och Team Finance också deras kundteam. Den valda noden har en röd kant.

![Leader panel](pics/strukt.png)

### Skapa nya noder
<!---Skall detta kanske ligga under redigera nod? eller egen--->
Genom att klicka på knappen "Lägg till" öppnas ett popup-fönster och ledaren kan skriva in all information som behövs för att definiera nästa nod, såsom:

- Beskrivning av noden
- Modernod

Genom att klicka på knappen "Spara" skapas den nya noden och användaren omdirigeras till en ny sida som innehåller nodens:

- Nodinformation
    - Namn
    - Status (utkast, aktiv eller stängd)
    - Tid
    - Slutdatum (inte synlig om tiden är permanent)
    - Modernod
    - Ledare
- Kompetensegenskaper för nodens kulturprofil
- Kompetensegenskaper för nodens generella kontext

Kultur och generell kontext ärvs av modernod.

## DCP skickad

I denna panel listas de DCP:er som skickas ut av en ledare/distributör.
Data är tillgängliga i den här listan tills en ny MP är ansluten till DCPn.
I listan finns följande data:

- Namn på DCP
- Namn på kopplad MP
- Datum när DCPn är skickad
- Status

<!---Vad för status?--->

## Mina DCPer

I panelen "Mina DCPer" finns ett cirkeldiagram som sammanfattar statusen där användaren är ledare eller distributör.
Genom att klicka på knappen "Mina DCPer" kan användaren se listan över alla sina DCPer.

För mer information om DCP-status: [DCP-status](DCP-status.md){ .md-button .md-button--primary}

## MPP sparad
<!---Svårtolkad text--->
I det här avsnittet kan ledare/distributören se MPP som är sparade.
Ledare kan spara en MPP i Scan MPPs genom att klicka på bokmärkesikonen nedan.

-------------------------------
