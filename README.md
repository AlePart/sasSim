# Simulatore Tassazione SAS

Un'applicazione web per simulare la tassazione di una SocietÓ in Accomandita Semplice (SAS) in Italia, con funzionalitÓ complete per il calcolo delle imposte per soci di capitale e operativi.

## Caratteristiche

- Calcolo dell'utile aziendale e dell'IRES
- Gestione di soci operativi e di capitale con percentuali di partecipazione diverse
- Calcolo dei contributi INPS per i soci operativi
- Configurazione completa di buoni pasto e rimborsi trasferta
- Calcolo IRPEF con scaglioni personalizzabili
- Addizionali regionali e comunali
- Calcolo del netto percepito per ogni socio

## Come usare il simulatore

1. Inserisci i dati aziendali (fatturato, costi)
2. Configura le aliquote fiscali (IRES, INPS, scaglioni IRPEF)
3. Aggiungi e configura i soci (tipo, percentuale di partecipazione, redditi esterni)
4. Per i soci operativi, configura buoni pasto e trasferte
5. Visualizza i risultati dettagliati per ogni socio

## Accesso rapido

La pagina principale del sito ha un link al simulatore.
╚ anche possibile accedere direttamente alla pagina del simulatore tramite il percorso `/sasSim`.

## Sviluppo

### Prerequisiti

- Node.js (versione 14 o superiore)
- npm o yarn

### Installazione

```bash
# Clona il repository
git clone https://github.com/[tuo-username]/sas-tax-simulator.git

# Entra nella directory
cd sas-tax-simulator

# Installa le dipendenze
npm install

# Avvia il server di sviluppo
npm start
```

### Deploy su GitHub Pages

```bash
# Configura il deploy
npm run deploy
```

## Disclaimer

Questo simulatore fornisce una stima indicativa della tassazione. Per calcoli precisi si consiglia di consultare un commercialista. Le aliquote utilizzate potrebbero richiedere aggiornamenti in base alle normative vigenti.