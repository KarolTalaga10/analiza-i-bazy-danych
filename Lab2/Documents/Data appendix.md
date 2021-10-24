### Opis przetworzonych danych
Przetworzony zbiór danych (dostępny w folderze Analysis Data) zawiera następujące kolumny:
- iso2: kod kraju
- year: rok
- cases: liczba przypadków zachorowania na gruźlicę
- sex: płeć
- age: przedział wiekowy
### Generacja wykresów
Aby wygenerować wykres należy uruchomić skrypt Figures.ipynb i wpisać żądany kraj. Dostępne są dwa rodzaje wykresów (lepiej widocznie przy włączonym jasnym motywie):
- wykres punktowy obrazujący sumę przypadków w danym kraju na przestrzeni czasu
<div style="text-align:center"><img src="Wykresy/cases_country_plot.png" /></div>
- wykres słupkowy obrazujący liczbę przypadków w danym przedziale wiekowym
<div style="text-align:center"><img src="Wykresy/cases_age_country_hist.png" /></div>
