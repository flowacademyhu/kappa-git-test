# Teszt

Név: CSupor Nándor 

## Kérdések:

1. Mit értünk egy `commit` alatt, mit tartalmaz?
Változtatás, tetszőleges méretű lehet de kb 1 logikai változtatás legyen 1 commit
1. Mi a különbség a `fetch` es `pull` git parancsok között?
a fetch csak lekéri a távoli repoból a változtatásokat, a pull le is szedi őket
1. Mi a három állapota file-oknak git szempontjából, milyen parancsokkal mozgatjuk ezek között?
untracked, modified, staged, - add, commit, remove 
1. Mi a különbség a `git checkout origin/feature` és a `git checkout feature` parancsok között?
Az elsőnél az origin feature nevű branchére megyek át, a másokdiknál a sima feature branch-re.
1. Mi történik, ha valaki más is módosította a file-t amin dolgozunk és mit tudunk tenni ilyenkor?
COnflict lesz, fel kell oldani
1. Mi az a `HEAD` és mi a jelentősége?
legutolsó commitre való hivatkozás.
1. Mi a célja a branch-elésnek?
Hogy több irányba haladhasson a projekt, de maradjon egy eredeti működő változat, később eldöntjük mi kerül a main-be.
1. Hogyan lehet összehasonlítani file-ok állapotait, mire tudjuk még ezt a kimenetet használni?
git diff- Változtatásokat megmutatja a working directory és az index, a brachek, fájlok, commitok között.
1. Hogy lehet megnézni egy repo történetét, milyen eszközeink vannak ebben való keresésre?
git log- grep el lehet keresni
1. Melyik git parancsot használnád, hogy megtudd milyen állapotban van épp a repo?
git status



