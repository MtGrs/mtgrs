# Progetto #MES & Automazione Industriale

## Descrizione
Questo repository contiene soluzioni e script per lo sviluppo di software orientato al MES (Manufacturing Execution System) e all'automazione industriale. Il progetto è pensato per ottimizzare processi produttivi, garantire tracciabilità e integrare sistemi eterogenei in ambito industriale.

## Funzionalità Principali
- **Gestione della Produzione:** Monitoraggio in tempo reale, avanzamento ordini di lavoro, gestione delle risorse.
- **Integrazione Hardware/Software:** Collegamento con PLC, SCADA e sensori industriali.
- **Analisi e Reportistica:** Raccolta ed elaborazione dei dati di produzione per fornire KPI personalizzati.
- **Scalabilità:** Soluzioni modulabili e adattabili a impianti di varie dimensioni.

## Architettura del Sistema
- **Strati principali:** MES, SCADA, PLC.
- **Interfacce:** Integrazione con ERP e IoT Gateway.
- **Protocolli di comunicazione:** OPC UA, Modbus, MQTT.

### Esempio — Architettura tradizionale
- **Descrizione:** Questo modello rappresenta un'architettura tradizionale di automazione industriale.<br/>
ERP ↔ MES ↔ SCADA ↔ PLC ↔ Sensori

### Esempio — Architettura con robotica integrata
- **Descrizione:** I dati raccolti dai sensori e dalle macchine vengono inviati a un gateway IoT, trasmessi al cloud per analisi avanzate e utilizzati per migliorare la gestione del processo produttivo tramite manutenzione predittiva.<br/>
In questa architettura avanzata, vengono integrati robot industriali per automatizzare attività specifiche.<br/>
Il ***robot*** opera in modo autonomo o assistito, ma sempre coordinato tramite SCADA e MES per garantire coerenza con gli ordini produttivi emessi da ERP.<br/>
**Scopo**: Migliorare la flessibilità produttiva, integrare macchine autonome e ridurre le inefficienze.<br/><br/>
ERP ↔ MES ↔ SCADA ↔ Robot ↔ PLC ↔ Linea Produttiva

### Esempio — Integrazione con sistemi di visione artificiale
- **Descrizione:** Il MES gestisce diverse linee di produzione con macchine di tipologie differenti (CNC, linee di assemblaggio, ecc.), coordinate da sistemi SCADA individuali.<br/><br/>
ERP ↔ MES ↔ SCADA ↔ PLC ↔ Sensori + Sistemi di Visione ↔ Macchine


![Dashboard MES](https://github.com/MtGrs/mtgrs/blob/main/dshb_MES.png)
