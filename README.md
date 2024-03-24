# uwm-ML

Typowy potok uczenia maszynowego
  1. Określenie problemu do rozwiązania.
  2. Zgromadzenie danych.
  -  Zdefiniowanie odpowiedniej przestrzeni.
  -  Dokumentacja danych.
  -  Anonimizacja.
3. Podział danych (1.podzial_na_zbior_test_tren.ipynb)
  -  Wydzielenie rozłącznych podzbiorów: treningowy oraz testowy.
  -  Proporcje dostosowane do rozmiaru pełnego zbioru danych.
  -  Wszelkie dalsze kroki dokonywane tylko na podzbiorze treningowym.
4. Przetwarzanie i oczyszczanie danych (2.czyszczenie_danych_numerycznych.ipynb, 3.czyszczenie_atrybutow_nienumerycznych.ipynb, 4.potoki.ipynb, 5.redukcja_wymiarowisci_danych.ipynb)
  -  Uzupełnianie brakujących wartości.
  -  Kodowanie numeryczne wartości tekstowych.
  -  Redukcja asymptot.
  -  Skalowanie, standaryzacja i normalizacja wartości.
  -  Redukcja wymiarowości.
5. Trening modelu.
  -  Dopasowanie architektury modelu.
  -  Optymalizacja hiperparametrów.
  -  Analiza miar.
6. Uformowanie finalnego potoku.
