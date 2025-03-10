# Projekt Wykrywania Wieku 🎉

## 📑 Spis treści
- [📋 Opis projektu](#opis-projektu)
- [📂 Struktura projektu](#struktura-projektu)
- [📦 Wymagania](#wymagania)
- [⚙️ Instalacja](#instalacja)
- [📊 Przygotowanie danych](#przygotowanie-danych)
- [🧠 Trenowanie modelu](#trenowanie-modelu)
- [📈 Ocena modelu](#ocena-modelu)
- [🔍 Wykonanie predykcji](#wykonanie-predykcji)
- [📉 Wizualizacja wyników](#wizualizacja-wyników)
- [👥 Autor](#autor)

## 📋 Opis projektu
Projekt "Wykrywanie Wieku" ma na celu stworzenie modelu sieci neuronowej do przewidywania wieku osób na podstawie ich zdjęć twarzy. Model jest trenowany, walidowany i testowany na zbiorze danych UTKFace, który zawiera obrazy twarzy z etykietami wieku, płci i rasy.

## 📂 Struktura projektu
```
age-detection/
│
├── data/                   # Katalog do przechowywania obrazów zbioru danych
├── new_data/               # Katalog do przechowywania nowych obrazów do predykcji
├── README.md               # Dokumentacja projektu
├── requirements.txt        # Wymagania Pythona
└── notebook.ipynb          # Główny notatnik Jupyter dla projektu
```

## 📦 Wymagania
- Python 3.7+
- TensorFlow 2.0+
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## ⚙️ Instalacja
Sklonuj repozytorium:
```sh
git clone https://github.com/LiCHUTKO/age-detection.git
cd age-detection
```

Zainstaluj wymagane zależności:
```sh
pip install -r requirements.txt
```

## 📊 Przygotowanie danych
Dane są wczytywane z katalogu `data` i przetwarzane w notatniku `notebook.ipynb`. Zawierają obrazy twarzy z etykietami wieku, płci i rasy.

## 🧠 Trenowanie modelu
Otwórz plik `notebook.ipynb` w Jupyter Notebook lub Jupyter Lab. Wykonaj wszystkie komórki w notatniku, aby załadować dane, przygotować je, zbudować model, przeprowadzić trening i ocenić model.

## 📈 Ocena modelu
Model jest oceniany na zbiorze testowym za pomocą różnych metryk, takich jak strata i średni błąd bezwzględny (MAE).

## 🔍 Wykonanie predykcji
Model może wykonywać predykcje na nowych danych obrazowych. Umieść nowe obrazy w katalogu `new_data` i uruchom odpowiednie komórki w notatniku `notebook.ipynb`.

## 📉 Wizualizacja wyników
Wyniki treningu i oceny modelu są wizualizowane za pomocą wykresów.

## 👥 Autor
[LiCHUTKO](https://github.com/LiCHUTKO)