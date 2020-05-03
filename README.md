## Dokumentacja projektu BAI


### Temat projektu
Stworzenie serwisu do symulacji gry na giełdzie kryptowalut.

### Cele projektu
Głównym celem projektu jest zasymulowanie gry na giełdzie kryptowalut oraz sprawdzenie czy podczas gry na giełdzie można się wzbogacić czy więcej stracić.

### Funkcjonalności
Na sersie można znaleźć następujące postrony:
* Strona główna
* Kursy walut
* Zarządzanie portfelem

Na każdym widoku pojawia się menu u góry strony, na którym znajdują się podstrony oraz biężące saldo.

1. Wyświetlanie bieżących danych o kryptowalutach.

Na Stronie Głównej serwisu jest umieszczona lista czterech głównych kryptowalut ze szczegółami ściągniętymi z API (nazwa, BID, ASK) oraz posiadaną ilość kryptowaluty (liczone w sztukach). Oprócz tego widodczne są funkcje (kup, sprzedaj, szczegóły, usuń).
![Strona Główna](screens/StronaGłówna1.png)

Szczegóły dotyczące danej kryptowaluty można zobaczyć po kliknięciu przycisku *Szczegóły*. Są tam wyświetlane dane z ostatnich kilku godzin w formie wykresów (kupno i sprzedaż)
![Szczegóły Kryptowaluty](screens/SzczegolyKrypto.png)

2. Wyświetlanie bieżących kursów walut.

Na podstronie *Kursy Walut* jest umieszczona lista najpopularniejszych walut sciągnietych z API (waluta, kod, kupno, sprzedaż)
![Strona Główna](screens/KursyWalut.png)

3. Dodawanie dedykowanych kryptowalut do listy śledzonych pozycji.

Na *Stronie Głównej* jest dostępna funkcja do dodania nowych kryptowalut do bieżącej wyświetlanej listy. Po wyborze kryptowaluty i kliknięciu przycisku *Dodaj* nowy wiersz pojawia się w tabeli kryptowalut.
![Dodaj Kryptowaluty](screens/DodaneKryptowaluty.png)

4. Wirtualny portfel z możliwością przewalutowania na inną walutę po aktualnym kursie nbp.

Na podstronie *Zarządzanie Portfelem* jest dostępna opcja do przewalutowania obecnej waluty. Po kliknięciu przycisku *Kup/Sprzedaj* pojawia się okno z 3 walutami pobranymi z API (waluta, kod, cena kupna, cena sprzedaży). Po wybraniu waluty należy wprowadzić ilość i wybrać opcję kup/sprzedaj, a następnie kliknąć przysisk wymień, aby waluta obecna waluta (w złotówkach) została wymieniona na inną walutę.
![Wymiana Walut](screens/WymianaWalut.png)

5. Zakupy i sprzedaż kryptowalut wykorzstując wirtualny portfel.

![Kup Kryptowalutę](screens/KupKrypto1.png)
![Widok kupionej kryptowaluty](screens/KupKrypto2.png)
![Sprzedaj Kryptowalutę](screens/SprzedajKrypto1.png)
![Widok sprzedanej kryptowaluty](screens/SprzedajKrypto2.png)

6. Zasilenia portfela.
![Zasil Portfel](screens/ZasilPortfel.png)

7. Przywrócenie stanu początkowego portfela
![Zarządzanie Portfelem](screens/ZarządzaniePortfelem.png)

### Linki do składowych projektu
[Projekt](https://monikasajbura.github.io/BAI_projekt/)

[Dane o cenach kryptowalut](https://bitbay.net/pl/api-publiczne)

[Kursy walut](http://api.nbp.pl/)
