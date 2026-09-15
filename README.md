# Nacomi — propozycje układu podstron sklepu

Koncepcja UX/UI dwóch kluczowych podstron sklepu [nacomi.pl](https://nacomi.pl):
**listy kategorii** i **karty produktu**. Każda strona ma przełącznik
**Przed / Po** — po lewej mapa problemów obecnej wersji, po prawej propozycja
wraz z uzasadnieniem każdej decyzji.

https://fabianadrianw.github.io/nacomi_strony/

---

## Czym to jest, a czym nie jest

To **materiał roboczy przygotowany z własnej inicjatywy**, nie zlecenie i nie
oficjalny projekt marki. Nacomi nie brało udziału w jego powstaniu; nazwa,
logo, zdjęcia i teksty produktowe należą do Nacomi i użyte są wyłącznie
poglądowo.

Kolory, typografia i oprawa graficzna są celowo robocze. **Przedmiotem
propozycji jest układ i logika prowadzenia klienta** — co gdzie stoi, w jakiej
kolejności i dlaczego — a nie gotowy layout wizualny.

## Co jest w środku

| Plik | Zawartość |
|---|---|
| `index.html` | Hub — punkt wejścia z opisem metody i linkami do obu podstron |
| `kategoria.html` | Lista produktów: hierarchia wizualna, filtrowanie po realnej potrzebie klienta (problem skóry, SPF, linia) zamiast po atrybutach katalogowych, redukcja obciążenia poznawczego |
| `produkt.html` | Karta produktu: jedna spójna ścieżka wzroku od zdjęcia do decyzji zakupowej, przebudowana kolejność sekcji, sekcja składu i dopasowania do typu cery |

## Metoda

Każda propozycja zaczyna się od **nazwanego problemu w obecnej wersji**, nie od
pomysłu na wygląd. W widoku „Przed" każdy problem jest opisany osobno — co
konkretnie nie działa i jaki ma to skutek dla klienta. Widok „Po" pokazuje
odpowiedź na dokładnie te punkty. Osobno zdiagnozowane jest zachowanie na
telefonie.

Nic tu nie jest zmienione dlatego, że „tak ładniej".

## Stack

Statyczny HTML/CSS/JS bez zależności i bez procesu budowania. Otwierasz plik
w przeglądarce i działa — bez logowania, bez instalacji.

---

Adrian Wojtasik · [eyelingo.app](https://eyelingo.app)
