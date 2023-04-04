# POST MORTEM
Rasmus Johansson
03-03-2023

## Inledning
Syftet med detta arbete var att i grupp skapa en login sida där man kunde logga in, logga ut och skapa ett konto. Detta för att lära oss mer om databaser, routes, sessioner och CRUD principer.

I detta arbete fick vi även använda oss av tests för att validera vår kod. Dessa tests var uppdelade i olika delar så att vi snabbt och enkelt kunde validera olika delar av koden utan att behöva t.ex. skapa och ta bort nya användare hela tiden för att se till att inloggningen fungerar.

Eftersom att vi bara kodade med en dator fick vi byta av varandra efter att en viss tid gått.

## Bakgrund
Arbetet började med att vi skulle förbereda en planering över hur hemsidan skulle fungera. Vi planerade de eventuella routes, views och tabeller vi skulle använda oss av. Vi försökte även planera hur de olika routesen skulle fungera. När vi väl var klar med planeringen forkade vi detta repository och började jobba på det första testet.

Det första testet gick bara ut på att få igång servern och få den att visa upp texten 'Login ALC'. Den testade även krypterings funktionen vilken vi skulle använda för att kryptera lösenorden.
Testet gick bra och vi blev ganska snabbt klar med det.

Det andra testet vi gjorde gick ut på att ansluta till en databas och sedan hämta information där ifrån. Vi skulle skapa ett login formulär och sedan koppla det till javaScriptet med hjälp av cookie-parser paketet. Vi hade till början lite problem med att ansluta till databasen men vi lyckades eventuellt lösa detta efter att vi uppdaterat testen och lyckats ansluta databasen rätt, att hämta den information som krävdes från databasen gick ganska bra och vi blev eventuellt klar. 

Det tredje testet gick ut på att med hjälp av cookies faktiskt logga in användaren och sedan spara inloggningsinformationen i en cookie. Vi började med att göra en profilsida som visade upp den inloggade användarens namn och en utloggningsknapp. Vi hade lite problem med att spara informationen i cookies men vi lyckades lösa det tillslut.

Det fjärde och sista testet gick ut på att på att göra ett registrerings formulär. Detta gick ganska bra och vi blev ganska snabbt klar. 

## Positiva Erfarenheter
Jag tycker att grupparbetet gick ganska bra, när vi väl började förstå oss på hur det fungerade med sessioner och databaser gick testen bra tycker jag.

## Negativa Erfarenheter
Ett problem vi mötte på grund av storleken av gruppen var att det var svårt att få alla i gruppen att förstå. Vi hade även i början vissa problem med att anropa databasen.

## Sammanfattning
Sammanfattningsvis tycker jag att detta arbete gått bra och vi har fått lära oss en mängd viktiga saker. Vi lyckades klara alla test, dock finns det viss finslipning som går att göra. Grupparbetet tycker jag gick bra.
