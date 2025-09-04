Fråga 3: Vad innebär samarbete med GitHub? Vad är pull requests, branches och merge?
GitHub används ofta i team för att flera utvecklare ska kunna jobba på samma projekt utan att skriva över varandras kod. Man gör det genom att:

Arbeta på egna branches

Göra ändringar

Skicka en pull request för att föreslå att ändringarna ska in i huvudkoden

Någon i teamet granskar och godkänner → ändringarna mergas in. 

Branch: 
-Parallel tidslinje av ett projekt.
-Man kan skapa en branch för att jobba på en ny feature utan att påverka huvudkoden (main branch).
-Varje branch kan ha sin egen version av koden.
-Branches kan skapas, bytas och tas bort.
-Branches kan mergas in i main branch när de är klara och då kan någon annan i teamet granska ändringarna innan de mergas in.

PR: 
- En begäran om att få merge:a en branch in i main branch. 
- Teamet kan diskutera,kommentera och granska ändringarna innan de mergas in.
- När PR är godkänd kan ändringarna mergas in i main branch.



Merge:
- Merge är processen att kombinera ändringar från en branch in i en annan branch. (oftast till main branch)
Fråga 2: Fråga 3: Vad innebär samarbete med GitHub? Vad är pull requests, branches och merge?
GitHub används ofta i team för att flera utvecklare ska kunna jobba på samma projekt utan att skriva över varandras kod. Man gör det genom att:

Arbeta på egna branches

Göra ändringar

Skicka en pull request för att föreslå att ändringarna ska in i huvudkoden

Någon i teamet granskar och godkänner → ändringarna mergas in. 

Branch: 
-Parallel tidslinje av ett projekt.
-Man kan skapa en branch för att jobba på en ny feature utan att påverka huvudkoden (main branch).
-Varje branch kan ha sin egen version av koden.
-Branches kan skapas, bytas och tas bort.
-Branches kan mergas in i main branch när de är klara och då kan någon annan i teamet granska ändringarna innan de mergas in.

PR: 
- En begäran om att få merge:a en branch in i main branch. 
- Teamet kan diskutera,kommentera och granska ändringarna innan de mergas in.
- När PR är godkänd kan ändringarna mergas in i main branch.


Fråga 2: Vad är ett Git-commit och varför är det viktigt?
Beskriv ett verkligt scenario där Git hjälper dig undvika problem.
Ett Git-commit är en ändring i vår Git – repo. När du commitar så sparas ändringar i fil,när och vem har gjort ändringen. Vi får även ett commit-meddelande som ger oss möjligheten att förklara varför ändringen har gjorts. Ändringarna kopplas även till egen ID. Det är viktigt för att följa utveckling över tid. Man kan alltid backa till en gammal version om den nya inte fungerar. Flera utvecklare kan jobba på samma kod. 
: Man jobbar på ett projekt och ändrar något i koden för att göra en förbättring. Efter ett tag så märker jag att hela programmet har slutat funka. Eftersom alla våra commit har tidigare sparats i Git kan vi enkelt gå tillbaka och kolla hur koden såg ut innan. Vi kan även gå tillbaka till den fungerade versionen direkt. Detta gör att vi sparar mycket tid och kan få projektet att funka direkt. Utan Git hade vi behövt hitta exakt vart och vad vi ändrade manuellt. Det blir rörigt och tar långt tid att åtgärda. 

Fråga 1: Beskriv skillnaden mellan vattenfallsmodellen och agil metodik.
När bör man använda vilken, och varför?
Vattenfall: Skulle jag använda mig av vattenfall metoden för ”insta” så skulle jag göra så här:
•	Lägga upp en plan, vilka delar/funktioner behöver jag för appen. Vilken design vill jag använda mig av eller kund vad vill.
•	Hade då börjat i vad jag tycker är rätt ordning på funktioner och så fort en blir klar så går jag vidare till nästa.
•	Låt oss börja först och främst med design och hur det ska se ut.
•	När design är klar kan vi gå vidare till nästa steg som login.
•	Vi utför då våra koden i stegvis tills vi gör klart varje steg.
•	När alla steg är klara kan appen lanseras.
o	Vattenfall passar bäst när: Kraven är tydliga ocg fasta redan från början.Projektet är kortare och enklate.
Agil: Här behöver jag inte göra att i steg viss och vänta till varje steg är färdig.
•	Självklart så behöver man en plan här med däremot kan vi dela upp varje steg i små sektioner som ge oss möjlighet att vara flexibla och kunna gå tillbaka för att till exempel ändra på design eller login vid önskan.
•	Denna metod ger oss fördelarna på att kunna jobba med olika saker samtidigt och inte behöva boka av allt i stegvis utan kunna lätt hoppa från login till likes för att sedan gå vidare till upplägg av bilder.
•	Nu kan jag testa mig fram och tillbaka bygga login eller upplägg av bilder men gå tillbaka och ändra om inte jag är nöjd.
•	Här har jag möjligheten att lansera utan och vara klar med alla steg för att få feedback från användare.
•	Agil passar bäst när: Kraven är otydliga eller kan förändras under projektets gång. Projektet är längre och mer komplext.Kunden behov kan utvecklas under tiden.


