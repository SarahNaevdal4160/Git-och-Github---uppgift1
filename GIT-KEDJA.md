
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

