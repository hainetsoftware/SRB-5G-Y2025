# Mappa Interattiva Postazioni Radio Base - Livorno 2025

## Descrizione

Questa pagina web presenta una mappa interattiva con le postazioni di Stazioni Radio Base (SRB) costruite nel comune di Livorno nell'anno 2025.

## Caratteristiche

### 🗺️ Mappa Interattiva
- Mappa basata su **Leaflet** e **OpenStreetMap**
- Visualizzazione in tempo reale di tutte le postazioni
- Zoom e pan intuitivi
- Auto-zoom al caricamento per visualizzare tutte le postazioni

### 📍 Marker Personalizzati
- Ogni postazione è identificata da un marker numerato
- Colore del marker corrisponde all'operatore telefonico
- Il numero identifica l'ordine della postazione nella lista

### 📋 Informazioni Popup
Cliccando su un marker, viene visualizzato un popup contenente:
- **Postazione**: Nome della stazione radio base
- **Indirizzo**: Localizzazione geografica
- **Operatore**: Gestore della rete (TIM, Vodafone, Wind-Tre, Iliad, Linkem, ecc.)
- **Data**: Data di costruzione/installazione (2025)

### 🎨 Legenda Colori Operatori
- 🔴 **Iliad**: Rosso (#FF6B6B)
- 🔵 **Linkem**: Turchese (#4ECDC4)
- 🔵 **Tim**: Blu (#45B7D1)
- 🟠 **Vodafone**: Arancione (#FFA07A)
- 🟢 **Wind-Tre**: Verde (#98D8C8)
- 🟡 **Altri gestori**: Giallo (#F7DC6F)

### 📱 Sidebar Laterale
- **Lista completa** di tutte le postazioni
- Visualizzazione rapida di informazioni per ogni postazione
- Click su un elemento della lista per:
  - Aprire il popup della postazione
  - Spostare la vista della mappa su quella postazione (zoom 15x)

## Come Usare

### Apertura del file
1. Scarica il file `mappa_postazioni.html`
2. Apri il file con un browser web (Chrome, Firefox, Edge, Safari, ecc.)
3. La mappa si caricherà automaticamente

### Navigazione
- **Zoom**: Usa la rotella del mouse o i pulsanti + e - in alto a sinistra
- **Pan**: Trascina la mappa con il mouse
- **Clicca su un marker** per visualizzare i dettagli della postazione
- **Clicca su un elemento della lista** a destra per saltare a quella postazione

### Interazione
- Passa il mouse sugli elementi della lista laterale per evidenziarli
- Clicca su un elemento per centrare la mappa e aprire il popup
- Chiudi i popup cliccando sulla X nel popup o cliccando altrove sulla mappa

## Dati Disponibili

Ogni postazione include:

| Campo | Descrizione |
|-------|-------------|
| Nome | Identificativo della Stazione Radio Base |
| Indirizzo | Ubicazione geografica in Livorno |
| Operatore | Gestore della rete cellulare |
| Data | Data di installazione/autorizzazione |
| Coordinate | Posizione geografica in WGS84 (Lat/Lon) |

## Tecnologie Utilizzate

- **Leaflet**: Libreria JavaScript per mappe interattive
- **OpenStreetMap**: Dati geografici e layer mappa
- **HTML5 + CSS3 + JavaScript**: Struttura, stile e interattività
- **Sistema di coordinate**: Gauss-Boaga fuso ovest (EPSG:3003) convertite in WGS84

## Compatibilità

✅ Chrome / Chromium
✅ Firefox
✅ Safari
✅ Edge
✅ Dispositivi mobili (responsive design)

## Note Tecniche

- Le coordinate originali sono nel sistema Gauss-Boaga fuso ovest (EPSG:3003)
- Sono state convertite approssimativamente al sistema WGS84 per la visualizzazione su OpenStreetMap
- La mappa è completamente client-side (non richiede server)
- Tutti i dati vengono caricati localmente nel browser

## Riferimenti

- **ARPAT** (Agenzia Regionale per la Protezione dell'Ambiente della Toscana)
- **SIRA**: Sistema Informativo Regionale Ambientale
- Portale: https://sira.arpat.toscana.it/

## Licenza

Dati rilasciati con licenza **IODL v.2** (Italian Open Data License)
- Liberamente utilizzabili
- Attribuzione consigliata: ARPAT SIRA

## Contatti

Per informazioni sulle postazioni radio base:
- ARPAT - Via del Ponte alle Mosse, 211 - 50144 Firenze
- Tel: 055 32061
- Email: pfr_sira@arpat.toscana.it
