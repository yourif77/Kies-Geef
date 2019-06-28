# Hoe kan het platform automatisch incasseren bij gebruikers?

### Inleiding

Om deze vraag te beantwoorden ben ik gestuit op de website van PayPro: [https://guide.paypro.nl](https://guide.paypro.nl). Via dit platform zijn er vier verschillende manieren om gebruikers van mijn platform automtaisch te incasseren. Voordat ik hier verder op in ga moet ik eerste twee andere zaken vermelden. Het is van groot belang dat klanten een machtiging afgeven. Dit zouden ze bijvoorbeeld kunnen doen wanneer ze een account aanmaken via de app. Daarnaast moet het duidelijk zijn hoevaak en hoelang een klant geïncasseerd zal moeten worden. Dit aspect is bij mijn platform anders, omdat de klant dit zelf kan bepalen.

Bij PayPro zijn er vier verschillende manieren om geld bedragen automatisch bij gebruikers te kunnen incasseren: Via een factuur + betaallink, via een betaallink, Via een batch en via een API.

### **Via een factuur + Betaallink**

Met deze methode maak je een facturen op die naar de gebruiker gestuurd kan worden. Deze kan vervolgens met iDeal betaald worden als eerste termijn. Hierbij wordt een link geleverd die de gebruiker kan gebruiken om daadwerkelijk te betalen.

### **Betaallink**

Dit werkt het zelfde als de methode hierboven, alleen wordt hier niet gebruik gemaaktvan de facturen dienst.

### **Via een batch**

Als je gebruikt maakt van een batch, maak je gebruik van een XML bestand. Mij platform houdt \(automatisch\) bij wat gebruikers willen dat er afgeschreven moet worden en dit wordt opgeslagen in een XML bestand. Dit bestand kan weer ingeleverd worden bij PayPro, waarna het juiste bedrag kan worden afgeschreven.

### **Via een API**

Het is ook mogelijk om het systeem te kopppelen via een API van PayPro, maar zitten hier nog wel een aantal haken en ogen aan vast. Ik heb contact opgenomen \(via mail\) met PayPro om te vragen of het mogelijk is om de gebruikers het bedrag te kunnen wijzigen. Hier werd mij vertelt dat dit niet kan, maar dat dit wel kan met een XML bestand. Ik heb met een back-end programmeur gezeten en samen uitgezocht en het is wel mogelijk om het via de API te laten werken, maar moet hier wel in de code mee gerommeld worden. 

### **Conclusie**

Ik ben van mening dat optie 3 of optie 4, mits dit te doen is met de code, de beste oplossing is om het platform Kies&geef op te laten werken. Bij de eerste twee opties is het niet mogelijk om het bedrag aan te kunnen passen, wat wel essentieel is voor mijn platform.

## Mailen met payPro, Quido

### Inleiding

Zoals ik al vertelde heb ik contact opgenomen met PayPro om wat dieper in de stof te duiken. Het was voor mij niet duidelijk of het mogelijk is om de gebruikers het bedrag aan te kunnen passen en heb ik hier mail contact over gehad: 

### Mailcontact met Quido

Beste mevrouw/meneer, 

Ik heb een vraag over automatische afschrijvingen. Is het mogelijk om het bedrag van een automatische afschrijving, door de klant zelf, te laten wijzigen? 

Met vriendelijke groet, Youri



_Dag Youri,  
  
Dit is helaas niet mogelijk._

_Ik hoop je vraag/opmerking hiermee voldoende beantwoord te hebben. Laat het me weten als ik meer voor je kan betekenen!_

_Met vriendelijke groet, Quido_

\_\_

Beste Quido,

Is het wel mogelijk om dit door het bedrijf, die de automatische afschrijving incasseert, te laten doen bij de klant? Een klant geeft bijvoorbeeld aan dat de automatische afschrijving van 10 euro naar 15 euro verandert dient te worden en dat het bedrijf dit dan \(eventueel automatisch\) aanpast bij PayPro bij de klant, waardoor het bedrag alsnog is veranderd?

Met vriendelijke groet,

Youri



_Dag,_

_Je kunt er voor kiezen om te incasseren doormiddel van een batch, dan levert je elke maand een XML bestand aan bij ons met het bedrag dat dient te worden geïncasserd voor al jou klanten._

_Met vriedenlijke groet, Quido_

