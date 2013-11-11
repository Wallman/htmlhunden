# README

## Dependencies
Detta projekt kr�ver `node`, `npm` och `grunt-cli`.

### Installera Grunt
`$ npm install -g grunt-cli --save dev`

### H�mta �vriga dependencies
`$ npm install`

## Tasks
- `$ grunt` Lyssnar p� filf�r�ndringar, kompilerar jade-filer, och k�r en server p� `localhost:9001`

## F�r att skapa ett nytt kapitel
Den h�r processen beh�ver automatiseras ytterligare men f�r nu

1. Skapa en ny .jade-fil i `src/chapters/**/*.jade` och se till att den inneh�ller ett html-ankare med samma namn som filnamnet. Algoritmen som anv�nds f�r att f�rvandla titlar till ankare �r f�ljande, (1) lowercase, (2) ers�tt " " med "-", (3) ta bort alla tecken utom 0-9 och a-z. Allts�: `Hali hall�!` blir `hali-hall`.

1. Inkludera den nya filen i `src/index.jade` d�r du vill.