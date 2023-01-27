# Datorarkitektur (del IV) - Stacken
Fjärde delen i en serie som behandlar CPU-konstruktion i mjukvara. 
En simulerad processor som baseras på mikrodator ATmega328P implementeras i terminalmiljö,
där klockpulser, in- och utdata implementeras via inmatning samt utskrift från terminalen.

Denna del behandlar stacken, primärt stackens och stackpekarens syfte och arbetssätt, 
PUSH- och POP-operationer, inkrementering respektive dekrementing av stackpekaren med mera.
Instruktioner CALL, RET, PUSH och POP implementeras för anrop respektive återhopp till och 
från subrutiner, allokering av lokala variabler med mera.
  
I efterföljande delar ska ytterligare OP-koder, ALU:n samt interrupt-implementering läggas till.

Filen "stack.png" utgör en bild som demonstrerar stackens arbetssätt visuellt samt via text.

Filen "embedded_computer_system_part4_start_code.zip" innehåller startkoden (utan stackimplementering).

Resterande filer utgörs av processorn med färdig stackimplementering samt att programkoden har 
uppdaterats för att testa stackimplementeringen via multipla subrutinsanrop samt återhopp.

Se video tutorial här:
https://youtu.be/cUgF4K6fdtY
