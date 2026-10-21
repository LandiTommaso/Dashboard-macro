# Prezzi, redditi e finanza pubblica in Italia

Progetto di analisi economica descrittiva, con dashboard interattiva.

**Dashboard:** https://landitommaso.github.io/prezzi-redditi-finanza-pubblica/

## Domande di ricerca

1. L'aumento dei prezzi del 2026 ha caratteristiche simili a quello del 2022?
2. Come si sono evoluti produttività, salari reali e reddito disponibile dal 2000, e come si collocano rispetto agli altri grandi paesi dell'area dell'euro?
3. Quali vincoli pongono la composizione della spesa, la spesa per interessi e i saldi di bilancio alle politiche di sostegno ai redditi?

## Struttura

1. Dinamica dei prezzi al consumo, 2019-2026
2. Prezzi dell'energia e ruolo delle accise
3. Costi di produzione e prezzi agricoli
4. Struttura del settore agricolo e politica agricola comune
5. Occupazione, ore lavorate e produttività
6. Salari reali e reddito disponibile
7. Composizione della spesa pubblica
8. Spesa per la difesa: definizioni a confronto
9. Saldi di bilancio, spesa per interessi e manovra 2027
10. Sintesi dei risultati e limiti

## File

| File | Contenuto | Unità |
|---|---|---|
| `index.html` | Dashboard completa, in un unico file con dati inclusi | |
| `data/prezzi_ipca_tendenziali.csv` | IPCA Italia per componente, mensile, 2019-2026 | variazione % tendenziale |
| `data/pil_ore_occupati_trimestrali.csv` | PIL reale, ore lavorate, occupati e rapporti, 2014-2026 | indice 2015=100 |
| `data/produttivita_salari_redditi_annuali.csv` | Produttività oraria (IT, DE, FR, ES, EA20), salari reali, reddito disponibile, 2000-2025 | indice 2000=100 |
| `data/spesa_pubblica_cofog_pct_pil.csv` | Spesa delle amministrazioni pubbliche per funzione COFOG, 1995-2024 | % del PIL |

## Dati e metodo

Analisi descrittiva di serie storiche ufficiali, estratte il 21 ottobre 2026. Le variazioni dei prezzi sono tendenziali (mese sullo stesso mese dell'anno precedente); i valori reali sono deflazionati con il deflatore dei consumi delle famiglie o con l'IPCA, come indicato in ciascun grafico.

Fonti principali: Eurostat (prc_hicp_minr, namq_10_gdp, namq_10_a10_e, nama_10_lp_ulc, nama_10_gdp, prc_hicp_aind, nasa_10_nf_tr, nama_10_pe, tec00113, gov_10a_exp, gov_10a_main, nama_10_a10, nama_10_a10_e, ef_m_farmleg); Istat; Banca d'Italia; MEF; Documento programmatico di bilancio 2027; Osservatorio sui conti pubblici italiani; Baldoni e Ciaian (Joint Research Centre, 2021). Le fonti di ogni grafico sono indicate nella dashboard.

## Limiti

L'analisi è descrittiva e non identifica effetti causali. Alcuni dati di settore (Ismea) sono ripresi da fonti secondarie e i dati 2025-2026 sono in parte provvisori. I dettagli sono nella sezione 10 della dashboard.

## Autore

Tommaso Landi
