# Suivie-Budget-perso

1. Titre du projet :
Suivi de Budget Personnel
2. Contexte du projet :
L’objectif de ce projet est de développer une application simple qui permet à un utilisateur de suivre ses finances personnelles en enregistrant ses dépenses et ses revenus. L’application doit offrir un tableau de bord qui affiche le solde total en temps réel, basé sur les transactions ajoutées.
3. Objectifs du projet :
•	Permettre à l'utilisateur d'ajouter des transactions (dépenses et revenus).
•	Afficher un solde total en fonction des transactions saisies.
•	Sauvegarder les données de manière persistante avec localStorage.
•	Offrir une interface simple, claire et responsive.
4. Fonctionnalités principales :
•	Ajout de transactions : L’utilisateur pourra entrer un montant et une description pour chaque transaction.
o	Revenus : Le montant est ajouté au solde total.
o	Dépenses : Le montant est soustrait du solde total.
•	Affichage des transactions : Chaque transaction ajoutée doit être visible sous forme de liste.
•	Calcul du solde total : Le solde sera automatiquement mis à jour à chaque ajout ou suppression de transaction.
•	Persistance des données : Les transactions doivent être sauvegardées dans le localStorage, ce qui permettra de les garder même après un rafraîchissement de la page.
•	Interface utilisateur :
o	Formulaire d'ajout de transactions (champ montant et description).
o	Liste des transactions.
o	Affichage du solde total.
o	Interface claire et responsive.
5. Technologies utilisées :
•	Frontend :
o	HTML : Structure de la page.
o	CSS : Mise en forme, design simple et responsive.
o	JavaScript : Logique d’ajout de transactions, calcul du solde, et gestion du localStorage.
•	Stockage des données :
o	localStorage : Pour stocker les transactions localement dans le navigateur.
6. Contraintes et limitations :
•	Débutant : L’application doit rester simple, sans backend ni base de données. Tout doit fonctionner sur le côté client avec localStorage.
•	Responsive : L'application doit être utilisable sur ordinateur de bureau ainsi que sur mobile (mais de manière simple, sans des fonctionnalités mobiles avancées).
•	Design : L’aspect visuel doit être simple et épuré pour éviter la surcharge d’informations.
7. Maquette de l’application :
Tu peux créer une esquisse de ton application pour visualiser l'interface. Cela peut être un simple dessin sur papier ou une maquette faite avec des outils comme Figma ou Adobe XD. Mais ce n'est pas obligatoire au début. Ce qui est essentiel, c'est que tu aies une idée claire de ce que tu veux afficher et comment l’agencer.
Voici une idée basique de l'interface :
•	Un formulaire avec deux champs (montant et description) et un bouton "Ajouter".
•	Une liste des transactions enregistrées.
•	Un affichage du solde total.
8. Plan de développement :
Voici comment tu peux organiser ton travail :
Phase 1 : Préparation
•	Créer la structure HTML de base.
•	Styliser la page avec du CSS simple (mise en page, couleurs, etc.).
Phase 2 : Ajout de la fonctionnalité JavaScript
•	Implémenter la gestion des transactions (ajouter, afficher, et calculer le solde).
•	Sauvegarder les transactions dans le localStorage.
•	Afficher les transactions à chaque rechargement de la page.
Phase 3 : Tests et validation
•	Tester l’application pour vérifier que les transactions s’ajoutent correctement.
•	Tester la persistance des données avec localStorage (si tu rafraîchis la page, les transactions doivent rester).
•	Vérifier que le solde est bien mis à jour.
Phase 4 : Améliorations et fonctionnalités supplémentaires
•	Ajouter des vérifications (ex : s'assurer que le montant est valide).
•	Améliorer le design (polices, couleurs, responsive).
•	Ajouter des fonctionnalités supplémentaires si tu te sens prête (par exemple, catégories de transactions, ajout d’un graphique simple, etc.).
________________________________________
9. Critères de réussite :
Le projet sera considéré comme réussi si :
•	L’utilisateur peut ajouter des transactions, et le solde total est mis à jour correctement.
•	Les transactions sont sauvegardées dans localStorage et persistent après un rafraîchissement de la page.
•	L'interface est simple, intuitive et fonctionnelle.
________________________________________
10. Délais :
Tu peux définir un délai en fonction de ton emploi du temps et de tes progrès. Par exemple :
•	Phase 1 (préparation) : 1 à 2 jours.
•	Phase 2 (fonctionnalités de base) : 3 à 4 jours.
•	Phase 3 (tests et validation) : 1 à 2 jours.
•	Phase 4 (améliorations) : Selon ton temps et tes objectifs, tu peux étendre cette phase.
