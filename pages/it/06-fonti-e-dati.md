# 6. Fonti e dati

Tutti i dati citati in questo documento hanno una fonte istituzionale o
terza autorevole, linkata qui sotto.

## Fonti ufficiali italiane

- **Agenzia delle Entrate** — Aliquote IRPEF e regime forfettario
  https://www.agenziaentrate.gov.it/portale/web/guest/imposte/regime-forfettario
- **INPS** — Gestione Separata, aliquote per autonomi
  https://www.inps.it/it/it/inps-comunica/dati-e-bilanci/gestioni-e-bilanci/gestione-separata.html
- **MEF** — Relazione sull'economia non osservata e sull'evasione
  fiscale e contributiva (serie storica tax gap)
  https://www.mef.gov.it/focus/Relazione-sull-economia-non-osservata-e-sull-evasione-fiscale-e-contributiva
- **Corte dei Conti** — Referto sul regime forfettario (24 giugno 2026)
  https://www.corteconti.it/

## Fonti ufficiali UE

- **Commissione Europea** — Country Report Italia 2026 (3 giugno 2026)
  https://economy-finance.ec.europa.eu/publications_en
- **EU VAT Directive** — soglie di esenzione piccole imprese
  https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32006L0112

## Coefficienti di redditività per codice ATECO (2026)

Il reddito forfettizzato si calcola applicando al fatturato un coefficiente
diverso a seconda del settore ATECO. Più alto è il coefficiente, più
reddito imponibile si genera a parità di fatturato.

| Gruppo ATECO | Descrizione | Coefficiente |
|---|---|---|
| 10-11 | Industrie alimentari e bevande | 40% |
| 45; 46.2-46.9; 47.1-47.9 | Commercio ingrosso e dettaglio | 40% |
| 47.81 | Commercio ambulante alimentari/bevande | 40% |
| 47.82; 47.89 | Commercio ambulante tessuti/altri prodotti | 54% |
| 41-43; 68 | Costruzioni, immobiliare, intermediari immobiliari | 86% |
| 46.1 | Intermediari del commercio (agenti, mediatori) | 62% |
| 55-56 | Servizi alloggio e ristorazione | 40% |
| 64-66; 69-75; 85; 86-88 | Libero professionista | **78%** |
| ALTRO | Altre attività (residuale) | 67% |

> *Nota: il coefficiente 78% (libero professionista) è quello usato negli
> esempi di calcolo del presente documento.*

## Aliquote previdenziali 2026 per categoria

| Tipologia soggetto | Gestione | Aliquota 2026 | Minimale |
|---|---|---|---|
| Professionista senza cassa | Gestione Separata INPS | 26,07% | Nessuno |
| Professionista con cassa | Cassa di appartenenza (INARCASSA, ENPAM, ecc.) | 10%–19,5% variabile | Dipende dalla Cassa |
| Artigiano | INPS Artigiani | 24,00% | Sì — fisso + eccedenti |
| Commerciante | INPS Commercianti | 24,48% | Sì — fisso + eccedenti |
| Agente/mediatore | ENASARCO / INPS Commercianti | ~8,5% / 24,48% | Dipende dal profilo |

**Parametri di base 2026**:
- Reddito minimale annuo (base contributo fisso): **€18.808,00**
- Contributo fisso annuo artigiani (sul minimale): **€4.521,36**

> *Nota: il professionista "tipico" che citiamo negli esempi (consulenza,
> ATECO 70-74) ha aliquota 26,07% senza minimale fisso, ma subisce la
> totalità dell'imposta sul reddito forfettizzato (78% × fatturato).*

## Confronto soglie IVA altri paesi UE

| Paese | Soglia esenzione IVA | Riferimento normativo |
|---|---|---|
| Italia | €85.000 | Art. 1 co. 54-89 L. 190/2014 |
| Francia | €100.000 (micro) | Art. 293 B CGI |
| Germania | €100.000 (Kleinunternehmer) | §19 UStG |
| Austria | €700.000 (Kleinunternehmer) | §6 Abs. 1 Z 27 UStG |
| Spagna | Regime simplificado variabile | L. 37/1992 art. 122-134 |

## Fonti terze autorevoli

- **Wikipedia — IRPEF (in inglese: Income tax in Italy)**
  https://en.wikipedia.org/wiki/Income_tax#Italy
- **Wikipedia — Taxation in Italy**
  https://en.wikipedia.org/wiki/Taxation_in_Italy
- **Il Sole 24 Ore — Norme e Tributi**
  https://ntplusdiritto.ilsole24ore.com/

## Dati citati nel documento — verifica

| Affermazione | Fonte | Ultimo controllo |
|---|---|---|
| Aliquota sostitutiva forfettario 15% | L. 190/2014, art. 1 co. 64 | 2024 |
| Aliquota ridotta 5% primi 5 anni | L. 190/2014, art. 1 co. 65 | 2024 |
| Soglia di fatturato €85.000 | L. 190/2014, art. 1 co. 54 | 2024 |
| INPS Gestione Separata 26,07% (2026) | Circolare INPS annuale / tabella parametri 2026 | 2026 |
| INPS Artigiani 24,00% (2026) | Tabella aliquote previdenziali 2026 | 2026 |
| INPS Commercianti 24,48% (2026) | Tabella aliquote previdenziali 2026 | 2026 |
| Reddito minimale annuo €18.808,00 (2026) | INPS — minimale contributivo 2026 | 2026 |
| Contributo fisso artigiani €4.521,36 (2026) | INPS — minimale contributivo 2026 | 2026 |
| Coefficiente ATECO 78% (libero professionista) | DM coefficienti redditività | 2026 |
| IRPEF scaglioni 23/35/43% | D.Lgs. 509/2024 in attuazione L. 111/2023 | 2024 |
| Tax gap autonomi 59,8% | MEF Relazione evasione 2024 (dato 2022) | 2024 |
| Costo forfettario €3,4 mld/anno | Corte dei Conti, 24 giugno 2026 | 2026 |
| Country Report UE su Italia | Commissione UE, 3 giugno 2026 | 2026 |

## Come segnalare errori o dati da aggiornare

Apri una Issue con tag `dati` o una Pull Request seguendo le regole in
[CONTRIBUTING.md](../CONTRIBUTING.md).
