# Python UDP Flood Simulator

Un semplice script in Python sviluppato per scopi educativi e di testing all'interno di un laboratorio virtuale isolato. Il programma simula un attacco DoS di tipo UDP Flood per analizzare il comportamento del traffico di rete.

## 🛠 Tecnologie Utilizzate
* **Python 3** (Librerie standard: `socket`, `random`)
* **Ambiente di Test:** Macchine virtuali (Kali Linux e Metasploitable 2)
* **Analisi del Traffico:** Wireshark

## ⚙️ Come Funziona
Lo script utilizza i socket di rete (`AF_INET` e `SOCK_DGRAM`) per inviare pacchetti UDP generati casualmente (`random.urandom`) verso un indirizzo IP e una porta specificati dall'utente. È strutturato con un ciclo di invio parametrizzabile e gestisce eventuali eccezioni di connessione in modo sicuro.

---
*Nota: Questo script è stato realizzato esclusivamente a scopo didattico e di studio all'interno di un ambiente di laboratorio controllato.*
