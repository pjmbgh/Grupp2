### **Introduktion till Git och GitHub**

I den moderna utvecklingsvärlden är versionshantering en grundläggande färdighet för alla som arbetar med kod, oavsett om det handlar om enskilda programmerare, team av utvecklare eller stora företag. Git och GitHub är två av de mest använda verktygen inom detta område. I denna text går vi igenom vad Git är, hur det fungerar, vad GitHub tillför och varför dessa verktyg är så viktiga i dagens utvecklingsmiljöer.



Vad är Git?

Git är ett distribuerat versionshanteringssystem som skapades av Linus Torvalds 2005, ursprungligen för att hantera utvecklingen av Linux-kärnan. Det är ett kraftfullt verktyg som gör det möjligt att spåra ändringar i filer, samarbeta med andra utvecklare och hantera olika versioner av ett projekt på ett effektivt och säkert sätt.



En av de största fördelarna med Git är att det är distribuerat. Det innebär att varje utvecklare har en fullständig kopia av hela projektets historik, inte bara de senaste ändringarna. Detta ökar säkerheten och möjligheten att arbeta offline, samt gör det enkelt att återgå till tidigare versioner av koden vid behov.



Grundläggande begrepp i Git

För att förstå hur Git fungerar behöver man känna till några centrala begrepp:



Repository (repo): Ett Git-repository är ett projekt med versionshistorik. Det kan vara lokalt på din dator eller ligga på en server.



Commit: En commit är en ögonblicksbild av projektets tillstånd vid en viss tidpunkt. Den innehåller information om vad som har ändrats och av vem.



Branch: En branch (gren) används för att arbeta på en separat version av koden, t.ex. för att utveckla en ny funktion utan att påverka huvudversionen (ofta kallad main eller master).



Merge: När du är klar med en ändring i en gren kan du slå ihop den med huvudgrenen genom att göra en merge.



Staging area: En mellanliggande zon där du kan förbereda ändringar innan du committar dem.



Remote: En fjärrserver som innehåller en kopia av projektet, t.ex. GitHub.



Varför använda Git?

Git löser flera vanliga problem som uppstår vid mjukvaruutveckling:



Det är lätt att ångra misstag genom att gå tillbaka till en tidigare commit.



Flera utvecklare kan arbeta parallellt på olika delar av koden utan att störa varandra.



Det blir enklare att dokumentera vad som har ändrats, när och av vem.



Git ger en tydlig historik över ett projekts utveckling, vilket är användbart både för felsökning och planering.



Vad är GitHub?

GitHub är en molnbaserad plattform för att lagra Git-repositories och samarbeta kring kod. Det är inte samma sak som Git, men det bygger på Git och ger ett grafiskt användargränssnitt samt ytterligare funktioner för samarbete och projektledning.



Med GitHub kan utvecklare ladda upp sina projekt till molnet, dela dem med andra, samarbeta genom pull requests, hantera buggar och planera nya funktioner med issues och projektboards. GitHub är särskilt populärt i open source-världen, där tusentals projekt är fritt tillgängliga för vem som helst att bidra till.



Skillnaden mellan Git och GitHub

Git	GitHub

Versionshanteringssystem	Webbtjänst för att hantera Git-repositories

Körs lokalt på datorn	Kräver internetanslutning

Öppen källkod	Proprietär tjänst (gratis med premiumversioner)

Styr projektets historik	Hjälper till med samarbete och visuell hantering



Med andra ord: Git är motorn, GitHub är bilen du kör den med.



Så fungerar arbetsflödet med Git och GitHub

Initiera ett projekt med Git:

När du startar ett nytt projekt kan du skapa ett Git-repository med kommandot git init.



Lägg till och committa filer:

Du kan lägga till ändringar till staging-området med git add och sedan spara dem med git commit.



Koppla till ett GitHub-repo:

Med git remote add origin \[url] kopplas ditt lokala repo till GitHub.



Push och pull:



git push skickar dina ändringar till GitHub.



git pull hämtar uppdateringar från GitHub till din lokala kopia.



Branching och pull requests:

På GitHub kan du skapa en ny branch för att arbeta på en funktion, och sedan skicka en pull request för att be någon granska och slå ihop den med huvudgrenen.



Fördelar med GitHub

* Samarbete: Flera utvecklare kan bidra till samma projekt på ett organiserat sätt.



* Open source: Tusentals fria projekt är tillgängliga att studera, använda eller förbättra.



* Pull requests: En strukturerad process för att föreslå ändringar och få dem granskade.



* Issue tracking: Hantera buggar och förbättringar på ett tydligt sätt.



* CI/CD-integration: GitHub kan kopplas till verktyg för att automatiskt testa och bygga kod.



Alternativ till GitHub

GitHub är inte det enda alternativet för att lagra Git-repositories. Några andra populära tjänster är:



GitLab: Erbjuder liknande funktioner som GitHub men är också tillgängligt som egeninstallation.



Bitbucket: Används ofta i företag, med stöd för både Git och Mercurial.



Azure DevOps: Microsofts plattform för kodhantering och CI/CD.



Sammanfattning

Git och GitHub är idag standardverktyg inom mjukvaruutveckling. Git ger ett stabilt och kraftfullt sätt att hantera versionshistorik och kodförändringar, medan GitHub möjliggör effektivt samarbete, kodgranskning och projekthantering. Tillsammans ger de utvecklare möjlighet att arbeta strukturerat, spåra förändringar och samarbeta oavsett var i världen man befinner sig. För den som vill lära sig programmera är det därför viktigt att snabbt bli bekant med dessa verktyg och deras arbetsflöden.

