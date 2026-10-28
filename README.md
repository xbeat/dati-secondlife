# Dati aperti di secondlife.it

Dati per chi pensa di trasferirsi in un comune italiano, gli stessi che usa [secondlife.it](https://secondlife.it).
Aggiornati periodicamente; la versione più recente è sempre anche su [secondlife.it/dati-aperti](https://secondlife.it/dati-aperti).

## File

### `prezzi_case_comuni.csv`
Prezzi delle case in oltre 7.600 comuni, dalle quotazioni dell'Osservatorio del Mercato Immobiliare (OMI)
dell'Agenzia delle Entrate.

| Colonna | Significato |
|---|---|
| istat | codice ISTAT del comune |
| comune, sigla, provincia, regione | nome del comune, sigla e nome della provincia, regione |
| periodo | semestre delle quotazioni OMI |
| acquisto_medio_eur_m2 | media dei valori centrali delle zone OMI del comune, euro al metro quadro |
| acquisto_min_eur_m2, acquisto_max_eur_m2 | valore minimo e massimo tra le zone del comune |
| affitto_medio_eur_m2_mese | come sopra, per l'affitto, euro al metro quadro al mese |

Citazione: "secondlife.it su dati Agenzia delle Entrate - OMI".

### `programmi_trasferimento.csv` / `.json`
I programmi di comuni e regioni per chi si trasferisce: case a 1 euro, bonus di residenza, contributi per affitto e
acquisto. Ogni voce ha la fonte ufficiale (`url`, `source_urls`), lo stato (`open`, `recurring`, `closed`,
`unknown`) e la data dell'ultima verifica (`checked`). Gli elenchi che circolano sono spesso vecchi: lo stato e la
data dicono quanto fidarsi di ciascuna voce.

Citazione: "secondlife.it".

## Licenza

[Creative Commons Attribuzione 4.0 Internazionale](https://creativecommons.org/licenses/by/4.0/deed.it): uso libero,
anche commerciale, citando la fonte. Le quotazioni OMI sono dell'Agenzia delle Entrate, licenza CC BY 4.0.

## Contatti

Errori o programmi da aggiungere: info@secondlife.it, oppure [secondlife.it/pubblica](https://secondlife.it/pubblica).
Per chi cerca bandi per imprese: [occasioni.it](https://occasioni.it).
