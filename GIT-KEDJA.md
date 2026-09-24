
#1 Initiera ett nytt lokalt Git-repo (om du inte redan har gjort det i mappen)

git init

#2 Lägg endast til de specifika filerna (inga dolda filer eller skräp)

git add Main.java README.md

#3 Gör en commit med ett tydligt meddelande.

git commit -m "Detta är vad jag ändrat."

#4 Sätt huvudbranchen till Main.

git branch -M main

#5 Koppla ditt lokala repo till ditt publika GitHub-repo.

git remote add origin https://github.com/SarahNaevdal4160/Git-och-Github---uppgift1.git

#6 Gör en push utan --force.

git push -u origin main






Steg 4 — Reflektion (4 meningar)

#1 Vad var fel eller farligt i AI-förslaget (eller snutten)?

AI-förslaget var farligt eftersom det sparade en hemlig API-nyckel i Git-historiken och använde en osäker force-push som riskerar att skriva över din och andras kod. 

#2 Vad ändrade du?

Jag lade endast till specifika filer, kopplade till mitt eget GitHub-repo, ändrade till en vanlig push (utan force), tog bort den nya grenen och hanteringen av API-nyckeln och lät repot vara publikt. 

#3 Varför är publikt repo + begripliga commits viktigt inför Exam 1?

Dessa är viktiga för att läraren ska kunna se mitt repo och snabbt förstå vilka ändringar jag gjort när. 

#4 Varför är force push och commitade hemligheter dåliga idéer även “bara för övning”?

Det är dåliga idéer för att man kan skapa däliga vanor som kan orsaka stora problem i framtiden. 
