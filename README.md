# Git Verziokezelés

## Helyi repository létrehozása

-   helyi repo inicializálása
    > git init
-   ellenörzés
    > git status
-   előkészítjük a commitra
    > git add .
-   ellenörzés
    > git status
-   comitolás
    > git commit -m "first commit"
-   A commitok listázása
    > git log

## Helyi repo összekapcsolása a távoli repoval.

-   Távoli repo létrehozása
-   Helyi és távoli kapcsolása
    > git remote add origin ...\\token@github.com...
-   legelső alkalommal a push: > git push -u master
    -t ovábbiakban:
    > git push
