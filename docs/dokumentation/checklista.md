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
* Alla sidans dokument validerar som korrekt HTML.
  * https://validator.nu/.
    
    Under valideringen upptäckte jag att jag hade flera id:n som var likadana, samt att jag använde px-värden som width på `img`-element. Detta ändrade jag sedan. Jag märkte även att man inte fick ha mellanslag i href-property:n i `a`-taggar, vilket jag hade i mitt telefonnummer. Detta ändrade jag också.
* All CSS validerar som korrekt CSS.
  * https://jigsaw.w3.org/css-validator/.

    Min CSS validerade korrekt, men jag märkte att jag använde ett otillåtet värde på property:n `font-weight`, vilket jag fixade.
    
## Media
* Sidans media är optimerat.
* Bildstorlek och upplösning.
  * Ska bilden var 32 px x 32 px ska den vara det, inte 1920 x 1080.
* Bildens format är anpassat efter bildtyp.
  * Inga bmp eller tga filer, är det rimligt att köra png 32 på porträtt?
  * SVG och vektorformat där det passar.
  * PNG där storleken tillåter
  * JPEG på foto.
* Sidans totala storlek är rimlig.
  * Devtools, throttle network, testa.
