### Perspektywa Użytkownika (Wynajmującego)

- Rejestracja: Użytkownik musi mieć możliwość założenia konta wynajmującego, co wymaga obowiązkowego podpięcia karty
  płatniczej w celu autoryzacji przyszłych płatności.

- Wyszukiwanie: System umożliwia podgląd na mapie tylko tych hulajnóg, które są sprawne technicznie, nie są
  aktualnie wynajęte ani zarezerwowane przez kogoś innego, a ich poziom naładowania przekracza 20%.

- Rezerwacja: Użytkownik może zarezerwować wybraną hulajnogę na czas X minut; w tym czasie pojazd staje się
  niewidoczny
  dla innych osób i jest zablokowany przed wynajmem przez osoby trzecie.

- Rozpoczęcie wynajmu: Wynajem można rozpocząć na podstawie aktywnej rezerwacji lub bezpośrednio "z ulicy", pod
  warunkiem,
  że system pomyślnie zablokuje środki (depozyt) na karcie użytkownika.

- Uruchomienie pojazdu: Po pomyślnej autoryzacji płatności, system zdalnie odblokowuje i uruchamia hulajnogę.

- Zakończenie wynajmu: Użytkownik kończy wynajem poprzez aplikację, co jest możliwe tylko w wyznaczonych strefach
  zwrotu;
  system wyłącza wtedy pojazd i sprawdza jego stan.

- Zgłaszanie usterek: Podczas zwrotu użytkownik ma możliwość oznaczenia hulajnogi jako uszkodzonej, co automatycznie
  zmienia jej status w systemie.

- Rozliczenie: Po zakończeniu najmu system nalicza opłatę na podstawie czasu trwania, rozlicza ją z zablokowanego
  depozytu (zwracając nadpłatę) i wystawia fakturę lub rachunek.

- Awaryjne zakończenie: W przypadku całkowitego rozładowania baterii lub wykrycia krytycznego uszkodzenia w trakcie
  jazdy,
  system automatycznie unieruchamia hulajnogę, kończy wynajem i inicjuje proces płatności.

### Perspektywa Ładowacza (Juicera)

- Rejestracja ładowacza: Osoba chcąca zarabiać na ładowaniu musi założyć dedykowane konto, podpiąć kartę (jako
  zabezpieczenie) oraz podać numer rachunku bankowego do wypłat.

- Widoczność ofert: Ładowacz widzi hulajnogi wymagające ładowania (bateria < 80%), przy czym pojazdy o stanie 20-80% są
  widoczne tylko w godzinach nocnych (20:00–04:00), a te poniżej 20% – przez całą dobę.

- Rezerwacja do ładowania: Ładowacz może zarezerwować hulajnogę do ładowania, co blokuje ją dla użytkowników oraz innych
  ładowaczy na określony czas.

- Limit pracy: Jeden ładowacz może mieć w posiadaniu (zarezerwowane lub pobrane) maksymalnie 10 hulajnóg jednocześnie.

- Logistyka zwrotu: Naładowana hulajnogę (> 80%) należy oddać w wyznaczonym punkcie (hubie), co skutkuje naliczeniem
  wynagrodzenia dla ładowacza.

- System kar: System nalicza kary finansowe, jeżeli ładowacz odda hulajnogę rozładowaną, przekroczy czas zwrotu lub
  zostawi pojazd poza wyznaczoną strefą.

### Perspektywa Technika

- Autoryzacja: Konta techników są tworzone wyłącznie przez administratorów systemu na podstawie podpisanych umów o
  pracę/współpracę.

- Zarządzanie zleceniami: Technik posiada dostęp do listy zleceń serwisowych, obejmujących naprawy, transport pojazdów
  między strefami oraz interwencyjne ładowanie.

- Serwisowanie: Technik może zarezerwować i pobrać dowolną hulajnogę do serwisu na podstawie wygenerowanego zlecenia; po
  zakończeniu prac oznacza pojazd jako sprawny, przywracając go do puli ogólnodostępnej.

### Perspektywa Systemu (Automatyzacja)

- Workflow uszkodzeń: Jeżeli jakikolwiek użytkownik zgłosi uszkodzenie, system musi automatycznie wygenerować zlecenie
  serwisowe dla technika.
- Optymalizacja floty: System samodzielnie generuje zlecenia przewozu, jeśli w danej strefie znajduje się zbyt duża lub
  zbyt mała liczba hulajnóg.