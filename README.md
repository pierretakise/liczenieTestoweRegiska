# Karma dla kota — wydanie testowe (BETA)

Kalkulator dziennej porcji karmy mokrej dla kota, w wersji testowej.
Jednoplikowa aplikacja webowa (PWA) — bez backendu, bez instalacji, bez śledzenia.

To wydanie służy do sprawdzania nowych funkcji. Wersja używana na co dzień
stoi pod osobnym adresem i nie zmienia się razem z tym repozytorium.

## Co jest nowego w tym wydaniu

- **Karta „Teraz"** — na górze, jedną dużą liczbą, ile podać do następnej miski.
  Gdy cały dzień idzie jeden smak z jednego słoika, porcja jest stała przez cały
  dzień i karta o nic nie pyta.
- **Otwarty słoik** — w zakładce Spiżarnia można zapisać, jaki słoik jest napoczęty
  i ile w nim zostało; Kalkulator wstawia tę resztkę jednym kliknięciem.
- **Wspólny licznik posiłków** — ile posiłków już podano, widoczne dla wszystkich
  domowników korzystających z tego samego kodu gospodarstwa. Zeruje się po północy.
- **Rząd misek** — plan dnia jako kafelki: podane wyszarzone, następna podświetlona.

## Jak uruchomić

Otwórz adres w przeglądarce. Na telefonie: „Udostępnij → Dodaj do ekranu
początkowego" — aplikacja zachowa się wtedy jak zwykła apka i zadziała offline.

## Dane

Stan spiżarni trzymany jest w pamięci przeglądarki. Współdzielenie między
domownikami jest opcjonalne i włącza się przez wpisanie wspólnego kodu
gospodarstwa w zakładce Spiżarnia — bez kodu aplikacja działa wyłącznie lokalnie.
Aplikacja nie zbiera żadnych danych osobowych i nie zawiera skryptów śledzących.

## Uwaga dla testujących

To wydanie ma własną, oddzielną pamięć w przeglądarce i własną pamięć podręczną,
więc nie miesza się ze stanem wersji codziennej — nawet jeśli obie są otwarte
na tym samym urządzeniu.
