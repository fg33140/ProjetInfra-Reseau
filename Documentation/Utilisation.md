# **Utilisation**

1. Faire glisser un VPCS dans notre infra, puis le brancher sur n'importe quel Switch "Access" (exepté le 5) sur une des interfaces suivantes :  
   - 0/0
   - 0/1
   - 0/2

2. Une fois branché, allumez le VPCS et accédez à sa Console, taper la commande :  
   - ip dhcp  

    Pour vérifier les données fournis par le DNS, taper **sh ip**

### Il est maintenant possible, avec notre VPCS, de ping n'importe quel appareil du LAN, de ping des IP publics, nom de domaine public existant et surtout de pouvoir ping le futur server Web "web.projetinfra.net"  

<br>

### Remarque : Il est possible de voir le fonctionnement du protocol NAT.
 - Ouvrez la console du router et taper la commande **debug ip nat** puis effectuer des pings vers des IP public avec un VPCS de l'infra GNS3

[Suivant](/Documentation/Monitoring.md)  
[Retour](/Documentation/Installation.md)