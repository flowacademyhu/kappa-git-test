# Teszt

Név: Varga Imre 

## Kérdések:

1. Mit értünk egy `commit` alatt, mit tartalmaz?

A jelenlegi változatásokról készül egy snapshot, el lokálisan mentett változat, ami a módisításainkat
tartalmazza.

1. Mi a különbség a `fetch` es `pull` git parancsok között?

Fetchel gitről húzzuk le a commitokat
pullal viszont az egész repót

1. Mi a három állapota file-oknak git szempontjából, milyen parancsokkal mozgatjuk ezek között?

Untracked, tracked, staged

git add, git commit

1. Mi a különbség a `git checkout origin/feature` és a `git checkout feature` parancsok között?

git checkout feature-el átlépük a feature branchre


1. Mi történik, ha valaki más is módosította a file-t amin dolgozunk és mit tudunk tenni ilyenkor?

Conflict fog létrejönni, ha mi is módosítottunk rajta, ezt fel kell oldani a kódrészletek elfogadásával.

1. Mi az a `HEAD` és mi a jelentősége?

Az utolsó commitot jelzi

1. Mi a célja a branch-elésnek?

Több ágra szedni a projectet, mindenki más ágon tudja végezni a projektben rá kiszabott munkát.
Ezeket a brancheket a végén össze lehet fűzni.

1. Hogyan lehet összehasonlítani file-ok állapotait, mire tudjuk még ezt a kimenetet használni?

git diff
Megnézni hogy milyen különbségek, változások vannak a 2 fájl között.

1. Hogy lehet megnézni egy repo történetét, milyen eszközeink vannak ebben való keresésre?

git log

1. Melyik git parancsot használnád, hogy megtudd milyen állapotban van épp a repo?

git status


Date:   Fri Nov 8 14:10:54 2019 +0100

    Add basic node webapp and instructions to run it

