# Teszt

Név: 

## Kérdések:

1. Mit értünk egy `commit` alatt, mit tartalmaz?

Commit azért jött létre, hogy a egy logika alá soroható kódokat egy csokorba tudjuk gyüjteni, több felhasználó egyszerre dolgozhat, git add és git remove fájlokat szintén tartalmani fogja a a git
commit, valamint a commit mindig tartalmaz egy üzenetet amiben röviden összefoglalhatjuk a változást. A working dir. ből git add paranccsal jutunk stage állapotba ahol pedig a a git committal tudjuk
belerakni a lokális repoba. Git push-al pedig a távoli repoba. A commitok a változtatásokat mutatják branchek fájlok vagy más commitok között.


1. Mi a különbség a `fetch` es `pull` git parancsok között?

git pullnál git fetch és git merge parancs is lefut míg a fetchelésnél csak a commitokat szedem le a lokál repoba és tudom összemérni, hogy mennyit haladt előre például a main branch.

1. Mi a három állapota file-oknak git szempontjából, milyen parancsokkal mozgatjuk ezek között?

untracked : Mikor a git nem vizsgálja a fájlokat.

Tracked:

modified: Amikor módosítottuk a fájlunkat , de nem biztos hogy addolásra fog kerülni, vagy hogy utánna commioljuk
unmodified: A fájl nem változott, a git statusnál clean-nek fogja mutatni.
staged/cached : Ez az az állapot amikor a fájl gi add-al bekerül a stage állapotba, és innen tudujuk git committal rárakni a lokális repora.

1. Mi a különbség a `git checkout origin/feature` és a `git checkout feature` parancsok között?

Chekcout paranccsal tudunk a branchek között lépkedni. git checkout feature - a feature branchre lépünk át. Az origin a távoli repo neve, ha nem változtattuk meg.

1. Mi történik, ha valaki más is módosította a file-t amin dolgozunk és mit tudunk tenni ilyenkor?

Ha külön branchen vagyunk akkor vagy push vagy pull paranccsal tudjuk összehozni a 2 fájlt arra a branchre ahol szükségünk van rá. Amennyiben ugyanabban a fájlban hajtottunk végre változtatásokat 
akkor pedig a konfliktusokat kell kezelnünk.


1. Mi az a `HEAD` és mi a jelentősége?

Az aktuális Branch utolsó commitja. A legfrissebb változtatásról kapunk információt a commit üzenetben.

1. Mi a célja a branch-elésnek?

branchelésnél elágazásokat tudunk létrehozni, amelyek megkapják az eddigi fájlok állapotát, valamint utánna tudunk rajtuk változtásokat végrehajtani, amely nem fogja befolyásolni azt a branchet, 
amelyről a leváltunk. Ezek a branchek visszavezethetőek egy "ős" branchre. A változtatásaink csak akkor kerülnek bele az ősbrachbe amikor az ősbranchre pusholunk vagy az ősbranchről pullolunk.

1. Hogyan lehet összehasonlítani file-ok állapotait, mire tudjuk még ezt a kimenetet használni?

git status paranccsal érjük el a working dir. állapotát, ilyenkor az ottani fájlok állapotát tudjuk felmérni. Git diff-el pedig a branchek, commitok, fájlok közötti állapotot tudjuk felmérni.

1. Hogy lehet megnézni egy repo történetét, milyen eszközeink vannak ebben való keresésre?

git log paranccsal látjuk a repoban történt változásokat. Git diffet tudunk még használni hogy kiszűrjük mikor történt benne a változás.

1. Melyik git parancsot használnád, hogy megtudd milyen állapotban van épp a repo?

git status parancsot. Ezzel meg tudjuk vizsgálni épp melyik branchen vagyunk , és a fájljainkban történt e változás, valamint hogy azok a working dir. staged, lokál repoban vannak-e.


