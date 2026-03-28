# M365 Security Assessment Tool

Strumento interattivo per la valutazione della sicurezza dei tenant Microsoft 365, basato sui 25 controlli critici del **CIS Microsoft 365 Foundations Benchmark v6.0.1**.

## Funzionalità

- **25 controlli** organizzati in 5 aree: Identità, Email, App esterne, Dati, Logging
- **Sistema a semaforo** (verde/giallo/rosso) per ogni controllo
- **Calcolo automatico** del livello di rischio complessivo e per area
- **Note personalizzate** per ogni controllo
- **Report a 4 pagine** pronto per la stampa in PDF
- **Salvataggio locale** (localStorage) — i dati persistono tra le sessioni

## Utilizzo

1. Inserisci nome cliente e data
2. Valuta ogni controllo con il semaforo
3. Aggiungi note dove necessario
4. Clicca "Visualizza Report" per l'anteprima
5. Scarica l'HTML o stampa direttamente come PDF

## Deploy

File HTML singolo autocontenuto — nessun build step richiesto.  
Basta servire `index.html` su qualsiasi hosting statico (Netlify, GitHub Pages, ecc.).

## Crediti

Sviluppato da **Lanpartners** — Milano, Italia  
Basato su CIS Microsoft 365 Foundations Benchmark v6.0.1
