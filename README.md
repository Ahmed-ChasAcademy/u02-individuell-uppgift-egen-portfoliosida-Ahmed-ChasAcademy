# Vad kan man utveckla m.h.a av Javascript inom frontend?

Javascript är språket som gör allt interaktivt med webbplatsen. Utan Javascript skulle webbplatsen ha nästan 0 funktioner eller interaktioner förutom att gå från en HTML-fil till en annan eller ha några animationer och färgförändringar. Jag tror att Javascript är den viktigaste delen av användargränssnittet som faktiskt ger webbplatsen ett syfte om det kräver interaktioner mellan användaren och webbplatsen. Om webbplatsen är byggd för att vara ett sätt att bara visa information för användaren kommer Javascript inte att vara nödvändigt eftersom HTML och CSS endast skulle representera information på ett tilltalande visuellt sätt för användaren. Om webbplatsen kräver att du skickar information eller tar emot information från andra ställen på webben ska Javascript användas.

---

# Vad är JSON och hur används det inom frontend?

JSON är ett filformat som sparar information i nyckel:värdepar. JSON står för "JavaScript Object Notation". Det är ett sätt att spara information på ett sätt som många andra programmeringsspråk kan förstå och därför är det ett viktigt sätt att spara information som objekt. För att skriva JSON-filer måste man skriva information i ett nyckel:värdepar som till exempel `"Stad": "Stockholm"`. 

Staden anses vara nyckeln och Stockholm är värdet av den nyckeln. Allt i JSON-filen ska vara i dubbla citattecken. För att komma åt det som objekt i Javascript måste man `.parse()` det och för att skicka det från en Javascript-fil till en JSON-fil måste man `.stringify()` det för att lägga till dubbla citattecken till både nyckel- och värdeparet.

Vi kan helt enkelt säga att JSON-filen används för att lagra och hämta data på ett korrekt strukturerat sätt.

---

# Vad är HTTP och varför bör man som frontendutvecklare ha kunskap om det och dess protokoll?

HTTP (HyperText Transfer Protocol) är systemet som låter din dator prata med webbplatser. När du öppnar en webbplats skickar din dator en HTTP-förfrågan för att fråga om saker som text, bilder eller videor, och webbplatsen skickar tillbaka dem som ett HTTP-svar. 

Som frontend-utvecklare är det viktigt att känna till HTTP eftersom det hjälper dig att förstå hur webbplatser fungerar, hur data flyttas mellan din dator och webbplatsen och hur du åtgärdar problem när något går fel. Det hjälper dig också att få webbplatser att laddas snabbare och få information från andra webbplatser att visa på egen hand.
