# 💻 TASK 1 💻


## ✔️ Subtask 1

10 punktów 🙂

## ✔️ Subtask 3


Cześć, jestem Milena.
<p align="justify">Obecnie jestem w trakcie zmiany mojej ścieżki zawodowej. Szukam więc wszelkich sposobów i możliwości, które mogłyby pomóc mi zrealizować ten cel. Udział w challenge portfolio jest jednym z nich. Mam nadzieję, że dzięki wyzwaniu, poszerzę i uporządkuję swoją wiedzę, którą zdobywałam samodzielnie przez ostatnie kilka miesięcy. Poza tym, przede wszystkim, liczę na to, że poprzez zaangażowanie w projekty, zdobędę praktyczne umiejętności i będę mogła wykorzystać je w przyszłości w pracy. Ponadto chcę poznać praktyczny aspekt zawodu testera, a domyślam się, że może różnić się on nieco od tego przedstawionego w Sylabusie. Myślę, że dzięki wsparciu mentorek i grupy, będzie mi łatwiej pokonać swoje obawy i wątpliwości. Mam nadzieję, że zbuduję piękne portfolio, a w przyszłości znajdę swoją pierwszą pracę jako testerka oprogramowania. ☺️</p>


## ✔️ Subtask 4

### 1. Na czym polega ta aplikacja? Do czego służy?

<p align="justify"> ➡️ Jest to aplikacja, która umożliwia osobom poszukującym uzdolnionych piłkarzy ('łowcy talentów' - ang. scouts) przeglądanie zapisanych w bazie zawodników. Mają oni dostęp do wielu danych dotyczących piłkarzy, takich jak np. dane kontaktowe, pozycja zawodnika, klub, w którym występuje, parametry fizyczne itd. Aplikacja zapewnia im również możliwość dodania nowego gracza, a także edycji wprowadzonych danych. Dzięki aplikacji 'łowcy talentów' mogą śleczić informacje dotyczące rozegranych przez danego piłkarza meczów oraz dodać i edytować mecz. Mają oni także dostęp do raportów - mogą je czytać, tworzyć i edytować.</p>

<hr>
<hr>

### 2. Funkcjonalności, które posiada aplikacja:

<p align="justify"> 1️⃣ DEV TEAM CONTACT - funkcja, która ma służyć, do kontaktu z zespołem deweloperskim, prawdopodobnie w celu zgłoszenia ewntualnych problemów z działaniem aplikacji.</p>

+ INTUICYJNOŚĆ - SUGESTIE: 
     * Funkcja nie jest do końca intuicyjna. Przydałby się tutaj tooltip z wyjaśnieniem, do czego służy ten link i gdzie zostaniemy przekierowani.
     
<hr>
    
 <p align="justify"> 2️⃣ Dodaj gracza - funkcja umożliwia dodanie nowego piłkarza do bazy zawodników. Pozwala na podanie wielu informacji na temat danego gracza.</p>
 
 + INTUICYJNOŚĆ - SUGESTIE: 
     * Nieintuicyjne pola formularza: 'Łączy nas piłka', '90 minut', 'Języki' - użytkownik może mieć problem z rozszyfrowaniem, jakie informacje należy tutaj podać.
     * Brak focusu na pierwsze pole formularza po wczytaniu formularza - byłoby to wygodniejsze dla użytkownika, gdyby kursor umożliwiający wprowadzanie danych znajdował się w pierwszym polu.
     * Drop-down list - zamiast możliwości samodzielnego podawania informacji w przypadku tych pól formularza, gdzie występuje ograniczona liczba możliwych opcji do podania np. 'Poziom rozgrywek', 'Główna pozycja', 'Pozycja alternatywna'.
     
     ![]( https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screen/Intuicyjnosc-dodaj_gracza.png)
   
     * Przekierowanie na stronę edycj po zapisaniu danych piłkarza jest nieintuicyjne. Użytkownik może nie chcieć od razu modyfikować wprowadzonych danych. Lepszym rozwiązaniam byłoby przekierowanie na stronę z tabelą wynikową zapisanych w bazie piłkarzy.
     * W przypadku próby dodania zawodnika z nieprawidłowo wypełnionymi polami formularza, pojawia się informacja 'Nie udało się dodać gracza'. Użytkownik nie dostaje informacji dlaczego to się nie powiodło i jakie pola formularza są błędnie wypełnione.
 
 ![]( https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screen/Intuicyjnosc-nieudane_dodanie_gracza.png)
 
 <hr>
 
 <p align="justify"> 3️⃣ Edytuj gracza - funkcja umożliwia modyfikację danych piłkarza wcześniej zapisanego w bazie.</p>

 
  + INTUICYJNOŚĆ - SUGESTIE:
       * Po wrpowadzeniu zmian w danych zawodnika i kliknięciu przycisku 'SUBMIT', pojawia się informacja: 'Zapisano gracza', ale użytkownik nadal pozostaje na stronie edycji. Jest to nieintuicyjne, lepszym rozwiązaniem byłoby przekierowanie użytkownika na stronę z tabelą wynikową.
       * Dodanie przycisku 'RETURN' - sprawdziłby się on w sytuacji, kiedy użytkownik zmieniłby zdanie i nie chciałby jednak modyfikować informacji dotyczących danego zawodnika.
 
  ![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screen/INTUICYJNOSC-edytuj_gracza.png)
  
  <hr>
  
  <p align="justify"> 4️⃣ Przeglądanie danych zapisanych w bazie piłkarzy. Użytkownik ma tutaj dostęp do dodatkowych funkcji:</p>
  
  + Download CSV - umożliwia pobranie pliku w formacje CSV z danymi 10 aktualnie wyświetlanych na stronie piłkarzy.
  + Print - możliwość wydrukowania danych 10 aktualnie wyświetlanych na stronie piłkarzy.
  + View Columns - pozwala na wyświetlanie tylko wybranych kolumn. Użytkownik może zdecydować, które unformacje o zawodnikach chce przeglądać.
  + Filter Table - możliwość filtrowania danych według wybranych parametrów. Zwraca w tabeli wynikowej dane tylko tych piłkarzy, którze spełniają zdefiniowane warunki.
 
  + INTUICYJNOŚĆ - SUGESTIE:
       * Pole wyszukiwarki powinno się czyścić po wyszukaniu danych określonych zawodników, co umożliwiałoby od razu wprowadzenie nowego hasła do wyszukiwania.
       
 <hr>
       
 <p align="justify"> 5️⃣ Przeglądanie informacji o meczach rozegranych przez danego zawodnika. Użytkownik na tej podstronie ma dostęp do dodatkowych funkcji:</p>
 
 + Edytyj - umożliwia edycję wprowadzonych danych dotyczących określonego meczu rozegranego przez piłkarza.
 + Dodaj raport - funkcja pozwala na dodanie nowego raportu dotyczącego danego meczu rozegranego właśnie przez tego piłkarza.
 + Rozpocznij mecz - funkcja, która umożliwia dodanie do raportu informacji o zdarzeniach, które miały miejsce w trakcie meczu.
 
 + INTUICYJNOŚĆ - SUGESTIE:
      * Funkcja rozpocznij mecz - jest nieintuicyjna, użytkownik może mieć problem z odgadnięciem, co się pod nią kryje. Przydałby się jakiś opis tej funkcji i wyjaśnienie działań, które są tutaj możliwe do wykonania. Pomocne mogły także okazać się tooltipy dla przycisków pozwalających sterować meczem. Brak informacji odnoście tego, do czego one służą, utrudnia korzystanie z tej funkcji.
      
          ![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screen/INTUICYJNOSC-rozpocznij_mecz.png)
          
<hr>
      
 <p align="justify"> 6️⃣ Przeglądanie raportów dotyczących określonego meczu. Użytkownik na tej podstronie ma dostęp do dodatkowych funkcji:</p>
 
  + Edytyj - umożliwia modyfikację danych w raporcie.
  
  
<hr>
<hr>
  
### 3. Jakie funcje dodałabym/ zmieniłabym?
  
 ❌ Usunęłabym ze 'Strony głównej' możliwość śledzenia ostatnich aktywności, dokonywanych również przez innych użytkowników aplikacji - ze względów bezpieczeństwa.
 
 ❗ Zmodyfikowałabym funkcję edycji piłkarza/meczu/raportu - tak aby użytkownik miał możliwość modycikacji danych tylko tego piłkarza/meczu/raportu, które sam dodał do bazy, a nie wszystkich, także dodanych przez innych użytkowników aplikacji.
 
 ❗ W przypadku funkcji 'Dodaj gracza' - po uzupełnieniu pól formularza i przeładowaniu strony, pomocne mogłoby okazać się zapamiętanie danych wpisanych do formularza, tak żeby użytkownik nie musiał uzupełniać wszystkich pól na nowo.
 
➕ Wprowadziłabym przekierowanie użytkownika na stronę z tabelą wynikową - również po dokonaniu edycji danych dotyczących meczu/raportu i kliknięciu przycisku 'SUBMIT'.
 
➕ Dodałabym funkcję umożliwiającą usunięcie piłkarza/meczu/raportu. Użytkownik powinien mieć możliwość usunięcia danych, ale tylko tych, które sam wprowadził i zapisał w aplikacji.
 
➕ Dodałabym możliwość przejścia do zakładek 'Mecze' i 'Raporty' także ze 'Strony głównej', a nie tylko z podstrony edycji określonego zawodnika.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screen/INTUICYJNOSC-podstrony.png)
 
➕ Dodałabym możliwość wyszukiwania i filtrowania meczów i raportów według zdefiniowanych wartości i parametrów.

➕ Dodanie przycisku 'RETURN' - sprawdziłby się także na podstronie edycji meczu i raportu w sytuacji, kiedy użytkownik zmieniłby zdanie i nie chciałby jednak modyfikować danych.

➕ Po dokonaniu edycji danych dotyczących zawodnika/meczu/raportu i kliknięciu przycisku 'Wstecz' - powinno pojawić się ostrzeżenie, z pytaniem, czy użytkownik na pewno chce opuścić stronę bez zapisania wprowadzonych danych.
 
<hr>
<hr>

### 3. Ocena interfejsu aplikacji:

<hr>
<hr>

### 4. Potencjalne błędy:

🐞 Brak jakiejkolwiek walidacji pól formularza (oprócz pola 'E-mail') - możliwość wprowadzenia różnego typu danych/znaków, brak ograniczeń, co do liczby, przedziału wprowadzonych znaków.

![]()

🐞 Po klikcięciu w link 'DEV TEAM CONTACT' - użytkownik zostaje przekierowany na stronę aplikacji 'slack'.

![]()

🐞 Możliwość zapisania w bazie wielu graczy z takimi samymi danymi.

![]()

🐞 Nieaktywny przycisk 'CLEAR' na stronie edycji gracza/meczu.

![]() 

🐞 Nieistniejący zasób - użytkownik powinien zostać przekierowany na stronę z kodem opdowiedzi 404 i informacją 'Not Found'.

![]() 

🐞 Nieprawidłowo obsłużony komunikat błędu. W przypadku zmodyfikowania udresu URL i wpisania id nieistniejącego w bazie zawodnika - użytkownik zostaje przekierowany na stronę z informacją : 'An error 500 occurred on server'. Użytkownik powinien zostać przekierowany na stronę z kodem opdowiedzi 404 i informacją 'Not Found'.

![]()

🐞 W przypadku wpisania zbyt dużej liczby znaków w określone pole formularza - w tabeli wynikowej wartość ta nachodzi na inne elementy. 

![]()

🐞 Przy przeglądaniu danych piłkarzy i wybraniu określonych kolumn, które mają zostać wyświetlone, a następnie przejściu na kolejną podstronę, do tabeli wynikowej automatycznie zostają dodane kolumny: 'Wiek' i 'Recenzja'. Kolumny te nie były pierwotnie zaznoczone, jako te, które mają być wyświetlone.

![]()

🐞 Na stronie edycji raportu przycisk 'SAVE', ze względu na swoje zdefiniowane położenie, przy przewijaniu strony, nachodzi na inne elementy.

![]()

🐞 Będąc na stronie edycji danego zawodnika, po przejściu na zakładkę 'Raporty' i kliknięciu przycisku 'DODAJ RAPORT' - użytkownik zostaje przeniesiony na zakładkę 'Mecze'. 

![]()

🐞 Brak komunikatów walidacyjnych dla wymaganych pól formularza w przypadku próby wysłania pustego formularza. Kominikat walidacyjny pojawia się tylko przy pierwszym wymaganym polu, czyli polu 'Imię'.

![]()

🐞 Warning w konsoli.

![]()

🐞 Brak przekierowania na stronę raportu lub jakiejkolwiek akcji po kliknięciu w link: 'WRÓĆ DO RAPORTU'.

![]()

🐞 Podczas korzystania z aplikacji, po wybraniu preferowanego języka jako polski - część zawartości strony wyświetlana jest w języku angielskim.

![]()

🐞 Błędy językowe na 'Stronie głównej' aplikacji.

![]()

🐞 Funkcja sortowania wyników w tabeli dodanych piłkarzy nie działa prawidłowo. 

![]()

🐞 Brak zabezpieczenia niektórych endpointów. Dostęp do danych bez jakiejkolwiek autoryzacji z aplikacji zewnętrznej (Postman) lub poprzez wklejenie adresu URL w nowym oknie przeglądarki w trybie Incognito. 

![]()

🐞 Nieprawidłowo zapisujęce się dane w przypadku skorzystania z funkcji 'Download CSV'.

![]()

🐞 Funkcja wyszukiwania nie działa prawidłowo. Po wpisaniu szukanej frazy i przejściu na kolejną stronę tabeli wynikowej - wyświetlane dane nie są już zgodne z wyszukiwanym hasłem.

![]()






















































