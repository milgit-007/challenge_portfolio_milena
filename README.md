

# 📜Table of Contents:

### ➡️ TASK 1 - Exploratory Testing of the Scouts Panel Application 

### ✔️ [Subtask 1 - Test](#subtask1)

### ✔️ [Subtask 3 - About me](#subtask3)

### ✔️ [Subtask 4 - Scouts Panel Application](#subtask4)

+ [1. What is the purpose and functionality of this application?](#zad1)
+ [2. What are the features of the application?](#zad2)
+ [3. What additional functions or changes could be made to the application?](#zad3)
+ [4. Assessment of the application's user interface.](#zad4)
+ [5. Identification of potential bugs or issues with the application.](#zad5)

### ➡️ TASK 2 - Test Cases 

### ✔️ [Subtask 1 - Scouts Panel - Test Cases Based on User Stories](#task2_01)

### ✔️ [Subtask 2 - Scouts Panel - Test Cases Based on 'Own Experience'](#task2_02) 

### ✔️ [Subtask 3 - Why we should write Test Cases?](#task2_03) 

### ✔️ [Subtask 4 -  Mobile Application - Pick Eat Up - Test Cases](#task2_04) 

### ➡️ TASK 3 - Bug Reports and Test Report 

### ✔️ [Subtask 1 - Bug Report Template](#task3_01) 

### ✔️ [Subtask 2 - Scouts Panel - Execution of Test Cases and Bug Reports](#task3_02)

### ✔️ [Subtask 3 - Scouts Panel - Test Report](#task3_03)

### ✔️ [Subtask 4 - Scouts Panel - Exploratory Testing - Intellectual Tour](#task3_04)


### ➡️ TASK 4 -  Exploratory Testing and Bug Reports for the OLX Mobile Application and SwipeTo 

### ✔️ [Subtask 1 - Mobile Application Bug Report Template](#task4_01) 

### ✔️ [Subtask 2 - Exploratory Testing of the OLX Application and Bug Reports](#task4_02)

### ✔️ [Subtask 3 - OLX Mobile Application Analysis and My Feedback](#task4_03)

### ✔️ [Subtask 4 - SwipeTo - Bug Reports - Jira](#task4_04)

### ➡️ TASK 5 - SQL - part 1 

### ✔️ [Subtask 1 - SQL Statements I Have Learned](#task5_01) 

### ✔️ [Subtask 2 - Environment Configuration and Database Import](#task5_02)

### ✔️ [Subtask 3 - SQL Exercises - part 1](#task5_03)

### ➡️ TASK 6 - SQL - part 2 

### ✔️ [Subtask 1 - SQL Exercises - part 2](#task6_01)

### ✔️ [Subtask 2 - ISTQB - Test](#task6_02)

### ✔️ [Subtask 3 - Portfolio ](#task6_03)


<hr>

# 💻 TASK 1 💻

## ✔️<a name="subtask1">Subtask 1</a>

10 punktów 🙂

## ✔️<a name="subtask3">Subtask 3</a>

<b>Cześć, jestem Milena.</b>

Obecnie jestem w trakcie zmiany mojej ścieżki zawodowej. Szukam więc wszelkich sposobów i możliwości, które mogłyby pomóc mi zrealizować ten cel. Udział w challenge portfolio jest jednym z nich. Mam nadzieję, że dzięki wyzwaniu, poszerzę i uporządkuję swoją wiedzę, którą zdobywałam samodzielnie przez ostatnie kilka miesięcy. Poza tym, przede wszystkim, liczę na to, że poprzez zaangażowanie w projekty, zdobędę praktyczne umiejętności i będę mogła wykorzystać je w przyszłości w pracy. Ponadto chcę poznać praktyczny aspekt zawodu testera, a domyślam się, że może różnić się on nieco od tego przedstawionego w Sylabusie. Myślę, że dzięki wsparciu mentorek i grupy, będzie mi łatwiej pokonać swoje obawy i wątpliwości. Mam nadzieję, że zbuduję piękne portfolio, a w przyszłości znajdę swoją pierwszą pracę jako testerka oprogramowania. ☺️

## ✔️<a name="subtask4">Subtask 4</a>

### <a name="zad1">1. Na czym polega ta aplikacja? Do czego służy?</a>

➡️ Scouts Panel ⚽ - jest to aplikacja, która umożliwia osobom poszukującym uzdolnionych piłkarzy ('łowcy talentów' - ang. scouts) przeglądanie zapisanych w bazie zawodników. Mają oni dostęp do wielu informacji dotyczących piłkarzy, takich jak np.: dane kontaktowe, pozycja zawodnika, klub, w którym występuje, parametry fizyczne itd. Aplikacja zapewnia im również możliwość dodania nowego gracza, a także edycji wprowadzonych danych. Dzięki aplikacji, 'łowcy talentów' mogą śledzić informacje dotyczące rozegranych przez danego piłkarza meczów oraz dodać i edytować mecz. Mają oni także dostęp do raportów - mogą je przeglądać, tworzyć i edytować.

<hr>

### <a name="zad2">2. Funkcjonalności, jakie posiada aplikacja:</a>

<b> 1️⃣ Logowanie do aplikacji </b> - poprzez podanie prawidłowego 'Loginu' i 'Hasła' oraz kliknięcie przycisku 'ZALOGUJ'. Na panelu logowania użytkownik ma także dostęp do funkcji <b>'Przypomnij hasło'</b>. 
     
<hr>
    
 <b> 2️⃣ Dodaj gracza</b> - funkcja umożliwia dodanie nowego piłkarza do bazy zawodników. Pozwala na podanie wielu informacji na temat danego gracza.
 
 + <b>INTUICYJNOŚĆ - SUGESTIE:</b> 
     * Nieintuicyjne pola formularza: 'Łączy nas piłka', '90 minut', 'Języki' - użytkownik może mieć problem z rozszyfrowaniem, jakie informacje należy tutaj podać.
     * Brak focusu na pierwsze pole formularza po wczytaniu formularza - byłoby to wygodniejsze dla użytkownika, gdyby kursor umożliwiający wprowadzanie danych znajdował się od razu w pierwszym polu.
     * Drop-down list - zamiast możliwości samodzielnego podawania informacji w przypadku tych pól formularza, gdzie występuje ograniczona liczba możliwych opcji do podania np. 'Poziom rozgrywek', 'Główna pozycja', 'Pozycja alternatywna'.
     
     ![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/Intuicyjnosc-dodaj_gracza.png)
   
     * Przekierowanie na stronę edycji po zapisaniu danych piłkarza jest nieintuicyjne. Użytkownik może nie chcieć od razu modyfikować wprowadzonych danych. Lepszym rozwiązaniem byłoby przekierowanie na stronę z tabelą wynikową zapisanych w bazie piłkarzy.
     * Pole województwo nie jest wymagane, ale wybór wartości dla tego pola jest konieczny do utworzenia raportu, więc może pole to powinno być obowiązkowe już na etapie dodawania i zapisywania danych nowego gracza.
     * W przypadku próby dodania zawodnika z nieprawidłowo wypełnionymi polami formularza, pojawia się informacja 'Nie udało się dodać gracza'. Użytkownik nie dostaje informacji, dlaczego to się nie powiodło i jakie pola formularza są błędnie wypełnione.
 
 ![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/INTUICYJNOSC-nie_zapisano_gracza.png)
 
 
 <hr>
 
 <p align="justify"><b> 3️⃣ Edytuj gracza</b> - funkcja umożliwia modyfikację danych piłkarza wcześniej zapisanego w bazie.</p>

 
  + <b>INTUICYJNOŚĆ - SUGESTIE:</b>
       * Po wprowadzeniu zmian w danych zawodnika i kliknięciu przycisku 'SUBMIT', pojawia się informacja: 'Zapisano gracza', ale użytkownik nadal pozostaje na stronie edycji. Jest to nieintuicyjne, lepszym rozwiązaniem byłoby przekierowanie użytkownika na stronę z tabelą wynikową.
       * Dodanie przycisku 'RETURN' - sprawdziłby się on w sytuacji, gdy użytkownik jednak zmieniłby zdanie i nie chciałby modyfikować informacji dotyczących danego zawodnika.
 
  ![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/INTUICYJNOSC-edytuj_gracza.png)
  
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
      
          ![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/INTUICYJNOSC-rozpocznij_mecz.png)
          
<hr>
      
 <p align="justify"><b> 6️⃣ Przeglądanie raportów dotyczących meczów rozegranych przez danego piłkarza.</b> Użytkownik na tej podstronie ma dostęp do dodatkowych funkcji:</p>
 
  + **Edytuj** - umożliwia modyfikację danych w raporcie.
 
<hr>

<b> 7️⃣ DEV TEAM CONTACT </b> - funkcja, która ma służyć, do kontaktu z zespołem deweloperskim, prawdopodobnie w celu zgłoszenia ewentualnych problemów z działaniem aplikacji.

+ <b> INTUICYJNOŚĆ - SUGESTIE:</b>
     * Funkcja nie jest do końca intuicyjna. Przydałby się tutaj tooltip z wyjaśnieniem, do czego służy ten link i gdzie zostaniemy przekierowani.
     
 <hr>
 
 <b> 8️⃣ Wybór wersji językowej aplikacji </b> - użytkownik może korzystać z aplikacji w języku polskim i angielskim. Opcja możliwości wyboru preferowanego języka jest dostępna na panelu logowania oraz po zalogowaniu w menu bocznym.
 
 <hr>
  
### <a name="zad3">3. Jakie funkcje można ewentualnie dodać/zmienić?</a>
  
 ❌ Ze względów bezpieczeństwa i poufności danych, usunęłabym ze 'Strony głównej' możliwość śledzenia ostatnich aktywności, które są dokonywane również przez innych użytkowników aplikacji.
 
 ❗ Zmodyfikowałabym funkcję edycji piłkarza/meczu/raportu - tak aby użytkownik miał możliwość zmiany danych tylko tego piłkarza/meczu/raportu, które sam dodał do bazy, a nie wszystkich, także dodanych przez innych użytkowników aplikacji.
 
 ❗ W przypadku funkcji 'DODAJ GRACZA' i 'DODAJ MECZ'  - po uzupełnieniu pól formularza i przeładowaniu strony, pomocne mogłoby okazać się zapamiętanie danych wpisanych w formularzu, tak żeby użytkownik nie musiał uzupełniać wszystkich pól na nowo.
 
➕ Wprowadziłabym przekierowanie użytkownika na stronę z tabelą wynikową - również po dokonaniu edycji danych dotyczących meczu/raportu i kliknięciu przycisku 'SUBMIT'.

➕ Wprowadziłabym także możliwość dodania nowego zawodnika z poziomu zakładki 'Gracze', tak aby użytkownik, żeby skorzystać z tej funkcji, nie musiał cofać się do 'Strony głównej'.
 
➕ Dodałabym funkcję umożliwiającą usunięcie piłkarza/meczu/raportu. Użytkownik powinien mieć możliwość usunięcia danych, ale tylko tych, które sam wprowadził i zapisał w aplikacji.
 
➕ Dodałabym możliwość przejścia do zakładek 'Mecze' i 'Raporty' także ze 'Strony głównej', a nie tylko z podstrony edycji określonego zawodnika.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/INTUICYJNOSC-podstrony.png)
 
➕ Dodałabym możliwość wyszukiwania, sortowania i filtrowania danych także dla meczów oraz raportów.

➕ Dodanie przycisku 'RETURN' - sprawdziłby się także na podstronie edycji meczu i raportu, w sytuacji, kiedy użytkownik zmieniłby zdanie i nie chciałby jednak modyfikować danych.

➕ Po dokonaniu edycji danych dotyczących zawodnika/meczu/raportu i kliknięciu przycisku 'Wstecz' - powinno pojawić się ostrzeżenie, z pytaniem, czy użytkownik na pewno chce opuścić stronę bez zapisania wprowadzonych danych.

➕ Dodałabym również możliwość wyświetlania wszystkich zapisanych danych dotyczących gracza/meczu/raportu bez konieczności przechodzenia na stronę edycji tego zasobu. Użytkownik powinien mieć możliwość wyświetlenia tych informacji i przeczytania ich w komfortowy sposób, a następnie sam mógłby zdecydować, czy chce je edytować.
 
<hr>

### <a name="zad4">4. Ocena interfejsu aplikacji:</a>

🔍 Elementy na 'Stronie głównej' mogłyby być rozmieszczone w bardziej atrakcyjny wizualnie sposób. Brakuje tutaj także efektownego, przyciągającego wzrok, logo. Poza tym tytuł i nagłówki nie zwracają na siebie uwagi i wtapiają się w tło. Przydatne mogłyby okazać się wskazówki i podpowiedzi, w jaki sposób użytkownik może korzystać z aplikacji oraz jakie funkcjonalności ona oferuje. Na 'Stronie głównej' pojawiają się też błędy językowe i błędy w pisowni. To wszystko już na starcie nie wpływa na pozytywny odbiór aplikacji.

🔍 Główne funkcje aplikacji powinny być bardziej wyeksponowane. Tak, aby użytkownik nie miał problemu z dotarciem do nich. W tym przypadku utrudnione jest dostanie się do zakładek 'Mecze' i 'Raporty', do których można trafić tylko z poziomu edycji gracza.

🔍 Dane zawodników w zakładce 'Gracze', 'Mecze' i 'Raporty' powinny być zaprezentowane w bardziej czytelny i ciekawy sposób. Poza tym brak ograniczeń co do liczby wprowadzanych znaków, sprawia, że dodawany jest scrollbar, a wówczas przeglądanie tych informacji jest utrudnione i męczące.

🔍 Aplikacja nie jest responsywna. Niektóre treści nie prezentują się dobrze na mniejszych ekranach. Korzystanie z części funkcji jest wówczas utrudnione.

🔍 Aplikacja ta posiada zbyt minimalistyczny interfejs. Jest za bardzo statyczna. Użyte kolory nie są przyjemne w odbiorze. Jasny motyw 'męczy wzrok', więc przydałoby się tutaj zastosowanie bardziej przyjaznych dla oczu barw albo chociażby możliwość wyboru dark mode.

🔍 W aplikacji brakuje także przykuwających uwagę detali. Takie elementy jak: grafiki, galerie, interaktywne treści sprawiłyby, że aplikacja byłaby bardziej atrakcyjna dla użytkownika.

🔍 Sprawdziłyby się tutaj również breadcrumbsy, które pomogłyby użytkownikowi odnaleźć się w aplikacji. Dzięki nim łatwiej byłoby mu śledzić swoją aktualną lokalizację i wrócić do poprzednich podstron bez konieczności używania przycisku 'Wstecz' przeglądarki.

<hr>

### <a name="zad5">5. Potencjalne błędy:</a>

🐞 Brak zabezpieczenia części endpointów. Dostęp do danych bez jakiejkolwiek autoryzacji - z narzędzia Postman lub poprzez wklejenie adresu URL w nowym oknie przeglądarki w trybie Incognito. 

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-bezpieczenstwo.png)

<hr>

🐞 Możliwość zapisania w bazie wielu graczy z takimi samymi danymi.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-mozliwosc_zapisania_wielu_graczy_z_tymi_samymi_danymi.png)

<hr>

🐞 Funkcja 'View Columns' nie działa prawidłowo. Przy przeglądaniu danych piłkarzy i wybraniu określonych kolumn, które mają zostać wyświetlone, a następnie przejściu na kolejną podstronę, do tabeli wynikowej automatycznie zostają dodane kolumny: 'Wiek' i 'Recenzja'. Kolumny te nie były pierwotnie zaznaczone, jako te, które mają być wyświetlone.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-dodanie_kolumn.png)

<hr>

🐞 Funkcja sortowania danych w tabeli dodanych piłkarzy nie działa prawidłowo. 

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-sortowanie.png)

<hr>

🐞 Funkcja wyszukiwania nie działa prawidłowo. Po wpisaniu szukanej frazy i przejściu na kolejną podstronę tabeli wynikowej - wyświetlane dane nie są już zgodne z wyszukiwanym hasłem.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-wyszukiwarka.png)

<hr>

🐞 Brak jakiejkolwiek walidacji pól formularza (oprócz pola 'E-mail') - możliwość wprowadzenia różnego typu danych/znaków. Brak limitu, co do liczby znaków oraz ograniczeń dotyczących zakresu wprowadzanych liczb i dat.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-brak_walidacji_pol_formularza.png)

<hr>

🐞 Brak komunikatów walidacyjnych dla wymaganych pól formularza w przypadku próby wysłania pustego formularza. Komunikat walidacyjny pojawia się tylko przy pierwszym wymaganym polu, czyli polu 'Imię'.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-komunikaty_walidacyjne_brak.png)

<hr>

🐞 Błędy przy filtrowaniu danych:

+ W przypadku filtrowania danych według kryterium wieku, wykorzystywana jest data, a nie wiek piłkarza. Dlatego do tabeli wynikowej trafiają także zawodnicy, którzy nie osiągnęli jeszcze określonego wieku, a znajdują się jedynie w przedziale wyznaczonym przez przyjęte do filtrowania daty.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-filtrowanie_wiek.png)

<hr>

+ Przy filtrowaniu wyników według określonego parametru, a następne usunięcie tej wartości i wybraniu filtrowania według innego parametru, zapamiętywana jest wartość poprzedniego kryterium wyszukiwania. Ostatecznie zawodnicy, spełniający oba warunki, trafiają do tabeli wynikowej.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-filtrowanie_zapamietywanie_poprzednich_parametrow.png)

<hr>

🐞 Będąc na stronie edycji danego zawodnika, po przejściu na zakładkę 'Raporty' i kliknięciu przycisku 'DODAJ RAPORT' - użytkownik zostaje przeniesiony na zakładkę 'Mecze'. 

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-klikniecia-dodaj-raport-przenosi-nas-na-zakladke-mecze.png)

<hr>

🐞 'Warnings' w konsoli - w czasie korzystania z funkcji sortowania, wyszukiwania, filtrowania danych.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/WARNING-console.png)

<hr>

🐞 Po klikcięciu w link 'DEV TEAM CONTACT' - użytkownik zostaje przekierowany na stronę aplikacji 'slack'.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-dev-contact-team.png)

<hr>

🐞 Brak przekierowania na stronę raportu lub jakiejkolwiek akcji po kliknięciu linku: 'WRÓĆ DO RAPORTU'.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-link_wroc_do_raportu_nie_dziala.png)

<hr>

🐞 Nieistniejący zasób - użytkownik powinien zostać przekierowany na stronę z kodem odpowiedzi 404 i informacją 'Not Found'.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-nieistniejacy_zasob.png) 

<hr>

🐞 Nieprawidłowo obsłużony komunikat błędu. W przypadku zmodyfikowania adresu URL i wpisania id nieistniejącego w bazie zawodnika - użytkownik zostaje przekierowany na stronę z informacją: 'An error 500 occurred on server'. Użytkownik powinien zostać przekierowany na stronę z kodem odpowiedzi 404 i informacją 'Not Found'.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-zly_komunikat_bledu.png)

<hr>

🐞 Brak ograniczeń co do liczby wprowadzanych języków i załączanych linków z YouTube przy dodawaniu nowego gracza.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-dodaj_jezyk_i_link_YT.png)

<hr>

🐞 Błędne zapisywanie danych przy dodawaniu nowego meczu dla danego zawodnika. Aby zapisać mecz, nie jest wymagane zaznaczenie żadnego radio buttona (chociaż wybranie którejś opcji powinno być konieczne). Jednak w ciele żądania domyślnie przesyłana jest wartość - 'matchAtHome: false'. Po wejściu w panel edycji tego meczu, zaznaczony jest radio button z wartością 'Mecz wyjazdowy'.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-dodawanie_meczu_radio_button.png)

<hr>

🐞 Sprawdzając zakładkę Network w konsoli - można zauważyć, że podczas logowania do aplikacji w Response w obiekcie 'user' przesyłana jest bardzo duża (nadmiarowa) ilość danych.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-response_nadmiarowe_dane.png)

<hr>

🐞 W zakładce mecze po wybraniu opcji 'Rozpocznij mecz', użytkownik ma możliwość dodania zdarzeń do meczu. Po przejściu do panelu edycji tego meczu na liście zdarzeń wyświetlane są 'Meta dane', które nie są zrozumiałe i użyteczne dla użytkownika.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-lista_zdarzen.png)

<hr>

🐞 Nieprawidłowo zapisujące się dane w przypadku skorzystania z funkcji 'Download CSV'.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-download_CSV.png)

<hr>


🐞 Nieaktywny przycisk 'CLEAR' na stronie edycji gracza/meczu.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-nieaktywny_przycisk.png) 

<hr>

🐞 W przypadku wpisania zbyt dużej liczby znaków w określone pole formularza - w tabeli wynikowej wartość ta nachodzi na inne elementy. 

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-overlap.png)

<hr>

🐞 Podczas korzystania z aplikacji, po wybraniu preferowanego języka jako polski - część zawartości strony wyświetlana jest w języku angielskim.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-pomieszanie_jezykow.png)

<hr>

🐞 Błędy językowe i błędy w pisowni na 'Stronie głównej' aplikacji i stronie edycji gracza.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-bledy_jezykowe.png)

<hr>

🐞 Na stronie edycji raportu przycisk 'SAVE', ze względu na swoje zdefiniowane położenie, przy przewijaniu strony, nachodzi na inne elementy.

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/BUG-raport_przycisk_save_nachodzi_na_inne_elementy.png)

<hr>

# 💻 TASK 2 💻

## ✔️<a name="task2_01">Subtask 1</a>

### 📁 [Test Cases Based on User Stories](https://docs.google.com/spreadsheets/d/1rBmQfs4Acsg6MUCn8uuYeGAkeGYqnxBsLcjCWMfGNps/edit#gid=0)

## ✔️<a name="task2_02">Subtask 2</a>

### 📁 [Test Cases Based on 'Own Experience'](https://docs.google.com/spreadsheets/d/1jU3SUgaWm0FiRyUpTnnJ7LiWlG9B46tyOAGxn2N8nM0/edit#gid=764302285)

## ✔️<a name="task2_03">Subtask 3</a>

![](https://media.makeameme.org/created/tests-tests-everywhere-ikkczl.jpg)


### 👉 Why we should write test cases? Why test cases are important? 

📌 Test cases provide a structured approach to testing and ensure that all important areas of the software are covered and that testing is systematic and thorough.

📌 Test cases guarantee that software meets its requirements by verifying the software behaves as expected.

📌 Using test cases, testers can track progress and measure results, and can create test reports based on test results.

📌 Test cases, providing a common understanding of what should be tested, improving communication and teamwork.

📌 The purpose of test cases is also to help identify and reproduce bugs by providing clear steps on how to replicate them.

📌 Test cases can be useful for regression testing as well.

📌 When writing test cases, we can identify edge cases and negative scenarios that need to be considered when testing the software.

📌 Test cases can be useful when converting tests into automated scripts.

📌 Test cases can be a very good source of information about the system for new team members.

📌 Test cases can also be used in acceptance testing to confirm that the application works as expected.

📌 When writing test cases based on requirements, user stories and acceptance criteria, we can find defects and inconsistencies in them.

📌 By writing test cases, we can prepare test data that may be needed during test execution.

## ✔️<a name="task2_04">Subtask 4</a>

### 📁 [Pick Eat Up - Test Cases](https://docs.google.com/spreadsheets/d/1p0qtzf-GonfvHYDX-CW0mW0lt6H0xA5zIXGsgtavdUg/edit#gid=0)

<hr>

# 💻 TASK 3 💻

## ✔️<a name="task3_01">Subtask 1</a>

### 📁 [Bug Report Template](https://docs.google.com/spreadsheets/d/1LczMRwB2G6M3G79CQN9x3UoWwBZQwXsAaeiIUMewWcY/edit#gid=142669186)

## ✔️<a name="task3_02">Subtask 2</a>

### 📁 [Execution of Test Cases Written Based on User Stories](https://docs.google.com/spreadsheets/d/1Lxvl5lHW2tqgAJVLrWT3dhdB5jVweaJiMbZk1CDeLQs/edit?usp=share_link)

### 📁 [Execution of Test Cases Written Based on 'Own Experience'](https://docs.google.com/spreadsheets/d/1Etp_z5JsIklDq-6SHOj0OC7Tb2CBi-pcsM996rsNoEc/edit?usp=share_link)

### 📁 [Bug Reports](https://docs.google.com/spreadsheets/d/1LczMRwB2G6M3G79CQN9x3UoWwBZQwXsAaeiIUMewWcY/edit#gid=976627270)

## ✔️<a name="task3_03">Subtask 3</a>

### 📁 [Test Report](https://docs.google.com/document/d/1oXkOWjZgBjTzP-3KQuXjIUv_hPcjwA61mI8LdLvpZgA/edit?usp=share_link)

## ✔️<a name="task3_04">Subtask 4</a>

### 📁 [Exploratory Testing - Intellectual Tour 💡](https://docs.google.com/spreadsheets/d/1FLA8Eiy_HHp-hLkXB-UcoXh6t79-7fyzNsfE0GA-H0w/edit?usp=share_link)

<hr>

# 💻 TASK 4 💻

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Screenshots/olx-logo.png)

## ✔️<a name="task4_01">Subtask 1</a>

### 📁 [Mobile Application Bug Report Template](https://docs.google.com/spreadsheets/d/1R_yWdkP4XF8otJ9yEAID0kaVwPvEB2_pgyNP5vC7vtU/edit#gid=0)

## ✔️<a name="task4_02">Subtask 2</a>

### 📁 [Exploratory Testing of the OLX Application and Bug Reports](https://docs.google.com/spreadsheets/d/1R_yWdkP4XF8otJ9yEAID0kaVwPvEB2_pgyNP5vC7vtU/edit#gid=622446418)

## ✔️<a name="task4_03">Subtask 3</a>


### 1️⃣ What is this application used for? What is the purpose of this application?

<b> 🔶 OLX - is an application that allows users to buy and sell a wide range of new or second-hand products and services. The application makes easy and convenient transactions between buyers and sellers. The purpose of OLX is to connect buyers and sellers, and provide an easy-to-use platform for users to buy and sell goods. The application has many functionalities:</b>

🔹 Users can create an account, also via their email or social media.

🔹 Users can easily add their goods and services for sale by creating an offer with details such as product title, category, description, price, photos, localization, and contact information. 

🔹 Users can also browse items - the application provides search functionality, as well as filter offers to help users fast find what they are looking for. Users can search for products for specific keywords and filter the results based on different criteria like category, location, price, etc. The application also provides options to sort results by cheapest, most expensive, newest, or based on the user's preference. In addition, the application can use the user's location to show him relevant offers in his area.

🔹 Besides, users can save their favorite offers for quick access later, as well as save their observed searches.

🔹 Users can communicate with each other directly within the application to ask questions, negotiate prices, discuss product details, and so on.

🔹 The application allows secure in-app payments using various payment methods, making it easy to complete transactions securely and efficiently.

🔹 The application has a user profile section that allows users to view and manage their listings, messages, payments, and settings. Here users can manage their listings, including editing, deleting, or marking them as sold. In addition, they can create a candidate profile, view matched job offers, apply for jobs, and browse sent job applications. Users can set alerts to receive notifications of new offers that match their preferences.

🔹 The application offers customer support through a dedicated help center and a contact form for users to get answers to their questions and solve any problems.

### 2️⃣ Who are the end users of the application?

👥 The OLX application is targeted to a wide range of users, including individuals and businesses. The application allows them to buy and sell used or new items from various categories such as automotive, property, electronics, fashion, etc. They can easily add their items for sale, browse other users' listings and communicate with potential buyers. They can also search for work opportunities and offer their services.

### 3️⃣ In your opinion, is the application user-friendly?

🚀 The application has a user-friendly interface, making navigation easy and effortless. The layout is intuitive, and I can quickly figure out how to use the application and find the necessary functionalities. Adding offers through the application is simple, and the form can be filled out efficiently. Unfortunately, scrolling down when filling in the offer-adding form is problematic, and makes it difficult to complete the form by entering all required information, which sometimes even resulted in my having to leave the offer-adding page. In addition, clearer feedback on actions like validation messages or confirmations would be useful, because they don't always accurately reflect the situation. A positive point of the application is the ability to personalize the interface, notifications, or settings, including the option to switch between dark and light mode.

### 4️⃣ How would you improve the application? Do you have any ideas for additional functionality?

 ❗ I have a few suggestion that can be improve the OLX application:

+ Improving form security to prevent the use of HTML entities and tags and other invalid data.
+ Verifying added listings to ensure that the added details, including price, accurately reflect the products.
+ Improving the user experience by fixing the problem of the page scrolling down when filling in the form to add an offer.
+ Providing clear and relevant feedback on actions such as validation or confirmation messages.
+ Adding field validation when filling in some fields.
+ Changing the input types as numeric by default if the valid values are numbers.
+ Solving the problem of not being able to change the display of offers on the filter setting page.

➕ I have several potential additional functionalities that could be added to the OLX application:

+ Option to add several similar products from the same category at once.
+ Option for bidding on items by buyers.
+ A feature that would allow users to view listings on the map, making it easier to find offers in their area.
+ Option to join groups and conversations for people interested in a particular category of items, so that they can share their opinions and experiences.

### 5️⃣ What differences do you notice between testing a web application and a native application?

🔸 Testing native applications should involve testing on multiple devices and operating systems, which can be more time-consuming than testing a web application. On the other hand, web apps need to be tested on different browsers, devices, and operating systems.

🔸 Testing native applications are different because native applications can access device-specific features and data, such as the camera, contacts, push notifications, and GPS, whereas web applications do not have direct access to these components.

🔸 Web applications have a common user interface that runs on all browsers, while native applications have a platform-specific user interface. Native applications have a simpler and more intuitive user interface, as this allows the application to be more user-friendly. Access to the main functions must be easy and quick. Navigation should also be intuitive and easily accessible. This is particularly important for mobile devices, where screen size is limited and users are more likely to use apps on the go, etc.

🔸 Testing for web applications includes testing page load times, web speed, and the general responsiveness of the application. On the other hand, testing for native apps includes testing for battery, memory, and processor usage.

🔸 Web apps can be tested using browser-based tools, while native apps require specialized testing tools.

📱 In addition, in testing mobile applications, attention should be paid to: 
+ Verification of the navigation of the application, whether it is intuitive, or easily usable.
+ Verify that applications can be seamlessly downloaded to the device, installed, and run on different mobile device configurations. 
+ Verification that updates install correctly, work, and are compatible with different versions of operating systems. 
+ Verification of device resources, e.g.: lack of installation capacity, and possible collisions with other installed applications. 
+ Verification of GUI on various screen resolutions and sizes.
+ Verification of the responsiveness of the application.
+ Verification of landscape and portrait orientation.

## ✔️<a name="task4_04">Subtask 4</a>

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/swipeto.jpg)


### 🔗 [SwipeTo - Bug Reports - Jira](https://testowanie-225.atlassian.net/jira/software/projects/CPP/boards/4)

### 📄 Bug Report Template in Jira

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-1_TEMPLATE.png)

### 🐞 Bug Reports in Jira

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-2.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-3.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-4.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-5.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-6.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-7.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-8.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-9.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-10.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-11.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-12.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-13.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-14.png)

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%204/CPP-15.png)

<hr>

# 💻 TASK 5 💻

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/sql.png)

## ✔️<a name="task5_01">Subtask 1</a>

### 🧠 SQL Statements I Have Learned:

```sql
-- SELECT query:
SELECT (DISTINCT) column_1, column_2 AS alias_name, ...
FROM table_name;

-- WHERE clause - filtering data:
SELECT column_1, column_2, ...
FROM table_name
WHERE column_1 =/!=/<>/>/>=/</<= value |
WHERE condition_1 AND condition_2 |
WHERE condition_1 OR condition_2 |
WHERE columnn_1 (NOT) LIKE pattern |
WHERE column_1 (NOT) IN (value_1, value_2, ...) |
WHERE column_1 (NOT) BETWEEN value_1 AND value_2 |
WHERE column_1 IS (NOT) NULL;

-- Ordering data with the ORDER BY clause:
SELECT column_1, column_2, ...
FROM table_name
ORDER BY column_1 ASC|DESC;

-- Grouping and aggregating data with the GROUP BY and HAVING clauses:
SELECT column_1, MIN(column_2) |
MAX(column_2) |
COUNT(column_2) |
AVG(column_2) |
SUM(column_2)
FROM table_name
GROUP BY column_1
HAVING condition;

-- Transforming string data with string functions:
SELECT LOWER(column_1), UPPER(column_1), INITCAP(colimn_1), LENGTH(column_1)
FROM table_name;

-- Mathematical functions:
SELECT CEIL(column_1), FLOOR(column_1), ROUND(column_1, n), TRUNC(column_1, n)
FROM table_name;

-- INSERT INTO - adding data to a table:
INSERT INTO table_name (column_1, column_2, column_3, ...)
VALUES (value_1, value_2, value_3, ...);

-- UPDATE - modifying data in a table:
UPDATE table_name
SET column_1 = value_1, column_2 = value_2, ...
WHERE condition;

-- DELETE - removing data from a table:
DELETE FROM table_name 
WHERE condition;

-- Joining tables with the JOIN clauses:
SELECT table_1.column_1, table_2.column_2
FROM table1
(INNER/LEFT/RIGHT/FULL OUTER) JOIN table_2
ON table_1.column = table_2.column;

-- Combining data from multiple tables with UNION:
SELECT column_name(s) FROM table_1
UNION (ALL)
SELECT column_name(s) FROM table_2;

-- Subqueries in the WHERE/FROM/SELECT clauses:
SELECT column_1, column_2
FROM table_1
WHERE column_1 operator (SELECT column_1 FROM table_2 WHERE condition);

SELECT column_1, column_2
FROM (SELECT column_1, column_2 FROM table_1 WHERE condition) AS temp_table;

SELECT column_1, (SELECT AVG(column_2) FROM table_2 WHERE condition)
FROM table_1;
```

## ✔️<a name="task5_02">Subtask 2</a>

### 📚 Environment Configuration and Database Import

![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/kurs_sql.png)

## ✔️<a name="task5_03">Subtask 3</a>

### Zapytania SQL:

🩸 1. Wyświetl tabelę 'actors' w kolejności alfabetycznej, sortując po kolumnie surname.

```sql
SELECT * 
FROM actors
ORDER BY surname ASC;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/1.png)

🩸 2. Wyświetl film, który powstał w 2019 roku.

```sql
SELECT * 
FROM movies 
WHERE year_of_production = 2019;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/2.png)

🩸 3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

```sql
SELECT * 
FROM movies 
WHERE year_of_production BETWEEN 1900 AND 1999;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/3.png)

🩸 4. Wyświetl jedynie tytuł i cenę filmów, które kosztują poniżej 7$.

```sql
SELECT title,
       price 
FROM movies 
WHERE price < 7;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/4.png)

🩸 5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.

```sql
SELECT * 
FROM actors 
WHERE actor_id >= 4 AND actor_id <= 7;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/5.png)

🩸 6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego operator logiczny.

```sql
SELECT * 
FROM customers 
WHERE customer_id = 2 OR customer_id = 4 OR customer_id = 6;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/6.png)

🩸 7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

```sql
SELECT * 
FROM customers 
WHERE customer_id IN (1,3,5);
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/7.png)

🩸 8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

```sql
SELECT * 
FROM actors
WHERE name LIKE 'An%';
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/8.png)

🩸 9. Wyświetl dane klienta, który nie ma podanego adresu email.

```sql
SELECT * 
FROM customers
WHERE email IS NULL;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/9.png)

🩸 10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich movie_id mieści się pomiędzy 2 i 8.

```sql
SELECT * 
FROM movies
WHERE price > 9 AND movie_id BETWEEN 2 AND 8;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/10.png)


# 💻 TASK 6 💻

![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)

## ✔️<a name="task6_01">Subtask 1</a>

🩸 11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈

```sql
UPDATE customers
SET surname = 'Miler'
WHERE name = 'Ania' and surname = 'Muler';
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/11.png)

🩸 12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z JOIN sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.

```sql
SELECT c.name, c.surname, c.email
FROM customers c 
JOIN sale s ON c.customer_id = s.customer_id
WHERE s.movie_id = 4;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/12.png)

🩸 13. Na pewno zauważyłaś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com.

```sql
UPDATE customers
SET email = 'pati@mail.com'
WHERE name = 'Patrycja';
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/13.png)

🩸 14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join).

```sql
SELECT c.name, c.surname, m.title, s.sale_date
FROM customers c 
JOIN sale s ON c.customer_id = s.customer_id
JOIN movies m ON s.movie_id = m.movie_id;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/14.png)

🩸 15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag

```sql
ALTER TABLE customers
ADD pseudonym CHAR(3) NOT NULL;

UPDATE customers 
SET pseudonym = CONCAT(LEFT(name,2), RIGHT(surname,1));
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/15.png)

🩸 16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.

```sql
SELECT title 
FROM movies
WHERE movie_id IN 
	(SELECT DISTINCT movie_id
         FROM sale);
```

Lub

```sql
SELECT DISTINCT m.title 
FROM movies m 
JOIN sale s ON m.movie_id = s.movie_id;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/16.png)

🩸 17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie (wykorzystaj do tego funkcję UNION).

```sql
SELECT name FROM actors
UNION 
SELECT name FROM customers
ORDER BY name ASC;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/17.png)

🩸 18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5$.

```sql
UPDATE movies
SET price = price + 2.5
WHERE year_of_production > 2000;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/18.png)

🩸 19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał.

```sql
SELECT a.name, a.surname, m.title
FROM actors a 
JOIN cast c ON a.actor_id = c.actor_id
JOIN movies m ON c.movie_id = m.movie_id
WHERE a.actor_id = 4;
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/19.png)

🩸 20. A gdzie nasza HONIA!? Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name = Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa.

```sql
INSERT INTO customers
(customer_id, name, surname, email, pseudonym)
VALUES (7, 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa')
```
![](https://github.com/milgit-007/challenge_portfolio_milena/blob/main/Task%205/20.png)

## ✔️<a name="task6_02">Subtask 2</a>

### ISTQB - Test - ⚪ ECRU -14/15

## ✔️<a name="task6_03">Subtask 3</a>

### [🔗 Portfolio](https://github.com/milgit-007/MilenaKurzatkowska-Portfolio) 































































