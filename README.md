# Face-Mask-Detection
L'objectif principal de ce projet est de proposer un pipeline fonctionnel basé sur
l'apprentissage profond pour détecter les visages et les classifier en temps-réel selon
leurs états en masque bien porté, masque non-porté ou masque mal-porté.

La détection se fait par une caméra reliée à une Raspberry Pi. Les résultats seront
ensuite envoyés vers un serveur distant via le protocole MQTT et en extraire des
statistiques.

Comme cas d’utilisation, un tel outil peut servir pour contrôler le port du masque dans
une entreprise et ne donner l’accès qu’aux personnes qui portent bien leurs bavettes.
