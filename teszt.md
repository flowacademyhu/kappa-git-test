# Teszt

Név:

## Kérdések:

1. Mit értünk egy `commit` alatt, mit tartalmaz?
   A lokális repóban végzett módosításokról készült snapshotok összessége. Ezeket mi hozzuk létre, így eltudjuk menteni ezeket a snapshotokat.

1. Mi a különbség a `fetch` es `pull` git parancsok között?

A 'fetch' paranccsal a távoli repoba feltöltött commitokat tudjuk a saját gépünkre importálni. Nem mergeli a változtatásainkkal, a working directoryt, és a staging areat nem bántja. Ezek nélkül tudjuk tulajdonképpen megnézni, hogy "hol tartunk a többiekhez képest.".

A pull ugyanígy importálja a távoli repóba feltöltött commitokat a saját gépünkre, de mergeli is ezeket a saját változtatásainkkal, az éppen aktuálisan branch-en, amin vagyunk.

1. Mi a három állapota file-oknak git szempontjából, milyen parancsokkal mozgatjuk ezek között?

untracked: Ezeket a fájlokat és módosításaikat a git nem veszi figyelembe.

tracked: Ezeket a fájlokat és módosításaikat a git trackeli.
Ezen belül három állapot létezik:
-modified: A fájl tartalma módosult a legutolsó commit óta.
-unmodified: A fájl tartalmában nem történt módosítás a legutolsó commit óta.
-staged: A módosult fájlunkról már készült snapshot, ezek a módosítások bekerülnek a következő commitunkba.

1. Mi a különbség a `git checkout origin/feature` és a `git checkout feature` parancsok között?

"Origin"-ként hivatkozunk a távoli repóra, és azoknak a brancheire. Itt a feature is egy távoli repón lévő branch. A checkout parancs arra szolgál, hogy áttudjunk ugorni egy másik branch-re.

1. Mi történik, ha valaki más is módosította a file-t amin dolgozunk és mit tudunk tenni ilyenkor?

Mergeléskor meg kell oldanunk olyan conflictokat, amiket a gitnek nem sikerült, ezeket a fájl szerkesztésével tudjuk megtenni. A git segít ebben, külön kijelöli a másik fejlesztő módosításait és a sajátjainkat.

1. Mi az a `HEAD` és mi a jelentősége?

Az aktuális branch legutolsó commitja. Ez óta a commit óta nem történt módosítás.

1. Mi a célja a branch-elésnek?

A fejlesztők a különböző brancheiken tudnak dolgozni, így nem zavarják egymást a saját módosításaikkal. A brancheket össze lehet mergelni, így a végén mindannyiuk munkája bekerül a repóba.

1. Hogyan lehet összehasonlítani file-ok állapotait, mire tudjuk még ezt a kimenetet használni?

git diff és git status paranccsal tudjuk összehasonlítani őket.

1. Hogy lehet megnézni egy repo történetét, milyen eszközeink vannak ebben való keresésre?

git log paranccsal tudjuk megnézni. Ennek a parancsnak vannak kapcsolói, amik segítenek keresni az előzményekben.

1. Melyik git parancsot használnád, hogy megtudd milyen állapotban van épp a repo?

git diff

4.  Date: Fri Nov 8 13:11:14 2019 +0100
    Mert : why would anyone put lorem ipsum here?
