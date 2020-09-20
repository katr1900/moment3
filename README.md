# Uppgift 3
## i kursen Webbutveckling III



## Användning

För att komma igång klona projektet till din lokala dator. Du behöver Git, Node och NPM installerat på din dator för att det ska fungera. Öppna sedan en terminal och navigera till katalogen för projektet. Kör där

```
npm i
```

Det här installerar alla filer som behövs. För att starta projektet kör

```
./node_modules/gulp/bin/gulp.js
```

Det här startar en webläsare på localhost:3000 och en default watch-task som håller koll på alla ändringar av CSS, JS och HTML-filer i projektet.

Projektet är en webbapplikation som är en TODO-app. Man kan lägga till och ta bort TODOs i en lista. Källkoden i ligger i source-mappen. När gulp körs så byggs filerna ihop och flyttas till pub-katalogen.