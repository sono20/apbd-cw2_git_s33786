# apbd-cw2_git_s33786
Zadanie 5:
W tym przypadku Git musiał utworzyć tzw. Merge Commit, ponieważ historie gałęzi main oraz feat rozeszły się. Nastąpiły zmiany na gałęzi docelowej.

#1. Kiedy Git wykona fast-forward, a kiedy powstaje merge commit?
Fast-forward: Gdy gałąź docelowa nie ma nowych zmian — Git tylko przesuwa wskaźnik do przodu.

Merge commit: Gdy obie gałęzie mają nowe, rozbieżne commity — Git tworzy nowy commit łączący obie historie.

#2. Czym w praktyce różni się merge od rebase?
Merge: Zachowuje pełną historię i strukturę drzewa (tworzy dodatkowy commit łączący).

Rebase: Przenosi commity na szczyt innej gałęzi, tworząc jedną, prostą linię czasu (przepisuje historię).

#3. W jaki sposób został rozwiązany konflikt w Twoim repozytorium?
Konflikt w StatisticsHelper.cs rozwiązano ręcznie. Usunięto znaczniki (<<<<, ====, >>>>) i świadomie wybrano typ double dla pola numer, łącząc zmiany w działający kod i zatwierdzając go nowym commitem.
