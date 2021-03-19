## Hosting
* Sidan hostas med Github pages. :white_check_mark:
  * Alla resurser fungerar och använder relativa sökvägar. :white_check_mark:
  * Alla länkar fungerar. :white_check_mark:
  * Sidans innehåll och resurser hostas lokalt på Git eller använder en CDN. :white_check_mark:
* Inga bilder eller annat är länkade till andra webbplatser. :white_check_mark:

## Manuell granskning
* Sidan fungerar i ett par webbläsare. :white_check_mark:

  Jag har testat sidan i Edge, Chrome och Firefox. Den funkar i vardera webbläsare.
* Sidan fungerar på telefon. :white_check_mark:

  Jag testade sidan på min telefon och den tappar ingen funktionalitet.
* Kolla av checklistan, https://webbriktlinjer.se/testa-din-webbplats/ :white_check_mark:

  Under testet insåg jag att mina titel-taggar inte var semantiska, så jag ändrade detta. Jag förbättrade även tangentbords-navigeringen. Min sida fick 89 % på testet.

## Lagar och regler
* Sidan följer alla relevanta lagar och regler för publicering på webben. :white_check_mark:
  * Personuppgifter, GDPR. :white_check_mark:
  * Copyright. :white_check_mark:

## Validering
* Alla sidans dokument validerar som korrekt HTML. :white_check_mark:
  * https://validator.nu/.
    
    Under valideringen upptäckte jag att jag hade flera id:n som var likadana, samt att jag använde px-värden som width på `img`-element. Detta ändrade jag sedan. Jag märkte även att man inte fick ha mellanslag i href-property:n i `a`-taggar, vilket jag hade i mitt telefonnummer. Detta ändrade jag också.
* All CSS validerar som korrekt CSS. :white_check_mark:
  * https://jigsaw.w3.org/css-validator/.

    Min CSS validerade korrekt, men jag märkte att jag använde ett otillåtet värde på property:n `font-weight`, vilket jag fixade.
    
## Media
* Sidans media är optimerat. :white_check_mark:
* Bildstorlek och upplösning. :white_check_mark:
  * Ska bilden var 32 px x 32 px ska den vara det, inte 1920 x 1080. :white_check_mark:

  Jag fick skala ner mina porträtt-bilder då de var större än 350 px (som de är på sidan). Detta försämrade kvalitén, men nu är de iaf rätt storlek.
* Bildens format är anpassat efter bildtyp. :white_check_mark:
  * Inga bmp eller tga filer, är det rimligt att köra png 32 på porträtt? :white_check_mark:
  * SVG och vektorformat där det passar. :white_check_mark:
  * PNG där storleken tillåter :white_check_mark:
  * JPEG på foto. :white_check_mark:
* Sidans totala storlek är rimlig. :white_check_mark:
  * Devtools, throttle network, testa. :white_check_mark:

## Tillgänglighet
* Sidan har testats med Wave. :white_check_mark:
  * https://wave.webaim.org/. :white_check_mark:

  Jag fick kontrastfel som jag försökte fixade genom att göra färgen på min text mörkare, men gjorde jag den mörk nog slutade den vara orange och blev brun istället. Det jag lärt mig av det här är att det är viktigt att välja en bra färg från början, det är försent att ändra hela färgschemat nu.
  * Finns även som extension. :white_check_mark:
* Arbete är gjort för att begränsa och åtgärda kontrast-varningar. :x:
  * Motivera.

  Jag var inte nog noga med att välja kontrast-rika färger när jag gjorde designen. Detta skulle jag jobbat mer på, då det är svårt att ändra hela designen i det här stadiet. Jag skapade den här designen för längesen, innan jag kände till vikten av kontrast. I kommande arbeten kommer jag vara nogrannare med kontraster.
* Sidan använder semantiska strukturelement. :white_check_mark:
* Sidan är begriplig och fungerar utan:
  * CSS. :white_check_mark:
  * Javascript. :white_check_mark:
