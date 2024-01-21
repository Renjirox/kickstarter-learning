# kickstarter-learning

Repozytorium z projektem do machine learning wykorzystującym dane z Kickstarter'a.

## Wyjaśnienie kolumn:

ID - ID Projektu
deadline - Deadline projektu w czasie UNIX
goal - Cel projektu w USD
launched - Czas wystartowania projektu w czasie UNIX
pledged - Ilość pieniędzy zebranych
state - Stan projektu | 1 = Zakończony powodzeniem | 0 - Zakończony niepowodzeniem
backers - Ilość osób które wsparły projekt

## Struktura projektu:

data/ks-projects-201612.csv - plik CSV z danymi przed przekonwertowaniem
data/modified_dataset_converted.csv - plik CSV z znormalizowanymi danymi i usuniętymi niepotrzebnymi kolumnami

kickstarter.ipynb - Plik Notebook z kodem w języku Python

## Uwagi

Algorytm SVM został zakomentowany ze względu na zbyt długi czas szkolenia.
