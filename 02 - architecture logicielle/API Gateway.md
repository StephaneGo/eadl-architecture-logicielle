
Date: 01/11/2026
Tags: 
[[Architecture logicielle]]

# Questions


# Notes


## quels sont les avantage de l'architecture API Gateway

L'architecture API Gateway centralise l'accès aux services backend via un point d'entrée unique.

### Avantage 1 : Sécurité centralisée

Elle gère l'authentification (OAuth, JWT), l'autorisation et la protection contre les attaques (DDoS, rate limiting) en un seul endroit, évitant de dupliquer ces contrôles sur chaque service.

### Avantage 2 : Gestion du trafic optimisée

Routage intelligent, équilibrage de charge, mise en cache et limitation de débit améliorent les performances et la disponibilité, en masquant la complexité des backends.

### Avantage 3 : Simplification client

Les clients font une seule requête ; la gateway agrège les réponses de multiples services, traduit les protocoles et génère une API cohérente, facilitant le développement frontend.

# Références

