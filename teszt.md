# Teszt

Név: Lázár Tamás 

## Kérdések:

1. Mit értünk egy `commit` alatt, mit tartalmaz?
a feltöltésre készen álló változásokat

1. Mi a különbség a `fetch` es `pull` git parancsok között?
a fetch csak frissiti a githubon lévő változásokat a lokális repoba a pull le is tölti

1. Mi a három állapota file-oknak git szempontjából, milyen parancsokkal mozgatjuk ezek között?
git add, git commit, git push

1. Mi a különbség a `git checkout origin/feature` és a `git checkout feature` parancsok között?
az origin/feature a githubon lévő repóra utal origin nélkül a lokális repóba lépünk át

1. Mi történik, ha valaki más is módosította a file-t amin dolgozunk és mit tudunk tenni ilyenkor?
feloldjuk a conflictokat

1. Mi az a `HEAD` és mi a jelentősége?
A HEAD az aktuális branch utolsó commitját jelöli, ami óta az adott branchen még nem keletkezett újabb commit.

1. Mi a célja a branch-elésnek?
hogy main-be csak olyan változás kerüljön ami bugmentes
  
1. Hogyan lehet összehasonlítani file-ok állapotait, mire tudjuk még ezt a kimenetet használni?
git diff

1. Hogy lehet megnézni egy repo történetét, milyen eszközeink vannak ebben való keresésre?
git log 
greppeléssel lehet benne keresni

1. Melyik git parancsot használnád, hogy megtudd milyen állapotban van épp a repo?
git status

commit 99c1ad7014cf2e72ce5479b9f62863cf1773c5d7 (origin/upstream)
Author: András Maróy <andras@maroy.hu>
Date:   Fri Nov 8 13:17:27 2019 +0100

    Improve the logic of the health endpoint
    
    Healthchecks should be an aggregate of all values affecting the health
    of the service.

commit 0dd6e49daff0bb9ee87ad85f8aa411351843831a
Author: András Maróy <andras@maroy.hu>
Date:   Fri Nov 8 13:14:35 2019 +0100

    Add /hello endpoint and bump version to 1.1.0

commit b0825c838041ef1f0d3b1c4b1b8d4fc4d435e6ac
Author: Mark Zuckerberg <zuck@facebook.com>
Date:   Fri Nov 8 13:08:59 2019 +0100

    Change the status endpoint to /health
    
    To follow industry standards, the endpoint responsible for the status of
    the service should live under the /health endpoint and return a bool
    value denoted by the `health` key.

commit db6d33bc2fb48a8a313effec9d73f5bccd29abc6
Author: Mark Zuckerberg <zuck@facebook.com>
Date:   Fri Nov 8 13:08:59 2019 +0100

    Change the status endpoint to /health
    
    To follow industry standards, the endpoint responsible for the status of
    the service should live under the /health endpoint and return a bool
    value denoted by the `health` key.

commit 1d1cf3480c68b564613809bec72ed33d9a98e2d0
Author: András Maróy <andras@maroy.hu>
Date:   Fri Nov 8 14:10:54 2019 +0100

    Add basic node webapp and instructions to run it
