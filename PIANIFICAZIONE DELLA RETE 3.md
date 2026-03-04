**PIANIFICAZIONE DELLA RETE**



*DISPOSITIVI:*

-1 router

-8 pc host + 3 della consegna

-4 switch



RETE DI CLASSE C: 191.155.30.0/24

SUBNET MASK DI BASE: 255.255.255.0



*RETE 1:*

-INDIRIZZO DI SUB: 191.155.30.0/25

-SUBNET MASK: 255.255.255.128

-RANGE: 191.155.30.1 - 191.155.30.126

-INDIRIZZO DI BROADCAST: 191.155.30.127/25

-GATEWAY / ROUTER: 191.155.30.1

-HOST 89: 191.155.30.90



*RETE 2:*

-INDIRIZZO DI SUB: 191.155.30.128/26

-SUBNET MASK: 255.255.255.192

-RANGE: 191.155.30.129 - 191.155.30.190

-INDIRIZZO DI BROADCAST: 191.155.30.191/26

-GATEWAY / ROUTER: 191.155.30.129

-HOST 39: 191.155.30.168



*RETE 3:*

-INDIRIZZO DI SUB: 191.155.30.192/27

-SUBNET MASK: 255.255.255.224

-RANGE: 191.155.30.193 - 191.155.30.222

-INDIRIZZO DI BROADCAST: 191.155.30.223/27

-GATEWAY / ROUTER: 191.155.30.193

-HOST 9: 191.155.30.202



*RETE 4:*

-INDIRIZZO DI SUB: 191.155.30.224/28

-SUBNET MASK: 255.255.255.240

-RANGE: 191.155.30.225 - 191.155.30.238

-INDIRIZZO DI BROADCAST: 191.155.30.238/28

-GATEWAY / ROUTER: 191.155.30.225





*\*NOTE:*

-per comodità come indirizzo delle porte dei router/gateway per gli host ho utilizzato il primo indirizzo tra quelli assegnabili

-nella prima rete ho messo /25 perché per indirizzare tutti gli ho bisogno di almeno 7 bit che quindi dedicherò alla parte di hostID stessa cosa per le altre sottoreti solo che hanno rispettivamente bisogno di 6 bit, 5 bit e 4 bit





