# Conexo - P.o.P. Monitoring System

**Conexo** is an integrated solution developed during the **DT Lab Networking Bootcamp** to address the lack of structured inventories in corporate Points of Presence (P.o.P.). The system enables real-time tracking of network device insertions, removals, and replacements, preventing the loss of critical assets.

## System Architecture
The project is built on a three-pillar architecture:
1. **Data Acquisition**: Powered by a **Webex Chatbot** that allows field operators to manage devices (Firewalls, Switches, Routers) directly through chat commands.
2. **Data Storage**: A **Python (Flask)** backend that communicates with a **PostgreSQL** database (via the `psycopg2` library) to maintain a complete history of every maintenance activity.
3. **Data Visualization**: A dedicated **Web App** that displays rack status (e.g., Naples Site) and real-time statistics on slot utilization.

## Key Features
- **Device Management via Chat**: Rapid commands for /manage (Insertion, Removal, Replacement).
- **Real-time Monitoring**: Web dashboard with detailed tables including Serial Numbers, Device Size, and Status.
- **Data Analytics**: Graphical visualization of remaining cabinet space and device status (Active/Removed).

## Tech Stack
- **Backend:** Python, Flask APIs
- **Database:** PostgreSQL
- **Integrations:** Webex API for the Chatbot
- **Frontend:** Web Application for data monitoring

## The Team (HEIM Solutions)
- **Davide Piccirillo** - Digital Sociologist & Data Analyst
- **Giosuè Casillo** - Digital Sociologist & Data Analyst
- **Francesco Brunello** - Computer Science Engineer
- **Davide Cangiano** - Back-end Developer

---
*Project developed in collaboration with Meditech, Cisco, and the University of Naples Federico II / Parthenope.*
