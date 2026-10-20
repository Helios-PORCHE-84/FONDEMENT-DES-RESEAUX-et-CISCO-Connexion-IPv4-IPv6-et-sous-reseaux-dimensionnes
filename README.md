# FONDEMENT DES RESEAUX et CISCO : Connexion IPv4/IPv6 et sous-réseaux dimensionnés

Contexte & Objectif : 

Projet d'équipe (L1, UE Fondement des réseaux) et Évaluations de compétences Cisco (Packet Tracer). L'objectif est de concevoir, maquette et configurer un réseau d'entreprise complet assurant la connectivité double pile (IPv4/IPv6) et la sécurisation des accès. 


Détails Techniques & Concepts Clés :

• Adressage VLSM : Découpage précis d'un réseau (ex: 192.168.10.0/24 ou 10.19.8.0) en sous-réseaux de tailles variables (ex: /25 pour 100 hôtes, /26 pour 50 hôtes) pour optimiser l'espace d'adressage.

• Infrastructure Cisco : Configuration de routeurs (Router-on-a-stick) et de commutateurs (Catalyst 2960/4221).

• Protocoles & Sécurité : VLANs, Trunking 802.1Q, EtherChannel (LACP), DHCP, Routage inter-VLAN, SSH, RSA, Port Security, et sécurisation des ports inutilisés. 


Cheminement de réalisation (Synopsis) :

1. Topologie et Câblage : Placement des équipements (Routeur R1, Switchs S1/S2, PC) dans la baie de brassage et câblage selon le schéma logique.

2. Plan d'adressage : Calcul des masques de sous-réseaux, des adresses réseau, de broadcast et des plages d'hôtes pour IPv4 et IPv6.

3. Configuration de base et Sécurité : Désactivation du DNS, configuration des bannières MOTD, chiffrement des mots de passe, création d'utilisateurs locaux et activation de SSH (clés RSA 1024 bits).

4. Infrastructure de commutation : Création des VLANs, configuration des liaisons Trunk (avec VLAN natif), agrégation de liens (EtherChannel) et sécurisation des ports d'accès (Port Security).

5. Routage et Services : Configuration des sous-interfaces sur le routeur (encapsulation dot1Q), mise en place du routage par défaut et configuration des pools DHCP (avec exclusion d'adresses).

6. Validation : Configuration des hôtes et tests de connectivité de bout en bout (ping IPv4 et IPv6) entre tous les nœuds du réseau.
