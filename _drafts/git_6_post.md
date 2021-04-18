## 6. gyakorlat: Git alap folyamatok további gyakorlása (opcionális)

Ez a gyakorlat opcionális, vagyis csak a legutóbb megtanultakat fogjuk gyakorolni, de azárt ajánlom az elvégzését. Semmi extra, ez igaz, ám a gyakorlás a programozásban is legalább olyan fontos, mint bármely más technika elsajátításában. Megtanulható könyvekből, de csak akkor fogod tudni, ha képes vagy működtetni, ahhoz pedig gyakorolni kell, nincs mese.

További fájlokat fogunk elvinni a commit fázisig. Nem csak újakat adunk hozzá, hanem régieket módosítunk és törlünk is. Persze, megtehetjük ezt ugyanazonon egy fájlon (az elsőn), de azért legyen egy pici változatosság, készítsünk pár új szöveges fájlt.

Első lépésként adjunk hozzá mondjuk egy újabb text fájlt a projekthez. Mindegy, mi a neve, mit tartalmaz. Ezt vagy a korábban hozzáadott fájlt módosítsuk. Minimális javítás a szövegben, vagy egy pici betoldás, kihúzás &ndash; az sem baj, ha nincs értelme. Én hozzáadtam a repóhoz egy újabb fájlt majd az elsőt minimális mértékben módosítottam. Így néz ki a módosítás a GH Desktopban:

![Fájl módosítás a Github Desktopban](..\assets\img\modified_file.png)
Ez a nézet a gitre jellemző: egyszerre mutatja az új és a régi szöveget egymás alatt. Ahogy láttuk az előző <!-- link az előzőre --> cikkben, a zöld sorok az újakat jelzik. Itt látjuk a pirosat, ami a régi, törölt sorokat mutatja. A módosítás tehát így épül fel a Gitben: valamit töröltünk, de valamit hozzá is adtunk. Sötétzölddel kiemeli a soron belül a változást, hogy ne vesszünk teljesen el. Oldalt a *Changes* menüben sárga kocka, közepén egy pötty mutatja, melyek a módosított fájlok.

Ezt a változtatást én elvittem a commit fázisba, majd hozzáadtam egy újabb fájlt.

![Fájl törlés](..\assets\img\deleted_file.png)
Mint a képen is látszik, nem kell, hogy szöveges fájl legyen, de minden másból kissé nehéz szöveges nézetet mutatni, ezért meg sem próbáltam megnyitni a GH Desktopban. Ha már hozzáadtam egy újat, töröltem is az előzőleg hozzáadott, később nem módosított fájlomat. A piros mínusz jellel ellátott négyzet a törölt fájlok jelölője. Mellette szegény első fájlt megint módosítottam, hogy a szöveg tükrözze a repo állapotát. (A szöveg alpján a **first.txt** először az *első* szöveges fájl volt, de miután a másodikat töröltem és csak egy kép maradt mellette, megváltoztattam, hogy az *egyetlen* szöveges fájl legyen. Nem kötelező, hogy a leírás tükrözze a valóságot, de miért is ne?)

Újabb commit a bal alsó sarokban. Ha szeretnénk, írhatunk egy rövid leírást is, csak a gyakorlás kedvéért.

Ebben a gyakorlatban ennél többet nem kérek. Ha lelkesít, nyugodtan próbálkozzatok tovább is, a gyakorlás sosem árt. :smile: Egy egész regényt le lehet gépelni ilyen apró módosítgatásokkal. Sőt, lehet írni git regényt is, ami a változáskövetésből rajzolódik ki (a *history*-ban íródik), bár legjobb tudomásom szerint még ilyen nincs.

Hogy előkészüljünk a jövő verziókövetés regényeire, a következő cikk <!-- link a 7-re --> a *history* rejtelmeit kutatja. Böngészgetünk a commitok között, visszatérünk korábban mentett állapotokra, elvetünk módosításokat.