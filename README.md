# HCD

het doel van dit vak is om voor een speciale case een oplossing te vinden, mijn case is Darice. Darice is op latere leeftijd doof geworden en ze wilt graag films beter kunnen volgen, in het speciaal gaat dat over geluidseffecten en muziek, want dat is op het moment niet heel goed beschreven in closed captions.


## week 1

deze week was ik op de eerste dag ziek, hierdoor heb ik de feedback gemist. Dit betekent dat ik automatisch moet herkansen om op die manier alsnog vier rondes feedback te krijgen.

Ik ben deze week begonnen met het opzetten van het bestand van Vasilis waar hij een subtitel script heeft geschreven voor video's van youtube. Ik heb wat ideeën bedacht voor volgende week om uit te werken


## week 2

Ik heb de eerste dag deze week een codepen uitgewerkt met wat effecten die ik wilde testen op Darice met een effect voor suspense in de muziek en een effect voor geweersschoten. Dit zijn twee simpele animaties die op de body verschijnen wanneer je op een button drukt, maar het idee is natuurlijk dat die uiteindelijk op een bepaald moment van de film worden aangezet om die geluiden te laten zien voor Darice.

### testresultaten

- Uit de test kwam dat Darice de geweersschoten niet erg interessant vond, omdat die meestal in de film worden laten zien. Het is dus blijkbaar belangrijk om te kijken of geluid alleen op de achtergrond is, want dan is het niet nodig om het te laten zien met extra effecten. Ook vond Darice het schoteffect irritant, wat goed is om te onthouden om een irritant geluid te visualiseren.
- Het zwel effect vond Darice interessant, ze zei dat het een gevoel gaf alsof de muziek luider word. Dit kan ik dus gebruiken om spanning of volume in muziek aan te geven, die twee gaan overigens vaak gepaard.

Na de test ben ik verder gegaan met het voorbereiden op de volgende test, ik wilde op twee dingen focussen:
1. ritme van muziek aangeven - dit wilde ik doen door een animatie op het ritme van de muziek te 
2. kijken hoe ik de tekst allemaal kan laten zien en wat Darice fijn vindt
3. kijken welke tekst en schermgrootte het beste zijn voor darice


## week 3

Deze week heb ik een aantal codepennetjes gemaakt waar ik mee ben gaan testen:

[music test 1](https://codepen.io/lorenzo_03/pen/MYYbzwv)

[music test 2](https://codepen.io/lorenzo_03/pen/PwwbxPq)

[music test 3](https://codepen.io/lorenzo_03/pen/MYYmoLo)

[music test 4](https://codepen.io/lorenzo_03/pen/mydZmKJ)


[text test 1](https://codepen.io/lorenzo_03/pen/Byagwwj)

[text test 2](https://codepen.io/lorenzo_03/pen/bNGPooe)

[text test 3](https://codepen.io/lorenzo_03/pen/QwWXqqd)

[text test 4](https://codepen.io/lorenzo_03/pen/pvoXWWw)


[size test](https://codepen.io/lorenzo_03/pen/MYYmoZo)


### testresultaten

1. Darice vind deze tekst- en schermgrootte het fijnste: screen height: 85vh; font-size: 18px;
2. Beweging op de achtergrond leidt af, dus het is beter om met kleur en opacity de muziek na te bootsen.
3. Kleur bij text voegt niks toe en het is bijna altijd duidelijk wie wat zegt dus namen zijn niet altijd nodig.
4. Ook kwam uit een test van iemand anders dat het beter is om tekst niet helemaal te centreren en ook niet helemaal links uit te lijnen.


### voorbereiding voor volgende test

Voor de volgende tekst wil ik toch kijken naar een interface waarbij je kleur kan koppelen aan karakters van de film, dat kan je natuurlijk niet voor elk persoon doen vanwege spoilers, maar bij de hoofdpersonen denk ik dat het een goed idee is.

Ik heb wat dingen geprobeerd te coderen, maar dat koste te veel tijd, dus ik heb gekozen om een voorbeeld te maken in Figma en die te testen:

<img width="386" alt="image" src="https://github.com/user-attachments/assets/98774bce-b59b-413a-9eb7-3615f36614a9" />


## week 4

Ik heb wat verder gewerkt aan de code voor mijn Figma prototype voor de test, dit was heel kort want er was maar een uur tijd.

### testresultaten

Er kwam uit dat het te veel moeite is om voor een film allemaal instellingen aan te passen, het is belangrijk dat je hem meteen aan kunt zetten en zo snel mogelijk kan kijken. Dat vond ik jammer, want dit leek me een goede uitdaging

Ik ben nu van plan om een aantal specifieke scenario's uit te werken die veel voorkomen in films alleen met geluid:

1. voetstappen buiten beeld
2. wind die waait
3. hartslag
4. een piep nadat er geschoten wordt

Ik wil deze voorbeelden uitwerken met visuele effecten en het liefste zo min mogelijk tekst. Ik ga voor elk van deze geluiden een test maken en die langs familileden halen (mijn oma is slecht horend dus die lijkt me het meest geschikt hiervoor)


## week 5

hier zijn de voorbeelden van de uitgewerkte animaties:

**voetstappen**

![footsteps](https://github.com/user-attachments/assets/f53c5641-4639-4f4e-b703-6dd08b162cdd)


**wind**

[wind-animation-test](https://codepen.io/lorenzo_03/pen/vEEWyaE?editors=0010)


**hartslag**

[heartbeat-animation-test](https://codepen.io/lorenzo_03/pen/ByyxaGz?editors=1100)


**piep na schoten**

[gunshot-animation-test](https://codepen.io/lorenzo_03/pen/MYYGWRV?editors=0100)


### extra test

Om zeker te zijn dat mijn ideeën werken heb ik aan mijn slechthorende oma de vier bovenstaande tests laten zien zonder geluid en aan haar gevraagd of ze het effect vond werken en wat het onduidelijk maakt als het niet werkt. Dit zijn de resultaten:

**voetstappen**

Het zijn duidelijk voetstappen, voegt een leuke animatie toe aan de film en maakt het duidelijk van welke kant het geluid komt.

**wind**

De wind waait maar 1 keer, ook lijkt het meer op vallende sterren. Het is wel handig om te weten hoelang het geluid doorgaat.

**hartslag**

Het is duidelijk dat het hart klopt, het klopt alleen erg snel.

**piep na schoten**

Het effect op de iframe is niet echt duidelijk, het wit op de achtergrond wel. Het effect is irritant.


### aanpassingen na de feedback

Ik heb de voetstappen zo gelaten, die zijn vrij duidelijk hoe ze nu zijn. De wind heb ik oneindig laten doorgaan, zodat ik het kan laten doorgaan zolang als het waai geluid is. De hartslag vond mijn oma te snel, maar ik denk dat zolang ik het tempo van het geluid aanhoud dat dat niet een probleem is. De achtergrond van de piep was duidelijk, maar het is misschien slim als ik de brightness wat hoger maak, zodat het effect op de iframe wat sterker word. Ook vond mijn oma het effect irritant, wat een goede uitkomst is want de piep is ook irritant dus ik boots het geluid goed na.


## oplevering

Uiteindelijk heb ik een aantal dingen gedaan om deze film een betere beleving te maken voor Darice:

1. Ik heb de film voorzien van ondertitelingen (tot de eerste minuut wegens tijd tekort)
2. Ik heb het tempo van muziek aangegeven aan de hand van een animatie met kleur op de achtergrond
3. Ik heb extra geluiden zoals voetstappen, wind en hartslag toegevoegd op een visuele manier om het gevoel wat meer over te brengen dan wanneer je alleen tekst gebruikt.

Ik heb dit allemaal aan Darice aangepast door verschillende tests te doen over wat voor haar wel en niet belangrijk is en ik ben uiteindelijk hierop uigekomen.

### als ik meer tijd had...

Ik heb bij dit project een hoop tijd verloren aan ziek zijn en het duidelijk krijgen van wat belangrijk is voor de opdracht in plaats van voor Darice, achteraf had ik meer tijd willen steken in mijn testen en meer concepten willen bedenken voor het visualiseren van kleine geluidjes op de achtergrond die je niet ziet maar wel hoort. Ik vond dat ook het leukste van de opdracht dus daar was ik graag mee doorgegaan. 

Ook had ik wat meer tijd willen steken in het netjes maken van mijn code, ik weet dat dit niet per se een vak is waar code erg belangrijk is, maar ik vind het voor mezelf wel belangrijk om een overzichtelijke code te schrijven waar ik later nog dingen uit kan terugvinden als dat nodig is.
