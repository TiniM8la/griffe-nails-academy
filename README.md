# Griffe Nails Academy — Landing Page

Landing page realizzata per **Griffe Nails Academy (GNA)**, progetto di formazione professionale nails con sede a Brescia.

Il sito nasce nell'ambito di un **progetto universitario di Digital Marketing** con l'obiettivo di progettare e testare un sistema digitale capace di rendere più chiara l'offerta formativa, generare contatti qualificati e accompagnare gli utenti verso la richiesta di informazioni e l'iscrizione.

## Obiettivo del progetto

Il progetto interviene principalmente nella fase compresa tra interesse e contatto.

Il percorso digitale progettato è:

**Instagram → Landing Page → Test di orientamento → WhatsApp → Valutazione personalizzata → Iscrizione**

La landing non sostituisce il rapporto diretto con l'educator, ma permette all'utente di arrivare al contatto con maggiori informazioni sul metodo e sulla formazione.

## Funzionalità principali

La landing comprende:

- presentazione di Griffe Nails Academy;
- descrizione del Metodo Griffe;
- segmentazione dell'offerta in base al punto di partenza dell'utente;
- informazioni sulla formazione;
- gallery fotografica;
- test di orientamento interattivo;
- generazione di un riepilogo personalizzato da inviare tramite WhatsApp;
- FAQ;
- contatto diretto tramite WhatsApp;
- collegamenti Instagram e Google Maps;
- Privacy Policy e Cookie Policy.

## Test di orientamento

Il test permette all'utente di indicare:

- esperienza professionale;
- contesto lavorativo;
- servizi e materiali utilizzati;
- punti di forza;
- principali difficoltà tecniche;
- obiettivi formativi;
- preferenza tra formazione individuale e piccolo gruppo.

Al termine viene generato un riepilogo delle risposte che l'utente può scegliere di inviare tramite WhatsApp per richiedere una valutazione personalizzata del proprio percorso.

## Analytics e misurazione

Il progetto integra:

- **Google Tag Manager**
- **Google Analytics 4**
- **Looker Studio**

Sono stati predisposti eventi personalizzati per analizzare le principali interazioni della landing:

- `test_start`
- `test_complete`
- `whatsapp_direct`
- `whatsapp_test`

I parametri UTM consentono inoltre di analizzare la provenienza del traffico e distinguere diversi touchpoint delle attività di comunicazione digitale.

La dashboard in Looker Studio è organizzata nelle aree:

**Overview · Acquisition · Conversion · Performance**

## Tecnologie

Il progetto è sviluppato come sito statico utilizzando:

- HTML5
- CSS3
- JavaScript
- Google Tag Manager
- Google Analytics 4

Il sito è responsive e progettato per una fruizione sia desktop sia mobile.

## Design

L'identità visiva riprende il posizionamento di Griffe Nails Academy attraverso uno stile essenziale, femminile e professionale.

## Struttura del progetto

```text
/
├── index.html
├── style.css
├── privacy.html
├── cookie.html
├── assets/
└── README.md
