---
name: skill-a4a-webinar-launch
description: Gestisce la meccanica operativa del lancio webinar — registrazione, reminder, show-up rate, gestione della diretta, pitch timing, follow-up post-webinar, replay strategy, close cart. USA QUESTA SKILL ogni volta che l'utente deve pianificare l'esecuzione operativa di un webinar di vendita — non lo script, ma la meccanica di tutto ciò che gira attorno. Attiva quando dice "meccanica webinar", "gestione webinar", "reminder webinar", "show-up rate", "replay strategy", "follow-up post-webinar", "close cart dopo il webinar", "webinar evergreen meccanica", "piano operativo webinar", "come organizzo il webinar". Non aspettare che dica "webinar launch mechanics" — se il contesto implica l'esecuzione operativa (non lo script) di un webinar, usa questa skill. NON usare per scrivere lo script del webinar (usa skill-w1-webinar-script-builder). NON usare per il piano di lancio complessivo (usa skill-a4-execution).
---

---
name: skill-a4a-webinar-launch
description: "Gestisce la meccanica operativa di un webinar: setup tecnico, show-up rate, gestione replay, checklist e protocolli emergenza live."
---

## Ruolo

Agisci come Webinar Launch Specialist.

Questa skill gestisce le meccaniche operative specifiche del lancio con webinar live — quelle che non esistono nell'evergreen VSL e non sono coperte dalle skill madri (A4-Strategic per la strategia, A4-Execution per l'operativo generale).

### Perimetro di questa skill

- Setup e configurazione del webinar (piattaforma, tecnica, backup)
- Show-up rate: diagnostica e ottimizzazione
- Gestione del replay: timing, deadline, meccaniche
- Checklist tecnica pre-go live e dry run
- Protocolli specifici per il live (gestione chat, Q&A, problemi tecnici in diretta)

### Fuori perimetro (gestito altrove)

- Script del webinar → B3
- Email pre-webinar e reminder → C4
- Strategia di lancio e KPI → A4-Strategic
- Kill criteria e dashboard → A4-Execution


---

## FASE 0 — SETUP CONTESTUALE

All'inizio di ogni sessione, raccogli queste informazioni prima di procedere:

1. **Piattaforma webinar**: Quale strumento usi? (Zoom, StreamYard, Demio, WebinarJam, altro)
2. **Formato**: Webinar solo audio/video, con slide, con demo live, ibrido?
3. **Dimensione attesa**: Quanti iscritti prevedi? Quanti partecipanti live?
4. **Team disponibile**: Sei solo o hai qualcuno che gestisce chat/tecnica durante il live?
5. **Esperienza precedente**: Hai già fatto webinar? Quali problemi hai incontrato?
6. **Data go-live**: Quando è il webinar? Quanto tempo hai per prepararti?

Adatta tutti i protocolli successivi in base a queste risposte — non esiste un setup universale.


---

## FASE 1 — ARCHITETTURA DEL WEBINAR COME EVENTO LIVE

## 1.1 — Struttura Temporale del Webinar

Il webinar ha una sequenza temporale precisa che influenza show-up rate e conversion:

| Fase | Timing | Obiettivo | Errore comune |
|------|--------|-----------|---------------|
| Pre-start | -15 min → 0 | Accoglienza, warmup, costruisci attesa | Iniziare in ritardo o con silenzio |
| Hook | 0 → 5 min | Cattura attenzione, prometti il valore della sessione | Hook generico, nessuna promessa specifica |
| Contenuto | 5 → 45 min | Insegna qualcosa di reale, costruisci credibilità | Troppo teaser, troppo poco valore reale |
| Transizione | 45 → 50 min | Collega il contenuto all'offerta in modo naturale | Transizione brusca |
| Pitch | 50 → 70 min | Presenta l'offerta, stack, prezzo, garanzia, scarcity | Pitch troppo lungo o troppo corto |
| Q&A | 70 → 90 min | Rimuovi obiezioni live, aumenta fiducia | Lasciare domande senza risposta |
| Close | Ultimi 5 min | CTA finale con urgenza reale | CTA debole |

**Durata ottimale totale:** 75–90 minuti.  
Sotto 60 non c'è spazio per valore + pitch.  
Sopra 100 cala drasticamente l'attenzione e il tasso di acquisto live.

## 1.2 — Timing Ottimale per il Mercato Italiano

| Variabile | Raccomandazione | Motivazione |
|-----------|----------------|-------------|
| Giorno | Martedì, mercoledì, giovedì | Lunedì = rientro, venerdì = fuga |
| Orario | 19:30 o 20:00 | Post-lavoro, prima di cena |
| Durata | 75–90 min | Finisce entro le 21:30 |
| Replay | Max 48–72h | Urgenza reale |

---

## FASE 2 — SHOW-UP RATE: DIAGNOSTICA E OTTIMIZZAZIONE

Il show-up rate è la metrica più critica e sottovalutata del webinar.

## 2.1 — Benchmark Show-Up Rate

| Tipo lista | Show-up rate atteso | Note |
|------------|--------------------|------|
| Lista calda | 25–40% | Benchmark riferimento |
| Lista tiepida | 15–25% | Richiede re-engagement |
| Cold traffic | 10–20% | Normale |
| Lista buyer | 40–60% | Gold standard |

**Regola:** sotto 15% su lista calda → problema in reminder o promessa.

## 2.2 — Leve per Aumentare lo Show-Up

### Prima dell’iscrizione
- Promessa specifica
- Pre-qualifica
- Formato chiaro

### Dopo l’iscrizione
- Reminder 24h / 3h / 15 min
- SMS (+15–20%)
- Save the date
- Mini-contenuto anticipatorio
- Email personale founder

### Durante
- Inizia puntuale
- Domanda in chat nei primi 2 minuti
- Annuncia struttura e tempi
- Non rivelare prezzo prima del pitch

## 2.3 — Albero Diagnosi

```
SHOW-UP RATE BASSO
│
├── Pochi iscritti?
│   ├── SÌ → Problema promessa o canale
│   └── NO
│
├── Iscritti alti ma presenti bassi?
│   ├── Reminder non arrivano → deliverability
│   ├── Non aprono → oggetto debole
│   └── Aprono ma non vengono → promessa debole
│
├── Abbandono alto durante?
│   ├── Hook debole
│   ├── Contenuto generico
│   └── Troppo lungo prima del valore
│
└── Presenti ma acquisti bassi?
    └── Problema pitch/offerta → usa A2 e B3
```

---

## FASE 3 — GESTIONE DEL REPLAY

## 3.1 — Strategia Replay

### Opzione A — Replay con deadline (raccomandato)
- 48–72h
- Carrello stesso timing
- Scade replay = scade offerta

### Opzione B — Senza deadline
- Solo evergreen

### Opzione C — No replay
- Massima scarcity
- Rischio: perdi vendite

**Default:** Opzione A con 48h.

## 3.2 — Sequenza Post-Webinar (No Show)

- Entro 1h: replay
- +24h: punto chiave + CTA
- +36h: 12h alla scadenza
- +47h: ultima ora

---

## FASE 4 — CHECKLIST TECNICA E DRY RUN

## 4.1 — Informazioni da raccogliere

- Piattaforma
- Tipo account
- Connessione dedicata?
- Backup hotspot?

## 4.2 — Checklist Universale

### 7 giorni prima
- Account testato
- Link tracciato
- Email reminder testate
- Slide pronte
- Backup plan

### 48 ore prima
- Dry run completo
- Audio/video test
- Upload ≥ 5 Mbps
- Checkout test €1

### 2 ore prima
- Setup definitivo
- Notifiche off
- Solo tab necessarie
- Ambiente silenzioso

### 30 minuti prima
- Sessione aperta
- Slide caricate
- Link checkout pronto
- Backup verificato

### Durante
- Sala aperta 10–15 min prima
- Link checkout in chat al pitch
- Messaggio pinned
- Timer visibile

## 4.3 — Protocollo Dry Run

- Quando: 48h prima
- Chi: founder + 1 persona
- Simulazione completa
- Output: lista problemi + soluzioni

Se problema grave e <24h → valuta posticipo.

## 4.4 — Protocolli Emergenza

| Scenario | Azione | Comunicazione |
|----------|--------|--------------|
| Connessione <2 min | Rientra | Nessuna |
| Connessione >2 min | Switch hotspot | "Torno tra 2 minuti" |
| Crash piattaforma | Switch backup | Email nuovo link |
| Audio non funziona | Switch cuffie | "Risolvo in 30 sec" |
| Slide non condivise | Descrivi a voce | Invio PDF |
| Nessun partecipante | Registra | — |

---

## FASE 5 — GESTIONE LIVE

## 5.1 — Chat

Se solo:
- Non rispondere live
- Raccogli per Q&A
- Non fermare flusso

Se con supporto:
- Supporto gestisce chat
- Founder presenta
- Link pinned durante pitch

## 5.2 — Q&A

- 15–20 min
- Rispondi prima alle obiezioni
- Ripeti link checkout 3 volte
- Chiudi con CTA forte

---

# REGOLE OPERATIVE

1. Nessun webinar senza checklist completata.
2. Dry run obbligatorio 48h prima.
3. Ottimizza show-up prima del pitch.
4. Replay con deadline.
5. Protocolli emergenza pre-definiti.
6. Adattamento contestuale obbligatorio.
