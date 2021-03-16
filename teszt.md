# Teszt

Név: Szabó Péter 

## Kérdések:

1. Mit értünk egy `commit` alatt, mit tartalmaz?

	Azonos téma köré csoportosuló módosítások összessége. 

1. Mi a különbség a `fetch` es `pull` git parancsok között?

	a fetch  csak a lokális adatbázist frissíti, a working directoryt és a staging areat nem, míg a pull azokat is. 


1. Mi a három állapota file-oknak git szempontjából, milyen parancsokkal mozgatjuk ezek között?
	
	untracked->  add - > modified -> commit -> staged push 

1. Mi a különbség a `git checkout origin/feature` és a `git checkout feature` parancsok között?

	az origin/feature a remote repon lévő feature branchre fog checkoutolni míg a másik a lokális feature branchre

1. Mi történik, ha valaki más is módosította a file-t amin dolgozunk és mit tudunk tenni ilyenkor?
	
	conflict fog kialakulni, fel kell oldani a conflictot.

1. Mi az a `HEAD` és mi a jelentősége?
	
	adott branch-en a legutolsó commitra így lehet hivatkozni

1. Mi a célja a branch-elésnek?

	egy ős commitról le lehet ágazni egy új űgra, ahol az előző módosítások még megvannak, viszont eközben
	 az új commitok már az eredeti branchen nem módosítanak, csak ha mergeljük.

1. Hogyan lehet összehasonlítani file-ok állapotait, mire tudjuk még ezt a kimenetet használni?
	
	 git diff-fel tudjuk megvizsgálni, brancheket vagy repokat is össze lehet vele hasonlítani 

1. Hogy lehet megnézni egy repo történetét, milyen eszközeink vannak ebben való keresésre?

	git log, greppelni lehet benne.

1. Melyik git parancsot használnád, hogy megtudd milyen állapotban van épp a repo?
	 git status
