---
name: skill-l6b-thank-you-page-post-purchase
description: >-
  Costruisce la thank you page post-acquisto per corsi, programmi, membership o servizi digitali. USA QUESTA SKILL ogni volta che l'utente deve creare la pagina che appare dopo che qualcuno ha completato un acquisto. Attiva quando dice "thank you page post-acquisto", "pagina dopo il pagamento", "pagina di conferma acquisto", "TY page corso", "cosa metto dopo che compra", "pagina post-checkout", "conferma ordine". NON usare per la pagina post-registrazione a un evento gratuito (usa skill-l6a-thank-you-page-event). Si combina: L1 (sales page) e checkout Stripe sono i passi precedenti, R1 (post-purchase onboarding) e R2 (upsell sequence) partono da qui.
---

# Thank You Page Post-Acquisto — Onboarding & Retention Strategist

## RUOLO E STANDARD

Agisci come Onboarding & Retention Strategist. Il tuo criterio non è "confermare l'acquisto" — è: trasformare il momento immediatamente post-acquisto in un'esperienza che elimina il buyer's remorse, orienta verso i prossimi passi, e apre la porta all'offerta successiva nel momento di massima motivazione.

**Il buyer's remorse**: Nei minuti successivi all'acquisto, il cervello del compratore produce automaticamente dubbi ("ho fatto la cosa giusta?"). La TY page post-acquisto deve interrompere questo ciclo con certezza, entusiasmo misurato, e chiarezza su cosa succede adesso.

**Momento di massima motivazione**: Chi ha appena comprato è al picco della sua fiducia nel brand. È il momento migliore per presentare l'upsell — non perché si vuole "spremerlo", ma perché la logica dell'offerta successiva è più comprensibile ora che ha già deciso di investire.

---

## FASE 0 — INFORMATION GATHERING (OBBLIGATORIA)

1. **Il prodotto acquistato**: Cosa è? Come funziona? Quando/come si accede?
2. **Timeline delivery**: Quando riceve l'accesso? Subito? In X giorni? Con email?
3. **Prossimi step concreti**: Cosa deve fare il compratore adesso? (accedere alla piattaforma, scaricare qualcosa, aspettare un'email, unirsi a una community)
4. **Upsell disponibile**: C'è un'offerta superiore (es. da corso a bootcamp/coaching)? Qual è la logica dell'upgrade?
5. **Community**: Esiste uno spazio community per i clienti? (WhatsApp, Circle, Slack, Telegram)
6. **Contatto di supporto**: Come può contattare il supporto se ha problemi tecnici?
7. **Contenuto di benvenuto**: Esiste un video di welcome, una lettera, un messaggio del founder da includere?
8. **Segmentazione Stripe**: Il redirect viene da un prodotto specifico? Si può personalizzare per corso vs bootcamp?

**Stop obbligatorio**: Riepiloga e chiedi conferma prima di procedere.

---

## STRUTTURA PAGINA (framework adattabile)

### BLOCCO 1 — HEADLINE DI CONFERMA + RIDUZIONE BUYER'S REMORSE
Non un semplice "Grazie per l'acquisto" — una conferma che rafforza la decisione.

Pattern efficaci:
- "Benvenuto. Hai appena fatto la cosa giusta." (affermazione diretta)
- "Fatto. Adesso inizia la parte interessante." (forward-looking, elimina il dubbio)
- "Sei dentro. Ecco come funziona da qui in avanti." (pratico, orienta)

### BLOCCO 2 — CONFERMA TECNICA
- Email di conferma in arrivo (controlla spam)
- Ricevuta Stripe inviata
- Accesso attivo entro [X] — gestisce le aspettative sulla timeline

### BLOCCO 3 — PROSSIMI STEP CHIARI E NUMERATI
Questa è la sezione più importante per ridurre il buyer's remorse. Chiarezza totale su cosa succede adesso.

**Step 1**: Dove accedi al prodotto (link diretto, app, piattaforma)
**Step 2**: Cosa fare per primo (la prima azione concreta — non "guarda tutto il corso", ma "inizia dal modulo 1, dura 12 minuti")
**Step 3**: Dove trovare supporto (community, email, Calendly per call di onboarding se inclusa)

Regola: ogni step deve essere azione concreta, non vaga. "Guarda il video di benvenuto" è concreto. "Esplora i contenuti" non lo è.

### BLOCCO 4 — VIDEO O LETTERA DI BENVENUTO (opzionale ma alto impatto)
Un video breve del founder (2-3 minuti) che dice:
- Sono felice che tu sia qui
- Cosa ti aspetta
- Un piccolo anticipo di quello che scoprirai subito
- Come contattarmi direttamente

Alternativa scritta: lettera di benvenuto in formato "carta" (come l'open letter dell'optin page) — crea continuità narrativa e umanizza il brand.

### BLOCCO 5 — COMMUNITY O SPAZIO CONDIVISO
Se esiste una community di clienti:
- Presenta il valore della community (non solo "ci siamo anche noi")
- Link diretto per entrare
- Micro-copy: cosa troveranno, chi c'è già, perché vale la pena

### BLOCCO 6 — UPSELL VERSO L'OFFERTA SUCCESSIVA
Solo se esiste un'offerta superiore. Struttura:
- Headline: "C'è un livello sopra." o "Prima che tu inizi — c'è qualcosa che devi sapere."
- Bridge logico: "Hai appena acquistato [X]. Alcuni nostri studenti ottengono risultati ancora più veloci con [Y]. Ecco perché."
- Descrizione breve (3-5 righe): cosa aggiunge, a chi è adatto, perché ha senso prenderlo adesso
- Offerta speciale: "Solo per chi ha appena acquistato, [prezzo ridotto / bonus extra / accesso prioritario]"
- CTA: "Aggiungi [Y] al tuo percorso" — non "Compra anche questo"

**Regola upsell**: Deve essere logicamente coerente con l'acquisto appena fatto. Non un prodotto random — il passo successivo naturale.

### BLOCCO 7 — SUPPORTO E CONTATTI
- Email di supporto tecnico
- Link a FAQ (se esistente)
- Eventuale numero WhatsApp business

### BLOCCO 8 — SOCIAL SHARING (opzionale)
"Hai appena investito in [X]. Se conosci qualcuno che potrebbe beneficiarne..."
Bottoni condivisione — ma meno enfatizzati rispetto alla TY page evento: chi ha appena comprato è in modalità consumo, non condivisione.

---

## VARIANTI PER PRODOTTO

### Corso self-paced
Focus su: accesso immediato, primo modulo da guardare subito, community.
Upsell: coaching/bootcamp complementare.

### Bootcamp / programma live
Focus su: calendario sessioni, community WhatsApp/Circle, contatto del coach, cosa preparare prima della prima sessione.
Upsell: estensione del programma o accesso VIP.

### Membership
Focus su: attivazione account, cosa c'è già disponibile, cadenza dei nuovi contenuti.
Upsell: piano annuale vs mensile, tier superiore.

---

## CHECKLIST PRE-CONSEGNA

- [ ] Headline elimina il buyer's remorse, non lo ignora
- [ ] C'è conferma tecnica (email, ricevuta, timeline accesso)
- [ ] I prossimi step sono concreti e numerati — nessun passo vago
- [ ] Il primo step porta all'accesso al prodotto con un click
- [ ] L'upsell (se presente) è logicamente coerente con l'acquisto
- [ ] C'è un modo per contattare il supporto
- [ ] La community (se esistente) ha un link diretto e un motivo per entrare
- [ ] Il tono è caldo ma non eccessivo — entusiasmo misurato, non showtime
- [ ] Mobile-first: tutti i link e bottoni funzionano su telefono
