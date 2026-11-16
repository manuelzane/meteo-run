<p><img src="icon-192.png" width="96" height="96" alt="Meteo Run"></p>

# Meteo Run

Web app (PWA) che confronta le previsioni di **Yr**, **Aeronautica Militare** e **Windy (modello ECMWF)** per la posizione GPS attuale e suggerisce come vestirsi per correre all'ora scelta.

Interfaccia nello stile del design system **IBM Carbon** (font IBM Plex Sans, icone `@carbon/icons`, Apache-2.0).

## Fonti dati
- Yr / MET Norway — `api.met.no` (CC BY 4.0)
- Servizio Meteorologico dell'Aeronautica Militare — `api.meteoam.it` (probabilità di pioggia, non mm)
- ECMWF HRES via Open-Meteo — `api.open-meteo.com` (stesso modello predefinito su Windy; l'API ufficiale di Windy è a pagamento)

## Pubblicazione
Sito statico: basta servire la cartella. Su GitHub Pages: *Settings → Pages → Deploy from a branch → `master` / root*.

Sull'iPhone: apri il sito in Safari → Condividi → **Aggiungi alla schermata Home**.
