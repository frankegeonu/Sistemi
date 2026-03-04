***PIANIFICAZIONE DELLA RETE***



DISPOSITIVI:



\- 2 router (Router0, Router1)

\- 11 PC host

\- 2 switch

\- 2 hub



---



***RETE DI PARTENZA***



*Indirizzo di rete*: 200.200.200.0/16

*Subnet mask di base*: 255.255.0.0



---



***RETE S1*** 



Host richiesti: fino a 2000

Prefisso: /21



*Subnet mask*: 255.255.248.0



*Indirizzo di rete*: 200.200.200.0/21



*Range host*: 200.200.200.1 – 200.200.207.254



*Broadcast*: 200.200.207.255



*Gateway*: 200.200.200.1



*Assegnazione host:*



\* PC0 → 200.200.200.10/21

\* PC1 → 200.200.200.11/21

\* PC2 → 200.200.200.12/21

\* PC3 → 200.200.200.13/21

\* PC4 → 200.200.200.14/21



---



***RETE S2***



Host richiesti: fino a 300



Prefisso: /23



*Subnet mask*: 255.255.254.0



*Indirizzo di rete*: 200.200.208.0/23



*Range host*: 200.200.208.1 – 200.200.209.254



*Broadcast*: 200.200.209.255



*Gateway:* 200.200.208.1



*Assegnazione host*:



\* PC5 → 200.200.208.10/23

\* PC6 → 200.200.208.11/23

\* PC7 → 200.200.208.12/23



---



***RETE S3***



Host richiesti: fino a 84



Prefisso: /25



*Subnet mask*: 255.255.255.128



*Indirizzo di rete*: 200.200.210.0/25



*Range host*: 200.200.210.1 – 200.200.210.126



*Broadcast*: 200.200.210.127



*Gateway*: 200.200.210.1



*Assegnazione host:*



\* PC8 → 200.200.210.10/25

\* PC9 → 200.200.210.11/25

\* PC10 → 200.200.210.12/25



---



***RETE DI COLLEGAMENTO ROUTER–ROUTER***



Prefisso: /30



Subnet mask: 255.255.255.252



*Indirizzo di rete*: 200.200.210.128/30



Router0: 200.200.210.129/30



Router1: 200.200.210.130/30



*Broadcast*: 200.200.210.131



---



***NOTE FINALI***



\* come indirizzo di gateway è stato utilizzato il primo indirizzo disponibile della sottorete

\* la rete /30 è utilizzata esclusivamente per il collegamento punto-punto tra router







