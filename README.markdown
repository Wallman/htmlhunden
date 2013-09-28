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
Den h�r processen beh�ver automatiseras, men f�r nu kr�vs tre steg ifall man vill l�gga till ett nytt kapitel.

1. Skapa en ny .jade-fil i `src/chapters/**/*.jade` och se till att den inneh�ller ett html-ankare med samma namn som filnamnet.

1. Inkludera den nya filen i `src/index.jade` (var noga med att filerna hamnar i r�tt ordning)

1. L�gg till en l�nk som pekar p� ankaret i filen `src/table-of-contents.jade`