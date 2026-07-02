# szachy-P0-SERC
# P0/SERC – Projekt Silnika SERC

## Opis

Projekt P0/SERC to framework do analizy dynamiki relacyjnej układów złożonych, oparty na geometrii 4-wymiarowego sympleksu i metryce Grama.

## Struktura

- `docs/` – dokumentacja matematyczna i protokoły
- `src/` – kod źródłowy (Recorder, Analyzer)
- `experiments/` – eksperymenty i wyniki
- `data/` – przykładowe dane

## Szybki start

```bash
# Instalacja zależności
pip install numpy pandas scipy matplotlib

# Uruchomienie Recordera (interaktywny)
python src/recorder/serc_recorder_v2.2.py

# Analiza pliku JSONL
python src/analyzer/serc_multiscale_analyzer.py data/sample/serc_batch_sample.jsonl