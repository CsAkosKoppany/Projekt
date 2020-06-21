# Projekt
Többváltozós analízis mérnöki alkalmazásai projekt feladat

Készítette:\
Csuta Ákos Koppány (A754ZN), Dobák Dávid (XX34G7)

Az oldalon megtalálható kódok mutatják be az általunk választott projekt megvalósítását. Egy "Genetic algorithm", GA segítségével oldottuk meg az alábbi problémát:\
Adott egy tetszőleges méretű "nagy", és több tetszőleges méretű "kis" téglalap. A feladat a "nagy" téglalap átfedés- és kilógásmentes lefedése, méghozzá minél nagyobb arányban.

- Az első kód a legegyszerűbb példa, amikor a lefedendő téglalap azonos méretű az egyik "kis" téglalappal. Ezen a példán magyarázó kommentek sorával ismertetjük a megoldás módját. Mivel ez minden további példa esetében is azonos, a későbbi eseteknél nem részletezzük a megoldás menetét.
- A második kód egy valamivel bonyolultabb eset, amikor a "nagy" téglalap pontosan akkora, mint a "kis" téglalapok közül kettő egymás mellé illesztve. Itt röviden bemutatjuk, hogy az algoritmus paraméterei miként hatnak az eredményre.
- A harmadik kód egy sokkal általánosabb eset, amikor sok "kis" téglalap kombinációja lesz a megoldás, illetve nem beszélhetünk a "nagy" 100%-os lefedéséről. A megoldás megtalálása után bemutatjuk, miben nyilvánul meg a GA használatának előnye az egyszerű véletlenszerű próbálkozással szemben. 
- A projekt zárásaként röviden bemutatunk egy lehetséges továbbfejlesztési módot is, nevezetesen azt, amikor a "kis" téglalapok 90 fokkal elforgathatóak z-tengely körül.
