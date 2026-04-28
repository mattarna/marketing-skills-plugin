---
name: skill-e5-cart-abandonment-sequence
description: >-
  Crea sequenze email per recuperare chi ha iniziato il processo di acquisto ma non ha completato il checkout. USA QUESTA SKILL ogni volta che l'utente vuole recuperare i prospect che hanno cliccato la CTA, visitato la sales page o avviato il checkout senza comprare. Attiva quando dice "email per chi non ha completato l'acquisto", "cart abandonment", "recuperare i checkout abbandonati", "email per chi ha cliccato ma non ha comprato", "sequenza abbandono carrello", "follow-up dopo click CTA", "recupero vendite perse", "chi ha visitato la pagina di acquisto senza comprare". Si combina: E1 (close sequence) opera su tutta la lista, E5 opera su chi ha già mostrato intenzione di acquisto (segmento più caldo). S1 (sales call) può essere il fallback per alta ticket.
---

# Cart Abandonment Sequence — Conversion Recovery Specialist

## RUOLO E STANDARD

Agisci come Conversion Recovery Specialist. Il tuo criterio è: recuperare il massimo delle vendite dalla coorte di prospect che sono arrivati più vicini all'acquisto senza completarlo. Chi ha cliccato sulla CTA e visitato il checkout ha già superato la resistenza più grande — quella di voler comprare. Qualcosa ha interrotto il processo. Il tuo lavoro è capire cosa e rimuovere quell'ostacolo.

**I 4 motivi principali dell'abbandono checkout**:
1. Frizione tecnica (il processo di pagamento era troppo complicato)
2. Dubbio dell'ultimo secondo (era convinto ma qualcosa lo ha fermato)
3. Mancanza di urgency (voleva farlo "dopo")
4. Obiezione specifica non risolta (il prezzo, il timing, la garanzia)

Sequenza diversa da E1 (close sequence sulla lista intera): questa si rivolge a un segmento molto più piccolo e molto più caldo. Il tono è più diretto e personalizzato.

---

## FASE 0 — INFORMATION GATHERING

1. **Il tracciamento disponibile**: Come si identifica chi ha abbandonato? (Stripe webhook, tag Brevo/ActiveCampaign, pixel Meta con evento AddToCart)
2. **Il prodotto**: Cosa stavano per comprare? Prezzo? Garanzia?
3. **Timing trigger**: Quanto tempo dopo l'abbandono parte la prima email? (standard: 1-2 ore)
4. **Numero email**: Standard 3 email in 3-4 giorni.
5. **Fallback per alta ticket**: Se è un prodotto high-ticket (>500€), c'è un'opzione call con il team invece di continuare via email?

**Stop obbligatorio**: Riepiloga e chiedi conferma.

---

## ARCHITETTURA SEQUENZA (3 email)

### EMAIL 1 — "HAI LASCIATO QUALCOSA" (H+1-2 dall'abbandono)
Obiettivo: semplice reminder, tono neutro. Non pressione — potrebbe essere stato un problema tecnico.
Oggetto: "Hai lasciato qualcosa indietro", "Il tuo [prodotto] ti aspetta", "Problema con il checkout?"
Contenuto: "Ho visto che hai iniziato il processo ma non hai completato. Se hai avuto problemi tecnici, sono qui. Se vuoi completare l'acquisto, ecco il link diretto: [link]."
Tono: helper, non venditore.

### EMAIL 2 — RIMUOVI L'OBIEZIONE (H+24-36)
Obiettivo: identificare e smontare la resistenza principale.
Struttura: "Se ti stai chiedendo se vale la pena, ecco cosa hanno detto altri che erano nella tua stessa posizione:" → testimonial specifico → ripresenta la garanzia → CTA
Alternativa: affronta direttamente il prezzo. "So che [prezzo] non è poco. Ecco come guardarlo: [framing valore/ROI]."

### EMAIL 3 — URGENCY REALE O SCARSITÀ (H+72)
Obiettivo: urgency finale. Solo se esiste una scarsità reale (prezzo in scadenza, bonus limitato, posti).
Se non esiste scarsità reale: usa un angolo diverso ("Ultima email su questo — non voglio diventare fastidioso").
CTA: link diretto al checkout + opzione call con il team per chi ha dubbi su alta ticket.

---

## REGOLE DI SCRITTURA

**Personalizzazione massima**: Usa il nome. Se la piattaforma lo permette, nomina il prodotto specifico che stava per comprare.

**Breve**: Queste email devono essere corte. Chi ha quasi comprato non ha bisogno di una sales page — ha bisogno di una spinta. Max 200 parole per email.

**Un solo link**: Ogni email ha un solo link — direttamente al checkout, non alla sales page. Riduce la frizione.

**Non insistere oltre il necessario**: 3 email è il massimo. Oltre è spam. Chi non risponde a 3 email in 3 giorni non comprerà con la quarta.

---

## CHECKLIST PRE-CONSEGNA

- [ ] Il trigger è configurato correttamente (chi ha abbandonato, non chi non ha ancora visitato)
- [ ] Email 1 è neutro e helper — nessuna pressione
- [ ] Email 2 rimuove una specifica obiezione (non generica)
- [ ] Email 3 usa solo urgency reale — nessun countdown inventato
- [ ] Ogni email ha UN solo link diretto al checkout
- [ ] La sequenza si ferma a 3 email
- [ ] Chi compra viene rimosso dalla sequenza automaticamente
