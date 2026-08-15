## 15 april
finished tutorial

## 16 april 15:30
Heb nagedacht over wat ik wil doen. Wou niet iets te moeilijk want ik ben een complete beginner. Heb uiteindelijk besloten om sounds toe te voegen omdat ik online las dat dat nog oké is voor een beginner + het spel is enorm saai zonder geluid. Heb wat sounds opgezocht en verder gekeken hoe ik deze twee dingen moet toepassen. Heb gekeken naar verschillende mogelijkheden en dit leek me het meest haalbaar voor mij.

## 16 april 17:30
Heb besloten waar ik soundbites wou afspelen en er verschillende gedownload voor de game.

## 17 april 10:00
Ben aan opzoeken hoe ik moet proberen de sound toe te voegen en ik wou ook wat meer pacing toevoegen aan het spel want alles gebeurd precies instantly en dat vind ik niet echt fijn.

## 17 april 15:00
Het spel werkte uiteindelijk nietmeer. 1. het spel stopte gewoon nooit en bleef kaarten trekken, 2. het optellen van de kaarten kloptte nietmeer. Wist nietmeer hoe ik het moest oplossen dus ik heb alles weg moeten doen/gereverted naar een oudere file. 

## 3 augustus 12:05
Ik heb een folder gemaakt met de sound bites erin.

## 3 augustus 14:00
pygame wilt de geluiden niet openen/vindt ze niet. Oplossingen aan het zoeken

## 4 augustus 09:00
Heb uiteindelijk een oplossing gevonden

## 4 augustus 9:30
Experimenteren met het afspelen van geluiden en het vinden van de juiste locatie in de code.

## 4 augustus 11:00
De geluiden zijn geprogrammeerd

## 4 augustus 12:30
Verkennen van mogelijke uitbreidingen. Heb verschillende mogelijkheden en hoe ik deze zou moeten toevegen opgezocht (zoals betting system of animaties toevoegen) maar dit leek me niet beginner-friendly.

## 4 augustus 14:30
Heb besloten om kaartsymbolen toe te voegen en heb deze in een deck gestoken in de code. Ervoor had ik eerst een andere oplossing waarbij ik de symbolen in een apart deck stak en hier random een symbool uit trok en apart opsloeg maar ik moest te veel aan de code aanpassen en toevoegen en snapte het ook niet echt helemaal. Ik heb toen dus nagedacht over een andere manier en alle wijzigingen weg gedaan/terug hersteld. Heb nu dus nieuwe decks gemaakt voor de symbolen en gekeken of de waarde van de kaarten nog steeds berekend worden met het nieuwe deck; ik heb hiervoor aanpassingen gemaakt in de code. De symbolen willen enkel niet tonen als ik de game run; ben aan het kijken/opzoeken waarom het niet lukt.

## 4 augustus 17:30
Heb de fout gevonden en de font aangepast en in sounds folder gezet omdat het niet wou werken en python het niet kon vinden in de directory. Heb de game nu nog eens gespeeld; de symbolen verschijnen, maar de score is soms met 10 verhoogd dus dit moet ik nu ook uitzoeken.

## 4 augustus 18:30
Heb eerst zelf geprobeerd de fout te vinden en het aan te passen maar dit lukte niet. Uiteindelijk aan chatgpt gevraagd. Die had die fout gevonden en een suggestie voorgesteld. Het werkt nu fatsoenlijk.

## 5 augustus 10:30
De aangepaste font past nu niet meer fatsoenlijk in de kaarten. In de buttons staan ze ook niet mooi. Ik wil nu de grootte van het font, de kaarten, of de plaats van het font aanpassen. Ik wil ook keyboard integratie toevoegen.
ESC = game sluiten
space = deal hand/new hand
left arrow = hit me
right arrow = stand

## 5 augustus 14:00
Wil text-to-speech toevoegen voor win/lose/tie, heb opgezocht hoe je dit kon doen. Eerste poging werkte, maar enkel bij de eerste keer dat je het spel speelde en stopte dan als je meerdere keren wou spelen in 1 sessie. Hier heb ik een oplossing voor gevonden en nu werkt het.