# UszW-kurier-grid

Projekt z przedmiotu **Uczenie się ze wzmocnieniem** (WEiI PRz, 2026/2027).

**Autor:** Jakub Fuhrman (179482)  
**Temat:** Agent-kurier na gridzie z energią i zamykającymi się przejściami

## Opis

Agent-kurier porusza się po mapie siatkowej, zbiera paczki i dostarcza je do bazy.
Ma ograniczoną energię; po zebraniu określonej liczby paczek część przejść na mapie się zamyka.
Planowany algorytm: **Q-learning** (ewentualnie porównanie z SARSA) + baseline (losowy / zachłanny).

## Struktura repozytorium

```text
UszW-kurier-grid/
|-- src/               # kod środowiska i agentów (w przygotowaniu)
|-- experiments/       # skrypty eksperymentów (w przygotowaniu)
|-- report/            # raport LaTeX
|-- results/           # wyniki eksperymentów
|-- ai_transcripts/    # dokumentacja wsparcia AI
|-- requirements.txt
`-- README.md
```

## Raport

Wstępnie uzupełnione rozdziały 1–3 znajdują się w katalogu `report/`.
Kompilacja lokalna lub przez Overleaf (plik główny: `report/szablon_raportu.tex`).

## Status

Etap E1: wybór tematu, repozytorium, wstępna formalizacja RL/MDP.
