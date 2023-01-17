# 💻 TASK 1 💻


## ✔️ Subtask 1

10 punktów 🙂

## ✔️ Subtask 3


<b>Cześć, jestem Milena.</b>
<p align="justify">Obecnie jestem w trakcie zmiany mojej ścieżki zawodowej. Szukam więc wszelkich sposobów i możliwości, które mogłyby pomóc mi zrealizować ten cel. Udział w challenge portfolio jest jednym z nich. Mam nadzieję, że dzięki wyzwaniu, poszerzę i uporządkuję swoją wiedzę, którą zdobywałam samodzielnie przez ostatnie kilka miesięcy. Poza tym, przede wszystkim, liczę na to, że poprzez zaangażowanie w projekty, zdobędę praktyczne umiejętności i będę mogła wykorzystać je w przyszłości w pracy. Ponadto chcę poznać praktyczny aspekt zawodu testera, a domyślam się, że może różnić się on nieco od tego przedstawionego w Sylabusie. Myślę, że dzięki wsparciu mentorek i grupy, będzie mi łatwiej pokonać swoje obawy i wątpliwości. Mam nadzieję, że zbuduję piękne portfolio, a w przyszłości znajdę swoją pierwszą pracę jako testerka oprogramowania. ☺️</p>


## ✔️ Subtask 4

### 1. Na czym polega ta aplikacja? Do czego służy?

<p align="justify"> ➡️ Scouts Panel - jest to aplikacja, która umożliwia osobom poszukującym uzdolnionych piłkarzy ('łowcy talentów' - ang. scouts) przeglądanie zapisanych w bazie zawodników. Mają oni dostęp do wielu informacji dotyczących piłkarzy, takich jak np.: dane kontaktowe, pozycja zawodnika, klub, w którym występuje, parametry fizyczne itd. Aplikacja zapewnia im również możliwość dodania nowego gracza, a także edycji wprowadzonych danych. Dzięki aplikacji, 'łowcy talentów' mogą śledzić informacje dotyczące rozegranych przez danego piłkarza meczów oraz dodać i edytować mecz. Mają oni także dostęp do raportów - mogą je przeglądać, tworzyć i edytować.</p>

<hr>

### 2. Funkcjonalności, jakie posiada aplikacja:

<p align="justify"><b> 1️⃣ DEV TEAM CONTACT </b> - funkcja, która ma służyć, do kontaktu z zespołem deweloperskim, prawdopodobnie w celu zgłoszenia ewentualnych problemów z działaniem aplikacji.

+ <b> INTUICYJNOŚĆ - SUGESTIE:</b>
     * Funkcja nie jest do końca intuicyjna. Przydałby się tutaj tooltip z wyjaśnieniem, do czego służy ten link i gdzie zostaniemy przekierowani.
     
<hr>
    
 <p align="justify"><b> 2️⃣ Dodaj gracza</b> - funkcja umożliwia dodanie nowego piłkarza do bazy zawodników. Pozwala na podanie wielu informacji na temat danego gracza.</p>
 
 + <b>INTUICYJNOŚĆ - SUGESTIE:</b> 
     * Nieintuicyjne pola formularza: 'Łączy nas piłka', '90 minut', 'Języki' - użytkownik może mieć problem z rozszyfrowaniem, jakie informacje należy tutaj podać.
     * Brak focusu na pierwsze pole formularza po wczytaniu formularza - byłoby to wygodniejsze dla użytkownika, gdyby kursor umożliwiający wprowadzanie danych znajdował się od razu w pierwszym polu.
     * Drop-down list - zamiast możliwości samodzielnego podawania informacji w przypadku tych pól formularza, gdzie występuje ograniczona liczba możliwych opcji do podania np. 'Poziom rozgrywek', 'Główna pozycja', 'Pozycja alternatywna'.
     
     ![]( https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screen/Intuicyjnosc-dodaj_gracza.png)
   
     * Przekierowanie na stronę edycji po zapisaniu danych piłkarza jest nieintuicyjne. Użytkownik może nie chcieć od razu modyfikować wprowadzonych danych. Lepszym rozwiązaniem byłoby przekierowanie na stronę z tabelą wynikową zapisanych w bazie piłkarzy.
     * Pole województwo nie jest wymagane, ale wybór wartości dla tego pola jest konieczny do utworzenia raportu, więc może pole to powinno być obowiązkowe już na etapie dodawania i zapisywania danych nowego gracza.
     * W przypadku próby dodania zawodnika z nieprawidłowo wypełnionymi polami formularza, pojawia się informacja 'Nie udało się dodać gracza'. Użytkownik nie dostaje informacji, dlaczego to się nie powiodło i jakie pola formularza są błędnie wypełnione.
 
 ![]( https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screen/Intuicyjnosc-nieudane_dodanie_gracza.png)
 
 
 <hr>
 
 <p align="justify"><b> 3️⃣ Edytuj gracza</b> - funkcja umożliwia modyfikację danych piłkarza wcześniej zapisanego w bazie.</p>

 
  + <b>INTUICYJNOŚĆ - SUGESTIE:</b>
       * Po wprowadzeniu zmian w danych zawodnika i kliknięciu przycisku 'SUBMIT', pojawia się informacja: 'Zapisano gracza', ale użytkownik nadal pozostaje na stronie edycji. Jest to nieintuicyjne, lepszym rozwiązaniem byłoby przekierowanie użytkownika na stronę z tabelą wynikową.
       * Dodanie przycisku 'RETURN' - sprawdziłby się on w sytuacji, gdy użytkownik jednak zmieniłby zdanie i nie chciałby modyfikować informacji dotyczących danego zawodnika.
 
  ![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screen/INTUICYJNOSC-edytuj_gracza.png)
  
  <hr>
  
  <p align="justify"><b> 4️⃣ Przeglądanie danych zapisanych w bazie piłkarzy.</b> Użytkownik ma tutaj dostęp do dodatkowych funkcji:</p>
  
  + **Download CSV** - umożliwia pobranie pliku w formacje CSV z danymi 10 aktualnie wyświetlanych na stronie piłkarzy.
  + **Print** - możliwość wydrukowania danych 10 aktualnie wyświetlanych na stronie piłkarzy.
  + **View Columns** - pozwala na wyświetlanie tylko wybranych kolumn. Użytkownik może zdecydować, które informacje o zawodnikach chce przeglądać.
  + **Filter Table** - możliwość filtrowania danych według wybranych kryteriów. Zwraca w tabeli wynikowej dane tylko tych piłkarzy, które spełniają zdefiniowane warunki.
 
  + **INTUICYJNOŚĆ - SUGESTIE:**
       * Pole wyszukiwarki powinno się czyścić po wyszukaniu danych określonych zawodników, co umożliwiałoby użytkownikowi od razu wprowadzenie nowego hasła do wyszukiwania.
       
 <hr>
       
 <p align="justify"><b> 5️⃣ Przeglądanie informacji o meczach rozegranych przez danego zawodnika</b>. Użytkownik na tej podstronie ma dostęp do dodatkowych funkcji:</p>
 
 + **Edytuj** - umożliwia edycję wprowadzonych danych dotyczących określonego meczu rozegranego przez danego piłkarza.
 + **Dodaj raport** - funkcja pozwala na dodanie nowego raportu dotyczącego danego meczu.
 + **Rozpocznij mecz** - funkcja, która umożliwia dodanie informacji o sytuacjach/akcjach, które miały miejsce w trakcie meczu. Następnie użytkownik ma możliwość zapisania ich i informacje te widoczne są na 'Liście zdarzeń' meczu. A w przypadku generowania nowego raportu - są one zawarte także w nim.
 
 + **INTUICYJNOŚĆ - SUGESTIE:**
      * Funkcja rozpocznij mecz - jest nieintuicyjna, użytkownik może mieć problem z odgadnięciem, co się pod nią kryje. Przydałby się jakiś opis tej funkcji i wyjaśnienie działań, które są tutaj możliwe do wykonania. Pomocne mogłyby także okazać się tooltipy dla przycisków pozwalających sterować meczem. Brak informacji odnoście tego, do czego one służą, utrudnia korzystanie z tej funkcji.
      
          ![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screen/INTUICYJNOSC-rozpocznij_mecz.png)
          
<hr>
      
 <p align="justify"><b> 6️⃣ Przeglądanie raportów dotyczących meczów rozegranych przez danego piłkarza.</b> Użytkownik na tej podstronie ma dostęp do dodatkowych funkcji:</p>
 
  + **Edytuj** - umożliwia modyfikację danych w raporcie.
  
  
<hr>
  
### 3. Jakie funkcje można dodać/zmienić?
  
 ❌ Usunęłabym ze 'Strony głównej' możliwość śledzenia ostatnich aktywności, które są dokonywane również przez innych użytkowników aplikacji - ze względów bezpieczeństwa.
 
 ❗ Zmodyfikowałabym funkcję edycji piłkarza/meczu/raportu - tak aby użytkownik miał możliwość zmiany danych tylko tego piłkarza/meczu/raportu, które sam dodał do bazy, a nie wszystkich, także dodanych przez innych użytkowników aplikacji.
 
 ❗ W przypadku funkcji 'DODAJ GRACZA' i 'DODAJ MECZ'  - po uzupełnieniu pól formularza i przeładowaniu strony, pomocne mogłoby okazać się zapamiętanie danych wpisanych w formularzu, tak żeby użytkownik nie musiał uzupełniać wszystkich pól na nowo.
 
➕ Wprowadziłabym przekierowanie użytkownika na stronę z tabelą wynikową - również po dokonaniu edycji danych dotyczących meczu/raportu i kliknięciu przycisku 'SUBMIT'.

➕ Wprowadziłabym także możliwość dodania nowego zawodnika z poziomu zakładki 'Gracze', tak aby użytkownik, żeby skorzystać z tej funkcji, nie musiał cofać się do 'Strony głównej'.
 
➕ Dodałabym funkcję umożliwiającą usunięcie piłkarza/meczu/raportu. Użytkownik powinien mieć możliwość usunięcia danych, ale tylko tych, które sam wprowadził i zapisał w aplikacji.
 
➕ Dodałabym możliwość przejścia do zakładek 'Mecze' i 'Raporty' także ze 'Strony głównej', a nie tylko z podstrony edycji określonego zawodnika.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screen/INTUICYJNOSC-podstrony.png)
 
➕ Dodałabym możliwość wyszukiwania, sortowania i filtrowania danych także dla meczów oraz raportów.

➕ Dodanie przycisku 'RETURN' - sprawdziłby się także na podstronie edycji meczu i raportu, w sytuacji, kiedy użytkownik zmieniłby zdanie i nie chciałby jednak modyfikować danych.

➕ Po dokonaniu edycji danych dotyczących zawodnika/meczu/raportu i kliknięciu przycisku 'Wstecz' - powinno pojawić się ostrzeżenie, z pytaniem, czy użytkownik na pewno chce opuścić stronę bez zapisania wprowadzonych danych.

➕ Dodałabym również możliwość wyświetlania wszystkich zapisanych danych dotyczących gracza/meczu/raportu bez konieczności przechodzenia na stronę edycji tego zasobu. Użytkownik powinien mieć możliwość wyświetlenia tych informacji i przeczytania ich w komfortowy sposób, a następnie sam mógłby zdecydować, czy chce je edytować.
 
<hr>

### 3. Ocena interfejsu aplikacji:

<hr>

### 4. Potencjalne błędy:

🐞 Brak zabezpieczenia części endpointów. Dostęp do danych bez jakiejkolwiek autoryzacji - z narzędzia Postman lub poprzez wklejenie adresu URL w nowym oknie przeglądarki w trybie Incognito. 

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-bezpieczenstwo.png)

🐞 Możliwość zapisania w bazie wielu graczy z takimi samymi danymi.

![]()

🐞 Funkcja 'View Columns' nie działa prawidłowo. Przy przeglądaniu danych piłkarzy i wybraniu określonych kolumn, które mają zostać wyświetlone, a następnie przejściu na kolejną podstronę, do tabeli wynikowej automatycznie zostają dodane kolumny: 'Wiek' i 'Recenzja'. Kolumny te nie były pierwotnie zaznaczone, jako te, które mają być wyświetlone.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-dodanie_kolumn.png)

🐞 Funkcja sortowania danych w tabeli dodanych piłkarzy nie działa prawidłowo. 

![]()

🐞 Funkcja wyszukiwania nie działa prawidłowo. Po wpisaniu szukanej frazy i przejściu na kolejną podstronę tabeli wynikowej - wyświetlane dane nie są już zgodne z wyszukiwanym hasłem.

![]()

🐞 Brak jakiejkolwiek walidacji pól formularza (oprócz pola 'E-mail') - możliwość wprowadzenia różnego typu danych/znaków. Brak limitu, co do liczby znaków oraz ograniczeń dotyczących zakresu wprowadzanych liczb i dat.

![]()

🐞 Brak komunikatów walidacyjnych dla wymaganych pól formularza w przypadku próby wysłania pustego formularza. Komunikat walidacyjny pojawia się tylko przy pierwszym wymaganym polu, czyli polu 'Imię'.

![]()

🐞 Błędy przy filtrowaniu danych:

+ W przypadku filtrowania danych według kryterium wieku, wykorzystywana jest data, a nie wiek piłkarza. Dlatego do tabeli wynikowej trafiają także zawodnicy, którzy nie osiągnęli jeszcze określonego wieku, a znajdują się jedynie w przedziale wyznaczonym przez przyjęte do filtrowania daty.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-filtrowanie_wiek.png)

+ Przy filtrowaniu wyników według określonego parametru, a następne usunięcie tej wartości i wybraniu filtrowania według innego parametru, zapamiętywana jest wartość poprzedniego kryterium wyszukiwania. Ostatecznie zawodnicy, spełniający oba warunki, trafiają do tabeli wynikowej.

![]()

🐞 Będąc na stronie edycji danego zawodnika, po przejściu na zakładkę 'Raporty' i kliknięciu przycisku 'DODAJ RAPORT' - użytkownik zostaje przeniesiony na zakładkę 'Mecze'. 

![]()

🐞 'Warnings' w konsoli - w czasie korzystania z funkcji sortowania, wyszukiwania, filtrowania danych.

![]()

🐞 Po klikcięciu w link 'DEV TEAM CONTACT' - użytkownik zostaje przekierowany na stronę aplikacji 'slack'.

![]()

🐞 Brak przekierowania na stronę raportu lub jakiejkolwiek akcji po kliknięciu linku: 'WRÓĆ DO RAPORTU'.

![]()

🐞 Nieistniejący zasób - użytkownik powinien zostać przekierowany na stronę z kodem odpowiedzi 404 i informacją 'Not Found'.

![]() 

🐞 Nieprawidłowo obsłużony komunikat błędu. W przypadku zmodyfikowania adresu URL i wpisania id nieistniejącego w bazie zawodnika - użytkownik zostaje przekierowany na stronę z informacją: 'An error 500 occurred on server'. Użytkownik powinien zostać przekierowany na stronę z kodem odpowiedzi 404 i informacją 'Not Found'.

![]()

🐞 Brak ograniczeń co do liczby wprowadzanych języków i załączanych linków z YouTube przy dodawaniu nowego gracza.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-dodaj_jezyk_i_link_YT.png)

🐞 Błędne zapisywanie danych przy dodawaniu nowego meczu dla danego zawodnika. Aby zapisać mecz, nie jest wymagane zaznaczenie żadnego radio buttona (chociaż wybranie którejś opcji powinno być konieczne). Jednak w ciele żądania domyślnie przesyłana jest wartość - 'matchAtHome: false'. Po wejściu w panel edycji tego meczu, zaznaczony jest radio button z wartością 'Mecz wyjazdowy'.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-dodawanie_meczu_radio_button.png)

🐞 Sprawdzając zakładkę Network w konsoli - można zauważyć, że podczas logowania do aplikacji w Response w obiekcie 'user' przesyłana jest bardzo duża (nadmiarowa) ilość danych.

![]()

🐞 W zakładce mecze po wybraniu opcji 'Rozpocznij mecz', użytkownik ma możliwość dodania zdarzeń do meczu. Po przejściu do panelu edycji tego meczu na liście zdarzeń wyświetlane są 'Meta dane', które nie są zrozumiałe i użyteczne dla użytkownika.

![]()

🐞 Nieprawidłowo zapisujące się dane w przypadku skorzystania z funkcji 'Download CSV'.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-download_CSV.png)


🐞 Nieaktywny przycisk 'CLEAR' na stronie edycji gracza/meczu.

![]() 

🐞 W przypadku wpisania zbyt dużej liczby znaków w określone pole formularza - w tabeli wynikowej wartość ta nachodzi na inne elementy. 

![]()

🐞 Podczas korzystania z aplikacji, po wybraniu preferowanego języka jako polski - część zawartości strony wyświetlana jest w języku angielskim.

![]()

🐞 Błędy językowe na 'Stronie głównej' aplikacji.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-bledy_jezykowe.png)

🐞 Na stronie edycji raportu przycisk 'SAVE', ze względu na swoje zdefiniowane położenie, przy przewijaniu strony, nachodzi na inne elementy.

![]()


























































