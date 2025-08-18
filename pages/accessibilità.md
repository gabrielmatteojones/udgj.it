---
layout: page
title: Accessibilità
date: 2025-08-18T19:43:00.000+02:00
permalink: /accessibilita/
categories: "[legal]"
---
**Report di Accessibilità del Sito Web**

**Sito Web in Esame**: \UDGJ

**Data di Analisi**: \18 luglio 2025

---

### 1. Introduzione

L'accessibilità web è un aspetto fondamentale per garantire che tutte le persone, inclusi coloro che hanno disabilità, possano utilizzare e navigare facilmente un sito web. Questo report fornisce una valutazione dell'accessibilità del sito web sopra menzionato, basata sulle **WCAG 2.1**, che definiscono le linee guida per rendere i contenuti web più accessibili.

---

### 2. Metodologia

Per la valutazione dell'accessibilità, sono stati utilizzati i seguenti strumenti e tecniche:

* **Valutazione manuale**: Esame diretto del sito per determinare la conformità alle WCAG 2.1.
* **Strumenti automatizzati**: Utilizzo di strumenti come **Google Lighthouse**, **WAVE** e **axe** per eseguire una scansione iniziale e identificare problemi evidenti.
* **Test utente**: Considerazione delle problematiche sollevate da utenti con disabilità (a seconda della disponibilità).

---

### 3. Risultati

#### 3.1 Conformità alle WCAG 2.1

| **Principio WCAG**  | **Soddisfatto (✓)** | **Non Soddisfatto (✗)** | **Commenti**                                                                                                        |
| ------------------- | ------------------- | ----------------------- | ------------------------------------------------------------------------------------------------------------------- |
| **Percezione**      | ✓                   |                         | Le immagini sono correttamente etichettate con testi alternativi, ma alcune immagini decorative non hanno alt-text. |
| **Operabilità**     | ✓                   |                         | La navigazione tramite tastiera è possibile, ma mancano alcune scorciatoie.                                         |
| **Comprensibilità** | ✓                   |                         | Il contenuto è chiaro, ma alcuni link hanno testi non descrittivi (ad esempio, "clicca qui").                       |
| **Robustezza**      | ✓                   |                         | Il sito è compatibile con i principali lettori di schermo e dispositivi assistivi.                                  |

#### 3.2 Punti Critici

* **Testi alternativi incompleti**: Alcune immagini decorative non sono dotate di alt-text, il che può causare difficoltà per gli utenti di lettori di schermo.
* **Contrasto insufficiente**: Alcuni testi e sfondi non rispettano il rapporto di contrasto minimo di 4.5:1, rendendo difficile la lettura per persone con scarsa vista.
* **Link non descrittivi**: Alcuni link come "clicca qui" non sono descrittivi, il che può creare confusione per gli utenti di tecnologie assistive.

#### 3.3 Punti di Forza

* **Navigazione da tastiera**: La navigazione da tastiera è generalmente supportata, con una corretta gestione del focus e dei tasti di navigazione.
* **Struttura chiara**: Il sito è strutturato in modo gerarchico, con intestazioni ben definite che facilitano la navigazione.
* **Compatibilità con lettori di schermo**: Non sono stati riscontrati problemi evidenti nell'interazione con lettori di schermo come JAWS e NVDA.

---

### 4. Raccomandazioni

1. **Aggiungere testi alternativi alle immagini decorative**: Le immagini puramente decorative dovrebbero avere un `alt` vuoto (`alt=""`) per evitare confusione ai lettori di schermo.
2. **Migliorare il contrasto dei testi**: Assicurarsi che tutti i testi abbiano un contrasto di almeno 4.5:1 rispetto allo sfondo, per garantire la leggibilità.
3. **Rendere i link più descrittivi**: Evitare l'uso di testi generici come "clicca qui". I link dovrebbero descrivere l'azione o il contenuto a cui portano (es. "Scopri di più sui nostri servizi").
4. **Testare su dispositivi mobili**: Verificare che il sito sia completamente accessibile anche su dispositivi mobili, inclusi gli schermi più piccoli e l'uso di funzioni di zoom.

---

### 5. Conclusioni

Il sito web in esame mostra una buona conformità alle linee guida di accessibilità, ma ci sono alcune aree che necessitano di miglioramenti. Implementare le raccomandazioni suggerite migliorerà l'esperienza di accessibilità per tutti gli utenti, inclusi quelli con disabilità.

---

**Firma**:
\Gabriel Matteo Jones
Gestore sito Web
\gabriel.jones@18f.it
