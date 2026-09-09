# Webbplats om resor och städer 🌍

## Om projektet

## Om projektet

Jag skapade den här webbplatsen i Laboration 1 i kursen Webbutveckling vid Mittuniversitetet. Webbplatsen handlar om olika städer och innehåller text, bilder, länkar och en tabell.

I Laboration 2 har jag använt Git och GitHub för att versionshantera projektet. Jag har även arbetat i flera separata branch och sedan mergat mina ändringar till main.

## Tekniker och verktyg

I projektet användes:

- **HTML5** för webbplatsens struktur och innehåll
- **CSS3** för webbplatsens design och layout
- **Git** för versionshantering
- **GitHub** för att lagra projektet online

## Publicerade versioner

Webbplatsen är publicerad på följande plattformar:

GitHub: https://maida1991.github.io/moment-1-webbplats/
Netlify: https://splendid-moonbeam-9a6fca.netlify.app/

## Versionshantering

Först skapade jag en initial commit med webbplatsen från Laboration 1. Därefter skapade jag en separat branch med namnet 'feature/add-city-to-table'.

I den nya branchen lade jag till en ny stad i tabellen. Ändringen sparades i en commit och mergades sedan tillbaka till *main genom en Pull Request på GitHub.

## Frågor om Git

### Vad är skillnaden mellan git add och git commit ?

git add - väljer vilka ändringar som ska förberedas och inkluderas i nästa commit (vi har olika set att använda den 'git add --all', 'git add . ', eller om vi har flera filer som är ändrat vi kan välja med 'git add namn/påfilen')

git commit - sparar de valda ändringarna i projektets tillsammans med ett beskrivande meddelande, vi måste först gjora 'git add' att kunna gjora en commit

### Varför använder man branches istället för att jobba direkt i `main`?

Branches gör det möjligt att utveckla och testa ändringar utan att direkt påverka den stabila versionen i 'main'.är ändringen är färdig och kontrollerad kan den mergas till 'main'. Det minskar risken för att ofärdig eller felaktig kod publiceras.

### Vad händer rent praktiskt när man gör en merge?

Vid en merge kombinerar Git ändringarna från en branch med en annan branch.

I detta projekt mergades ändringarna från 'feature/add-city-to-table' till 'main'. Efter merge ändringar är på main branch.

### Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på exempelvis Netlify?

När man pushar till GitHub skickas projektets kod och commit-historik till ett repository på GitHub.

När webbplatsen publiceras på Netlify görs den tillgänglig på internet via en publik webbadress. Netlify kan kopplas till ett GitHub-repository och automatiskt publicera en ny version när ändringar pushas till 'main'

### Hur exkluderar man en fil från versionshanteringen?

För att exkludera en fil eller mapp från versionshanteringen lägger man dess namn eller sökväg i filen '.gitignore'.

Exempel:

```gitignore
.DS_Store
secret.txt
node_modules/