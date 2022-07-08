# Balder

Application de presence virtuel lumineux.

## Application mobile:

- [ ] Connection de l'utilisateur
- [ ] Ajouter un autre utilisateur pour interaction
- [ ] Remplacer l'autre utilisateur d'interaction.
- [ ] Afficher Forme et Couleur à envoyer
- [ ] Afficher Forme et couleur reçue
- [ ] Notification push de l'élément reçu
- [ ] Ajouter un nouveau device

## Serveur 

- [ ] Gestion des comptes et auth
- [ ] Envoi des notifications Push
- [ ] Stockage des Devices des utilisateurs 
- [ ] Pub-sub entre devices et serveur pour l'envoi de l'état de la LED
- [ ] API pour l'app mobile
  - [ ] Get état de la LED
  - [ ] Put état de la LED
  - [ ] Add device
  - [ ] Remove device
  - [ ] User connection
- [ ] MQ pour les demande de changement d'etat d'un Device.

## RPI

- [ ] Souscription au Serveur pour les changements d'état de la LED
- [ ] Création d'un Token pour l'enregistrement de la LED dans le Serveur
- [ ] Communication avec l'arduino sur le port série USB pour:
  - [ ] ON/OFF de la LED
  - [ ] Changement de couleur

## Arduino

- [ ] Action disponible 
  - [ ] ON/OFF led
  - [ ] Couleur de la LED