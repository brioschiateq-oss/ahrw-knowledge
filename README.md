# AHRW Knowledge Base tecnica

Una **knowledge base pubblica e anonimizzata** per l'Assistente AHRW, creata dalla community. Contiene grammatica della sintassi verificata, formule, esempi di interpretazione, limitazioni osservate e soluzioni testate in produzione.

## 📖 Contenuti

- **Governance e metodo**: Regole di contribuzione, badge di stato (VERIFICATA, OSSERVATA, DA VERIFICARE, NON FUNZIONANTE)
- **Grammatica di Site Painter**: Sintassi documentata, campi, filtri, condizioni e Hide
- **Funzioni disponibili**: Condizioni, testo, numeri, date e formattazione
- **Query e variabili**: Campi delle query principali (gsve_qrep_doc_offerte, ambdoc_q), User Variables e Report Variables
- **Soluzioni verificate**: Formule testate con interpretazione, casi di prova e risultati
- **Special Definitions**: Behavior osservato su Calculations e Reset
- **DMS e Scheda Prodotto**: Classi documentali, relazioni, attributi, HTML e limitazioni
- **Funzioni vietate**: Approcci non verificati da evitare
- **Fonti esterne**: Link a documentazione ufficiale Zucchetti
- **Aggiornamenti controllati**: Procedura per proporre e approvare nuovi contenuti

## 🔗 Accedi alla Knowledge Base

**Web (consigliato):** https://brioschiateq-oss.github.io/ahrw-knowledge/

## 🛠️ Stack Tecnologico

- **HTML5** con semantica strutturata
- **CSS3** responsive e optimizzato
- **Schema.org JSON-LD** per rich snippets
- **Open Graph** per social sharing
- **Sitemap XML** e robots.txt per SEO
- **Bing Webmaster** verification

## 📋 Regole di Contribuzione

### Governance

**Contenuto pubblico**: NON pubblicare
- Nomi reali di clienti
- Matricole reali
- Prezzi
- Credenziali o token
- Indirizzi interni
- Screenshot non anonimizzati
- Dati commerciali sensibili

### Stati delle formule

| Badge | Significato |
|-------|-----------|
| 🟢 **VERIFICATA** | Provata in AHRW e funzionante |
| 🔵 **OSSERVATA** | Visibile, comportamento non completamente compreso |
| 🟡 **DA VERIFICARE** | Coerente con la grammatica, ancora da provare |
| 🔴 **NON FUNZIONANTE** | Prova eseguita con errore o risultato diverso |

### Regola di inferenza controllata

Una nuova espressione è ammissibile solo se:
- Usa funzioni già osservate
- Usa campi documentati o mostrati dall'utente
- Usa strutture sintattiche verificate
- Rimane **DA VERIFICARE** fino a prova concreta

### Metodologia di test

1. Mostrare il valore grezzo
2. Verificare la condizione separatamente
3. Provare il calcolo senza Hide
4. Applicare Hide solo dopo
5. Provare con e senza il dato speciale

## 🔍 Ricerca e Indicizzazione

- ✅ Repository **pubblico**
- ✅ GitHub Pages **abilitato**
- ✅ Bing Webmaster **verificato**
- ✅ Sitemap XML pubblicato
- ✅ robots.txt configurato
- ✅ Schema.org JSON-LD incluso
- ✅ Open Graph metadata

**Scopribile su:** Bing, Google, e tutti i motori di ricerca principali

## 📞 Supporto e Feedback

Per segnalazioni, correzioni o suggerimenti:
- Apri una **Issue** su GitHub
- Consulta la sezione "Aggiornamenti controllati"
- Rispetta la procedura di approvazione

## ⚠️ Disclaimer

- Questa knowledge base **integra, non sostituisce** la documentazione ufficiale Zucchetti
- Le soluzioni sono **verificate nel singolo ambiente** — potrebbero variare in base a versione, configurazione e contesto
- In caso di conflitto: 1) soluzione verificata nell'ambiente → 2) documentazione ufficiale → 3) deduzione da verificare

## 📄 Licenza

Contenuti pubblici e anonimizzati. Consulta il repository GitHub per dettagli.

## 🔗 Fonti Ufficiali

- [Zucchetti Tools: Expression Builder](https://www.zucchettitools.com/build60/help/portalstudio/00001200.htm)
- [Zucchetti Tools: funzioni SQL](https://www.zucchettitools.com/build60/help/portalstudio/00001195.htm)
- [Zucchetti Help: DMS Archivio](https://help.zucchetti.it/dms/ticpro/help/sam/ahrw_standard/gsdm/gsdm_archivio_index.html)

---

**Ultimo aggiornamento:** 15 settembre 2026  
**Repository:** https://github.com/brioschiateq-oss/ahrw-knowledge  
**Maintainer:** brioschiateq-oss