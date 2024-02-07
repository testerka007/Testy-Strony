Projekty Testowe

Witam mam na imię Dawid kilian i jak już wiesz jest to moje repozytorium.
Zostały tu opisane różne projekty.
Pierwszy projekt dotyczy strony internetowej Gildia.pl
Opis Strony:
Gildia.pl - Portal zajmuje się kulturą i rozrywką w szerokim rozumieniu: od literatury i komiksu, przez film i muzykę, po gry komputerowe, bitewne i RPG. Istnieją również działy zajmujące się popularyzowaniem nauki i badaniem niewyjaśnionych zjawisk paranaukowych. Formuła serwisu Gildia.pl obejmuje rozbudowane bazy danych, codzienne newsy, recenzje, felietony, polemiki, relacje z festiwali, konwentów i innych wydarzeń kulturalnych. Gildia.pl oferuje również swoim czytelnikom jedno z największych polskojęzycznych forów dyskusyjnych, a także sklep internetowy.
Ale krótko mowiąc jest to księgarnia online w której możesz zamawiać produktu różnego typu jak książki, gry, podkładki itp.

Nawigacja:
W folderze "Test run" znajduje się 5 plików :

1.Projekt_gildia - zawiera link do strony Qase w której zostały opisane Zestawy, przypadki i przebiegi testów, również znajdują się nazwy defektów które są do nich przypisane

2.TestRun_gildia - Plik zawiera informacje na temat zestawów testowych, przypadków testowych ich przebiegu (Do pobrania)

3.TestPlan_Gildia.pl - Plik formatu xls to plik który zawiera informacje na temat projektu_gildia

4.Projekt_Gildia.pl_Testy_automatyczne.side - Przypadki testowe, które zostały zautomatyzowane za pomocą narzędzia SELENIUM IDE.

Exportowanie pliku do SELENIUM IDE:

1.Musisz mieć zainstalowaną wtyczkę SELENIUM IDE w swojej przeglądarcie
2.Uruchom SELENIUM IDE
3.Kliknij przycisk "Open an existing project"
4.Następnie wybierz plik: Projekt_Gildia.pl_Testy_automatyczne.side

Wszystkie zautomatyzowane przypadki testowe zawierają w nazwie identyfikator "TEST-1", który informuję z którym przypadkiem testowym jest powiązany

5.Środowisko - Zawiera informacje na temat środowiska oraz narzędzi wykorzystanych podczas testów


Folder Wada - zawiera defekty odnalezione na stronie Gildia.pl
Każdy defekt jest przypisany do przypadku testowego, gdy wejdziesz do pliku Projekt_gildia.txt i uruchomisz znajdujący się tam Link to zobaczysz, że każdy przypadek testowy ma
identyfikator np : "TEST-2".
W folderze "Wada" każdy defekt zawiera identyczny identyfikator, który informuje o tym do którego przypadku testowego jest przypisany
