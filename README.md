# UML - Software analysis and modeling college project

## Sterownik alarmu przeciwwłamaniowego

#### Aktorzy:
  * komponenty:
    * czujniki (w drzwiach i oknach, bezprzewodowe)
    * wykrywacze ruchu (w domu i poza domem, bezprzewodowe)
    * kamery (w domu i poza domem, bezprzewodowe)
  * głośnik (centralny głośnik/syrena, może być połączony z większą ilością głośników)
  * dialer GSM (komunikacja z ochroną, policją, właścicielem)
  * panel kontrolny (klawiatura i wyświetlacz)

#### Analiza wymagań:
  * rejestracja / usunięcie czujnika
  * rejestracja / usunięcie wykrywacza ruchu
  * rejestracja / usunięcie kamery
  * sprawdzenie stanu czujników/kamer/wykrywaczy ruchu
  * zmiana adresu powiadomień (dla dialeru GSM)
  * sprawdzenie aktualnego adresu powiadomień
  ---

  * komunikat w przypadku otwarcia obudowy
  * komunikat w przypadku straty łączności z którymś z modułów
  * komunikat w przypadku straty zasilania
  * komuniakt w przypadku błędnych prób uwierzytelnienia
  ---

  * zmiana kodu
  * zmiana specjalnego, przymusowego kodu
  * uzbrojenie alarmu (po określonym czasie)
  * rozbrojenie alarmu (po użyciu kodu)
  * rozbrojenie alarmu z powiadomieniem ochrony (po użyciu kodu przymusowego)
  * zmiana długości czasu oczekiwania na rozbrojenie alarmu
  ---

  * aktywowanie alarmu (oczekiwanie na rozbrojenie alarmu)
  * uruchomienie alarmu (głośnik wyje, ochrona zostaje zawiadomiona itd.)
  * nagrywanie włamania
