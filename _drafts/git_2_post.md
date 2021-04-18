## 2. Git, GitHub és GitHub Desktop

![Git logó](..\assets\img\git_logo.png)

Mint azt írtam, az általunk használt verziókezelő rendszer a Git lesz. Továbbá a GitHub Desktop programot fogjuk vele használni. De hogy jönnek ezek össze? És pontosan mi az a Git?

### Git történelme és felépítése

A Git történelmébe nem megyek bele nagyon. Az isteni és zseniális Linus Torvalds fejlesztette a Linux rendszermag verziókezeléséhez, majd ebből lett a világ egyik legnépszerűbb verziókezelő szoftvere. Valószínűleg a Linux miatt...

Rendkívül egyszerű szoftver, a használata nem igényel szoftverfejlesztői diplomát, még akkor sem, ha elsőre kissé félelmetes, hogy parancssori kezelőfelülete van. Na, ez utóbbit fogjuk mi kiütni, de erről később. Emellett sokrétűen alkalmazható, mindent tud, amire egy verziókezelői helyzetben szükség lehet és még sok olyat is, amiről sosem gondolta volna az ember, hogy kell neki.

Korábban is volt róla szó, hogy elosztott rendszer, tehát nincs egy nagy igazság, bármi regisztrálhat és hozzászólhat a projektekhez. Persze ez nem azt jelenti, hogy nem léteznek eredeti repók, de ezeknél nem a fejlesztők mondják meg, hogy ki csatlakozhat. Bárki küldhet be javításokat, javaslatokat. A készítők legfeljebb arról dönthetnek, hogy ezt elfogadják vagy visszautasítják. Ha elfogadták, a kód végérvényesen beépült a projektbe.

Nagy előnye még a Gitnek, hogy nyílt, ingyenes. Igen, a Git forráskódja is verziókövetett, bárki hozzászólhat. :smile: Az ingyenességet nem kell magyarázni, ingyen és bérmentve letölthető. Sőt, a Linux rendszerekbe eleve beépített, de Windowsra sem lehetetlen telepíteni.

Az elosztottságból fakad, hogy az egyes változásokat merge, azaz összefésülés segítségével építi be az újabb kódokba. Azaz nem zárolja az egyes fájlokat, hogy most ezen nem dolgozhat senki, bármikor módosíthatunk bármin. Legfeljebb nem kerül beépítésre, mert egy másik felhasználó módosításaival pont ütközik, és azt hamarabb elfogadják a repó fenntartói.

A Git legnagyobb előnye ezek mellett, hogy gyors. A leggyorsabb, ha a mérések nem tévednek. Nem kell tehát sokat várni, hogy mentsen, összefésüljön, beépítsen, fellője a felhőbe, majd leszedje a legújabb módosításokat. Ez egy hatalmas repo esetén nagyon nagy előny.

Apropó felhő: a Git a letöltés után nem igényel netkapcsolatot. A 14. leckéig kizárólag offline fogunk dolgozni (rendben, az elején le kell tölteni a szoftvert, az nem számít), és utána is csak egy rövid ideig látogatjuk meg a webet. Így is teljesértékű, hiszen a saját gépünkön is lehetséges a fájlok verziókövetése.

Mégis a nagy előnye a megosztásban rejlik: a fájlokat, ezek változatit megoszthatjuk a széles nagyvilággal a neten, így bárki tud csatlakozni, hozzátoldani. Nem véletlenül kezdtem én is a Gittel az alapozó cikkeket: ezek is verziókövetett rendszerben vannak. Tehát Ti is hozzáadhatjátok a saját javaslataitokat, javításaitokat! Elírást találtál? Nosza, javítsd ki nyugodtan! :smile: Ritka, hogy ekkora beleszólása legyen az olvasónak a tartalomba.

A megosztást maga a Git nem köti meg. Küldözgethetnénk e-mailben, feltölthetnénk bármely saját oldalra, a többség mégis a nagyforgalmú, Git alapú oldalakat választja. Elvégre itt van a legtöbb felhasználó, csak nem lehetnek olyan rosszak...

Több ilyen is van. A két legnépszerűbb a [Github](https://github.com/), amit jelenleg a Microsoft birtokol (megvették, nem ők fejlesztették) és a [Bitbucket](https://bitbucket.org/) az Atlassiantól. Bár semmiféle különbséget nem szeretnék tenni a kettő között, mi most mégis az elsőt fogjuk használni. Mindketten kínálnak valami olyat, amit a másik nem: a Bitbucketnek vannak ingyenes privát repói, ami gyakorláshoz, titkos kódmegosztáshoz remek. A Githubon ezek a fizetős szolgáltatások körébe tartoznak, cserébe viszont a Github Pages alkalmazás segítségével bármely nyilvános repónkból automatikusan blogot készíthetünk. Illetve övék a [Github Desktop](https://desktop.github.com/), a szoftver, ami még egyszerűbbé teszi az amúgy parancssori Git alkalmazását. Zavarnak a kódok, meg parancssor, olyat nem is láttál, és az egész tiszta hackelés? Oké, akkor itt egy kedves program, mint bármely átlagos Windowsos alkalmazás, és mindent megcsinál helyetted a háttérben.

A következő rész egy rövid gyakorlat lesz: készítünk egy Github felhasználót (nem kötelező, de ha már fel szeretnénk lőni a gyakorló projektünket a netre, akkor ajánlott) és letöltjük ezt a Github Desktopot. Utána pedig elhagyjuk a netet egy darabig és csak jó sokára térünk vissza.