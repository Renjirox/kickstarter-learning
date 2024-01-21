# kickstarter-learning

Repozytorium z projektem do machine learning wykorzystującym dane z Kickstarter'a.

## Wyjaśnienie kolumn:

ID - ID Projektu
deadline - Deadline projektu w czasie UNIX<br/>
goal - Cel projektu w USD<br/>
launched - Czas wystartowania projektu w czasie UNIX<br/>
pledged - Ilość pieniędzy zebranych<br/>
state - Stan projektu | 1 = Zakończony powodzeniem | 0 - Zakończony niepowodzeniem<br/>
backers - Ilość osób które wsparły projekt<br/>

## Struktura projektu:

data/ks-projects-201612.csv - plik CSV z danymi przed przekonwertowaniem<br/>
data/modified_dataset_converted.csv - plik CSV z znormalizowanymi danymi i usuniętymi niepotrzebnymi kolumnami<br/>

kickstarter.ipynb - Plik Notebook z kodem w języku Python

## Uwagi

Algorytm SVM został zakomentowany ze względu na zbyt długi czas szkolenia.
