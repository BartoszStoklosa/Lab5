Plik drinks.csv zawiera ilości porcji spożytego alkocholu oraz agólnej sumy sporzytego alkoholu w różnych krajach, plik znajduję się w folderze ../Orginaldata/. Naszym zadaniem było wyodrębnienie ilości porcji spożytych alkoholi do jednej tabeli oraz ilości sporzytego alkoholu sumarycznie do drugiej tabeli. 

* wgrałem dane z postaci csv i zapisałęm je w zmiennej typu pandac.DataFrame

* dane były automatycznie podzielone co mocno ułatwiło przetworzenie struktury

* nie istniały też dane niekompletne, kraje które nie spożywają alkoholu np. "Afghanistan" też są wartościowymi danymi 

* wyodrębniłem z bazowej bazy danych kolumny z ilościami porcji spożytych alkoholi i zapisałem w osobnej bazie

* ten sam zabieg powtórzyłem z kolumną total_litres_of_pure_alcohol