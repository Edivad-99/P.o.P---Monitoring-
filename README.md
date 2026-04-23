# P.o.P---Monitoring-

# Conexo - P.o.P. Monitoring System 

[cite_start]**Conexo** è una soluzione integrata sviluppata durante il **DT Lab Networking Bootcamp** per risolvere il problema della mancanza di inventari strutturati nei Point of Presence (P.o.P.) aziendali[cite: 1, 4, 22]. [cite_start]Il sistema permette di tracciare l'inserimento, la rimozione e la sostituzione dei dispositivi di rete in tempo reale, evitando la perdita di asset fondamentali[cite: 24, 45, 47].

## Architettura del Sistema
Il progetto si basa su un'architettura a tre pilastri:
1.  [cite_start]**Data Acquisition**: Tramite un **Webex Chatbot** che permette agli operatori sul campo di gestire i dispositivi (Firewall, Switch, Router) direttamente da chat[cite: 42, 43, 83].
2.  [cite_start]**Data Storage**: Un backend in **Python (Flask)** che comunica con un database **PostgreSQL** (tramite libreria `psycopg2`) per mantenere lo storico di ogni manutenzione[cite: 31, 37, 38].
3.  [cite_start]**Data Visualization**: Una **Web App** dedicata che mostra lo stato dei rack (es. Sede di Napoli) e statistiche sull'utilizzo degli slot in tempo reale[cite: 32, 65, 118].

## Funzionalità Chiave
- [cite_start]**Gestione Dispositivi via Chat**: Comandi rapidi per `/gestisci` (Inserimento, Rimozione, Sostituzione)[cite: 60, 66, 68].
- [cite_start]**Monitoraggio Real-time**: Dashboard web con tabelle dettagliate (Serial Number, Device Size, Status)[cite: 118, 128, 132].
- [cite_start]**Analisi dei Dati**: Visualizzazione grafica dello spazio rimanente nei cabinet e dello stato dei dispositivi (Attivi/Rimossi)[cite: 185, 186, 187].

## Tech Stack
- [cite_start]**Backend:** Python, Flask APIs[cite: 35, 37].
- [cite_start]**Database:** PostgreSQL[cite: 39].
- [cite_start]**Integrazioni:** Webex API per il Chatbot[cite: 114].
- [cite_start]**Frontend:** Web Application per monitoraggio dati[cite: 117].

## Il Team (HEIM Solutions)
- [cite_start]**Davide Piccirillo** - Digital Sociologist & Data Analyst [cite: 10, 241, 242]
- [cite_start]**Giosuè Casillo** - Digital Sociologist & Data Analyst [cite: 15, 243, 245]
- [cite_start]**Francesco Brunello** - Computer Science Engineer [cite: 11, 246, 248]
- [cite_start]**Davide Cangiano** - Back-end Developer [cite: 16, 253, 255]

---
[cite_start]*Progetto realizzato in collaborazione con Meditech, Cisco e l'Università degli Studi di Napoli Federico II* [cite: 8, 13, 249, 256]
