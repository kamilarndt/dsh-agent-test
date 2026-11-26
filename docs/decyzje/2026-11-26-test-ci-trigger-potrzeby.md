# Potrzeby: testowy trigger CI (repo dsh-agent-test)

Po co ten workflow: repo służy jako poligon dsh-superagent bez drugiego
konta GitHub. Triggerem ticketa jest zmiana stanu CI (`observeCi`),
nie Issue (filtr own-author wycina wpisy Kamila).

Decyzje:
- D1: `test.yml` zaczyna na zielono (baseline), potem celowe czerwone
  sprawdza trigger.
- D2: po teście workflow do usunięcia.

Zgoda właściciela:
Cytat właściciela: „zrob to bez konta” · data odpowiedzi: 2026-11-26 · właściciel: kamil
decyzje objęte: D1, D2
