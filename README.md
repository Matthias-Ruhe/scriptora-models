# Scriptora – Sprachmodelle

Spracherkennungs-Modelle für **Scriptora – Teleprompter** (Windows und Android).

Die App lädt sie bei Bedarf einmalig aus dem Release [`models-v1`](../../releases/tag/models-v1), danach läuft die Erkennung offline.

| Sprache | Modell |
|---|---|
| Deutsch | vosk-model-small-de-0.15 |
| Englisch | vosk-model-small-en-us-0.15 |
| Französisch | vosk-model-small-fr-0.22 |
| Spanisch | vosk-model-small-es-0.42 |
| Italienisch | vosk-model-small-it-0.22 |
| Niederländisch | vosk-model-small-nl-0.22 |

## Herkunft und Lizenz

Die Modelle stammen unverändert vom [Vosk-Projekt](https://alphacephei.com/vosk/models) (Alpha Cephei) und stehen unter der **Apache License 2.0** (siehe `LICENSE`).

## Neue Modelle

In `models.txt` den Tag erhöhen (`models-v2`) und Modelle eintragen. Der Workflow legt das neue Release an; bestehende Releases werden nie verändert, damit ältere App-Versionen weiter funktionieren.
