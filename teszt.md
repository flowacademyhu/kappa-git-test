# Teszt

Név:Judák Barnabás 

## Kérdések:

1. Mit értünk egy `commit` alatt, mit tartalmaz?
Ezzel a jelöljük hogy mit változtattunk az adott dolgon a repoban, ezt megtudjuk tenni lokálisan is illetve fel is tudjuk psuholni a commitunkat ahol más is fogja látni milyen változtatást eszközöltünk az adott fájlon, vagy kódon.
1. Mi a különbség a `fetch` es `pull` git parancsok között?
A fetch csak letölti a legujabb verziót de ezt nem integrálja még bele a mi verziónkba a változtatásokat, ezzel szemben a git pull bele is integrálja ezeket a változtatásokat a mi verziónkba.
1. Mi a három állapota file-oknak git szempontjából, milyen parancsokkal mozgatjuk ezek között?
Untracked: a fálj létrevan hozva viszont a nem része még a git verzió kezelésnek, Staged: a fájl hozzá lett addolva egy git repohoz viszont nincsen még commitolva, Commited: amikor már commitoltuk a változtatásainkat és fel is pusholtuk azt a megfelelő repora.
1. Mi a különbség a `git checkout origin/feature` és a `git checkout feature` parancsok között?
az elsőnél átváltana az originen lévő feature branchre, a másodiknál pedig létrehozna egyet és át is váltana.
1. Mi történik, ha valaki más is módosította a file-t amin dolgozunk és mit tudunk tenni ilyenkor?
Ilyenkor összelehet mergelni a változtatásokat, megmutatja a git hogy a másik ember mit változtatott a fileon és megkérdezi az összes változtatott fájlnál hogy melyik verziót fogadjuk el, és a mergelés előtt commitolni kell.
1. Mi az a `HEAD` és mi a jelentősége?
A HEAD mint egy pointerkét szolgál megmutatja a megfelelő checkoutolt branchen hogy mi volt az utolsó commit, amikor például váltunk checkouttal másik branchre akkor a HEAD is áttranszferálódik a megfelelő branchre.
1. Mi a célja a branch-elésnek?
Például ha sokan dolgoznak egy repoban akkor különböző branchet hoz létre mindenki és mindenki külön tud így haladni a munkájával és nem ütköznek annyira a munkával. 
1. Hogyan lehet összehasonlítani file-ok állapotait, mire tudjuk még ezt a kimenetet használni?
git-diff a commitok közötti a különbségeket,állapotokat mutatja meg.
1. Hogy lehet megnézni egy repo történetét, milyen eszközeink vannak ebben való keresésre?
git log és itt lehet a bashos kereséseket használni mint például grepelni, pipolni, stb.
1. Melyik git parancsot használnád, hogy megtudd milyen állapotban van épp a repo?
git status




4.feladat: git log node-express-app.js
