# gittanfolyam
2019.04.01 - 2019.04.02

A revert parancs segítségével egy commit-tált snapshot összes módosítása visszavonható.
A parancs esetében a Git nem törli a korábbi commit-ot, hanem az aktuális branch-ben létrehoz egy újat, amely visszavonja a megadott commit változtatásait.
Erre az integritás megőrzése miatt van szükség.
visual studio 

git log --porcelain

git conflict
<<<<<<< HEAD
git conflict2
=======
git conflict3
>>>>>>> e5bdde454671e0f85055726cbb9a6f0e0c87198f
