# Opis projektu

### Temat Projektu
Rozpoznawanie cyfr pisanych odręcznie za pomocą sztucznej sieci neuronowej z wykorzystaniem frameworka Keras.

### Cel Projektu
Cel projektu i oczekiwane rezultaty

Celem projektu jest stworzenie prostego systemu rozpoznającego cyfry odręczne (0–9) na podstawie danych z zestawu MNIST. Oczekiwanym rezultatem jest wytrenowanie modelu osiągającego dokładność powyżej 90% oraz możliwość jego wykorzystania do predykcji na nowych obrazach.

### Opis funkcjonalności

- Wczytywanie i przetwarzanie danych z MNIST.
- Budowa, trening i ewaluacja sieci neuronowej.
- Predykcja cyfr na obrazach testowych.
- Wizualizacja wyników.
- Test jednostkowy poprawności działania modelu.
- Modułowy podział kodu.

### Jak uruchomić skrypt?
W terminalu (np. CMD, PowerShell, Terminal w VSCode) zainstaluj potrzebne biblioteki:
```
pip install keras numpy matplotlib
```

### Uruchomienie
Sklonuj repozytorium:
```commandline
git clone https://github.com/krystiandsw/Projekt-Programistyczny-2.git
cd Projekt-Programistyczny-2
```

Przejdź do folderu, w którym masz pliki i uruchom main.py:

```commandline
python main.py
```
Uruchom testy:
```commandline
python test_model.py
```

### Użyte technologie
- Keras
- NumPy
- Matplotlib
- Unittest (do testów jednostkowych)