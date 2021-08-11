---
lab:
    title: 'Labo 2.3 : Laboratoire Capstone Dynamics 365 Sales'
    module: 'Module 2 : Découvrir les principes fondamentaux de Dynamics 365 Sales'
---

Module 2 : Découvrir les principes fondamentaux de Dynamics 365 Sales
========================

## Labo pratique 2.3 - Laboratoire Capstone Dynamics 365 Sales

## Scénario de laboratoire

La société ABC est spécialisée dans la fabrication, la vente, l’installation et le dépannage d’équipements de sécurité. Ses produits incluent des caméras de sécurité à la fois d’intérieur et d’extérieur, des détecteurs d’humidité et d’incendie, des services de surveillance, etc. 

La société ABC utilise les applications Dynamics 365 pour renforcer l’engagement avec tous ses clients dans les différents domaines de son organisation, depuis les ventes jusqu’au dépannage. 

**Vente et marketing**

La société ABC commercialise ses offres auprès des clients résidentiels directement via des campagnes marketing ciblées. Les clients sont ciblés en fonction de leur ville et autres facteurs. Les supports marketing sont envoyés par courrier électronique et sont routés en fonction de l’interaction des clients avec le courrier électronique. 

Si certains de ses produits de petite dimension sont vendus par l’intermédiaire de revendeurs, la plupart sont vendus directement aux consommateurs par son équipe de vente interne.

En interne, le focus est axé sur deux domaines principaux : 

- **Clients résidentiels :** Les clients résidentiels cherchent généralement à acquérir des composants individuels ou à acheter une solution complète pour la maison. Leurs cycles de ventes sont généralement plus courts et ont pour origine les réseaux sociaux, des sites web, des références ou un contact direct à partir du prospect. Étant donné que les clients résidentiels recherchent plutôt des produits spécifiques ou des installations de petite dimension, leurs cycles de vente ne durent généralement que quelques jours ou semaines. 

- **Clients Entreprise :** Les vendeurs Entreprise se concentrent sur les clients qui recherchent des solutions d’entreprise plus spécialisées et personnalisées. Les ventes Entreprise s’étendent généralement sur plusieurs lieux et requièrent souvent plusieurs ressources pour mener à bien le projet. Ces cycles de vente sont généralement plus longs et comportent davantage de parties mobiles. 

Il est important que tous les vendeurs de la société ABC disposent des outils, ressources et conseils nécessaires, quel que soit leur domaine de focus, lorsqu’ils proposent leurs produits aux clients. 

**Installation système :**

Le processus d’installation pour les équipements de sécurité achetés varie selon le type de client. 

- **Clients résidentiels :** Étant donné que les installations résidentielles prennent généralement moins d’un jour, elles sont effectuées par les employés internes. Une fois la vente terminée, un ordre de travail est créé, un technicien qualifié est identifié et son intervention est planifiée. 

- **Clients Entreprise :** Les déploiements Entreprise peuvent prendre des mois et exigent qu’un responsable de projet supervise les opérations au jour le jour. Ce suivi inclut la création de plans de projet, la mise en place des équipes du projet et la planification des ressources. 

**Service et support :**

Une fois les systèmes installés, la société ABC assure le support après-vente. Un client qui rencontre un problème peut contacter le support clients. Un agent tente de travailler avec le client à distance pour résoudre son problème. Si le problème ne peut pas être résolu à distance, l’agent de support peut réaffecter le problème vers un ordre de travail qui sera planifié et exécuté par un technicien de terrain qualifié.  

## Objectifs

Vous êtes représentant commercial pour les ventes résidentielles de la société ABC. Si un grand nombre de vos prospects sont issus des événements parrainés par la société, des campagnes marketing et des listes achetées, il vous arrive toutefois encore souvent de recevoir des demandes directes de la part des clients. Lorsque vous recevez ces demandes, vous devez les entrer manuellement et exploiter ces prospects tout au long du cycle de vie de vente. 

Vous avez récemment reçu un appel d’une personne appelée Piper Smith. Une série de cambriolages s’est produite dans son quartier et elle souhaiterait acheter un équipement de sécurité pour sa maison. Vous allez entrer le prospect Piper dans le système en vous efforçant de la qualifier et de la faire avancer dans le cycle de vente. 

À l’issue de ce labo, vous aurez réalisé les opérations suivantes :

- Entrer un prospect dans Dynamics 365 Sales

- Qualifier et convertir un prospect en une opportunité de vente.

- Gérer les activités quotidiennes associées à une opportunité. 

- Ajouter un devis à une opportunité. 

- Fermer une opportunité de vente. 

- Générer une facture. 

## Configuration du labo

  - **Durée estimée **: 30 minutes

## Instructions
  
## Exercice 1 : Créer et gérer un prospect dans Dynamics 365 Sales


### Tâche 1 : Créer un nouveau prospect

1. Si nécessaire, ouvrez un navigateur InPrivate et accédez à [Https://home.Dynamics.com](https://home.dynamics.com/) 

2.  À l’invite, connectez-vous avec les identifiants utilisateur que l’instructeur vous a fournis. 

3. Dans la liste d’applications qui s’affiche, sélectionnez **Centre des ventes**.

4. Dans le volet de navigation de gauche, sélectionnez **Prospects**. 

5. Pour afficher tous les prospects de vente actuels dans le système, sélectionnez la flèche bas à côté de **Mes prospects ouverts**, et dans le menu qui s’affiche, sélectionnez **Prospects actifs**. 

6. Pour revenir à votre liste de prospects, sélectionnez la flèche bas à côté de Prospects actifs, et dans le menu qui s’affiche, sélectionnez **Mes prospects ouverts**. 

7. Nous allons ensuite créer un nouveau prospect pour Piper Smith. Dans la vue **Mes prospects ouverts**, sélectionnez **Nouveau** dans la barre de commandes.

8. Complétez votre nouvel enregistrement de prospect comme suit :

	- **Rubrique :** Intéressé par un équipement de sécurité - Vos initiales »

	- **Prénom :** Piper

	- **Nom :** Smith - Vos initiales

	- **Téléphone mobile :** 888 555-1762

	- **E-mail :** piper@sample.com


9. Cliquez sur le bouton **Enregistrer** dans la barre de commandes pour enregistrer le nouveau prospect et laissez-le ouvert.

10. Remarquez le flux des processus d’entreprise **prospect-opportunité** en haut de l’enregistrement. Cliquez sur la **Phase de qualification** pour la sélectionner. Renseignez la phase comme suit :

	- **Période d’achat :** Ce trimestre

	- **Budget estimé :** 10000 

	- **Processus d’achat :** Individuel

	- **Identifier le décisionnaire :** Terminé

11. Cliquez sur le symbole **X** dans la fenêtre de la phase pour fermer la fenêtre. 

12. Accédez à la **Chronologie** des enregistrements au milieu de l’écran et sélectionnez l’**icône du signe Plus** pour ajouter une nouvelle activité. 

13. Dans le menu qui apparaît, sélectionnez **Appel téléphonique**.

14. Dans l’écran Création rapide d’appel téléphonique, renseignez l’appel téléphonique comme suit :

	- **Objet :** Intéressé par un équipement de sécurité pour la maison

	- **Numéro de téléphone :** 888 555-1762

	- **Direction :** Entrant

	- **Description :** Après les événements qui se sont produits dans son quartier, elle cherche à acheter un système de sécurité. 

15. Sélectionnez le bouton **Enregistrer et fermer**.

16. Vous remarquerez que l’activité **Intéressé par un équipement de sécurité pour la maison** s’affiche maintenant dans la **Chronologie** des enregistrements. Pointez sur l’activité et sélectionnez l’activité de fermeture **Icône de coche** pour marquer l’appel téléphonique comme terminé. 

17. Dans la fenêtre **Fermer un appel téléphonique**, vérifiez que l’état est défini sur **Terminé** et sélectionnez **Fermer**.

 

**IMPORTANT :** Ne fermez pas l’enregistrement du prospect. Laissez-le ouvert car vous en aurez besoin dans la prochaine tâche. 

 

### Tâche 2 : Qualifier le prospect comme opportunité

Après une visite chez Piper, vous estimez qu’elle manifeste suffisamment d’intérêt pour poursuivre la démarche et que nous proposons des produits et services susceptibles de l’intéresser. Vous allez ensuite qualifier l’enregistrement de prospect. Un enregistrement d’opportunité associé est créé et le système passe à la phase suivante du processus de vente prospect-opportunité. 

1. Dans la **Barre de commandes**, cliquez sur le bouton **Qualifier**. 

2. Lorsque le système qualifie le prospect, un enregistrement d’opportunité est créé et le processus d’entreprise avance à la phase **Développer**. Sélectionnez la phase **Qualifier** pour afficher l’enregistrement de prospect d’origine. 

3. Sélectionnez la phase **Qualifier** pour revenir à l’opportunité.

4. Cliquez sur le bouton **Enregistrer et fermer** pour fermer l’enregistrement d’opportunité créé. 

 

 

## Exercice 2 : Gérer une opportunité de vente dans Dynamics 365 Sales

Maintenant que nous avons réussi à qualifier le prospect comme opportunité, il est temps de faire progresser l’opportunité dans son cycle de vie.

### Tâche 1 : Gérer une opportunité de vente et créer un devis 

1. Dans le volet de navigation de gauche, sélectionnez ** Opportunités**. 

2. Sélectionnez la flèche déroulante à côté de **Mes opportunités ouvertes** et dans le menu qui s’affiche, sélectionnez **Toutes les opportunités**.

3. Dans la Barre de commandes, sélectionnez Afficher un graphique. Notez que le graphique des **clients principaux** qui s’affiche est basé sur la table des opportunités. 

4. Sélectionnez la flèche déroulante à côté des **clients principaux**, puis dans le menu qui s’affiche, sélectionnez **Pipeline des ventes**.

5. Sélectionnez la partie Qualifier de la synthèse. Notez que la liste des Opportunités change pour afficher les opportunités ayant atteint la phase de qualification. 

6. Sélectionnez un point de l’espace blanc pour afficher à nouveau toutes les opportunités ouvertes. 

7. Sélectionnez la flèche déroulante à côté de **Opportunités ouvertes** et dans le menu qui s’affiche, sélectionnez **Mes opportunités ouvertes**. **Intéressé par un équipement de sécurité - Vos initiales** sera sans doute le premier élément qui apparaît, et le graphique devrait le refléter aussi. 

8. Dans la **Barre de commandes**, sélectionnez le bouton **Masquer le graphique**. 

9. Ouvrez **Intéressé par un équipement de sécurité - Vos initiales** qui a été créé lorsque vous avez qualifié le prospect précédemment. Notez que l’enregistrement se trouve déjà dans la phase **Développer** puisqu’il a été créé à partir d’un prospect précédemment qualifié.  

10. Sur l’en-tête de l’opportunité **Intéressé par un équipement de sécurité - Vos initiales** en haut de l’enregistrement, sélectionnez la flèche vers le bas à côté du champ Propriétaire. 

11. Procédez comme suit :

	- **Date de clôture estimée :** Demain

	- **Chiffre d’affaires estimé :** 12 500,00

12. Accédez à la **Chronologie des enregistrements** au milieu de l’écran et sélectionnez l’**icône du signe Plus** pour ajouter une nouvelle activité. 

13. Dans le menu qui s’affiche, sélectionnez **Rendez-vous**.

14. Dans l’écran **Création rapide : Rendez-vous**, renseignez les champs comme suit :

	- **Objet :** Réunion rapide - « Vos initiales »

	- **Lieu :** En ligne

	- **Heure de début **: Demain à 10h00

	- **Heure de fin :** Demain à 10:30

15. Dans la barre de commandes, sélectionnez **Enregistrer et fermer**.

16. Dans le flux des processus d’entreprise prospect-opportunité, sélectionnez la phase **Développer**. Notez que vous devez identifier les parties prenantes et les concurrents.

17. Sélectionnez le symbole **X** dans la fenêtre de la phase pour la fermer et pouvoir continuer à travailler. 

18. Dans la sous-grille **Parties prenantes**, notez que **Piper** est déjà définie comme partie prenante. 

19. Dans la sous-grille Équipe de vente, sélectionnez les **points de suspension verticaux**. Dans le menu qui s’affiche, sélectionnez **Nouvelle connexion**. 

20. Dans le champ **Recherche**, entrez le texte **Système** et sélectionnez l’enregistrement **Administrateur système**. Une fois que vous avez terminé, sélectionnez le bouton **Ajouter**. L’administrateur système devrait maintenant apparaître dans l’équipe de vente. Si ce n’est pas le cas, cliquez sur le bouton **Actualiser** dans la barre de commandes. 

21. Dans la sous-grille Concurrents, sélectionnez les **points de suspension verticaux**. Dans le menu qui s’affiche, sélectionnez **Ajouter un concurrent existant**. 

22. Dans l’écran **Rechercher un enregistrement**, sélectionnez **Nouvel enregistrement**, puis sélectionnez **Concurrents**.

23. Dans l’écran Création rapide : **Concurrent**, définissez le champ **Nom** sur **Coho Security - « Vos initiales »**.

24. Sélectionnez le bouton **Enregistrer et fermer**.

25. Vérifiez que l’enregistrement Coho Security que vous venez de créer est sélectionné, puis sélectionnez le bouton **Ajouter**. 

26. Sélectionnez la phase **Développer** dans le flux des processus d’entreprise **prospect-opportunité**, puis définissez les deux étapes **Identifier les parties prenantes** et **Identifier les concurrents** sur **Terminé**. 

27. Sélectionnez le bouton **Nouvelle phase** pour passer à la phase **Proposer**.

28. Dans la phase **Proposer**, marquez **Identifier l’équipe de vente** comme **Terminé**.

29. Sélectionnez le symbole **X** dans la phase Proposer pour fermer la fenêtre de phase. 

30. Dans l’enregistrement de l’opportunité, sélectionnez l’onglet **Devis**. 

31. Dans la sous-grille Devis, sélectionnez le bouton **Nouveau devis**.

 

**IMPORTANT :** Étant donné que de nombreuses applications internes sont déployées sur ces environnements, il est possible que le formulaire de devis actuellement affiché ne soit pas le formulaire correct pour les fonctionnalités liées aux ventes. Si le texte sous le nom du devis **Intéressé par un équipement de sécurité - Vos initiales** affiche : **Devis . Devis**, le formulaire correct est chargé. S’il affiche **Devis . Informations de Field Service**, vous devez le changer. Si vous avez besoin de le modifier, sélectionnez la flèche déroulante à côté de **Devis . Informations de Field Service**. Dans le menu qui s’affiche, sélectionnez **Devis**. 

 

### Tâche 2 : Gérer un devis

Maintenant que vous avez un devis associé, vous allez préparer le devis à présenter à un client. Dans des circonstances habituelles, nous ajouterions probablement les produits à l’enregistrement du devis avant qu’il soit transmis à un client. Étant donné que nous travaillons dans des environnements partagés, nous allons ignorer l’ajout des lignes de devis et nous concentrer sur la remise du devis. 


1. Vous devez maintenant sélectionner une liste de prix à joindre à l’opportunité.  Sous **Tarifs** dans le volet gauche, sélectionnez l’icône Recherche puis sélectionnez **Office 365 USA (exemple)** dans les options. Dans la **Barre de commandes**, sélectionnez le bouton **Activer un devis** pour activer le devis. 

2. Maintenant que le devis a été créé, mettons à jour l’enregistrement de l’opportunité de manière à refléter les nouvelles données. Dans l’enregistrement du devis, sélectionnez l’opportunité **Intéressé par un équipement de sécurité** - **« Votre nom »** dans le champ **Opportunité** sous la section **Informations de vente**. L’enregistrement du devis devrait s’ouvrir sur votre écran. 

3. Dans l’enregistrement du devis, sélectionnez la phase **Proposer**. 

4. Marquez les étapes **Développer la proposition**, **Effectuer une révision interne** et **Présenter la proposition** comme étant **terminées**, et sélectionnez le bouton **Phase suivante** pour passer à la phase **Fermer**. 

5. Dans la phase **Fermer**, marquez les étapes **Effectuer la proposition finale**, **Présenter la proposition finale**, **Envoyer une carte de remerciement** et **Compte rendu du fichier** comme étant **terminées**. 

6. Définissez **Confirmer la date de décision** sur **la date d’aujourd’hui**. 

7. Sélectionnez le bouton **Terminer**. 

8. Cliquez sur le symbole **X** dans la fenêtre de la phase de clôture pour fermer la fenêtre. 

9. Sélectionnez l’onglet **Devis**. 

10. Ouvrez le devis **Intéressé par un équipement de sécurité - Vos initiales**. 

11. Dans la **Barre de commandes**, sélectionnez le bouton **Créer une commande**.

12. Dans la fenêtre Créer une commande, renseignez les champs suivants :

	- **Raison du statut :** Conclu

	- **Conclu le :** Date du jour

	- **Fermer l’opportunité :** Oui

	- **Calculer le revenu réel à partir des devis :** Non

	- **Revenu réel :** 12 500$

13. Sélectionnez le bouton **OK** 

Le système crée une nouvelle commande client associée à l’élément. Il ferme en outre à la fois l’enregistrement du devis et l’enregistrement d’opportunité associée. Une fois que tout est terminé, la commande s’ouvre sur votre écran. Laissez la commande ouverte. 

###  

### Tâche 3 : Gérer la commande et la facture

Maintenant que vous avez généré une commande client, nous allons fermer la commande et générer une facture. Dans des circonstances habituelles, les produits figurant sur l’enregistrement de devis seraient ajoutés à la commande client. Étant donné que nous travaillons dans des environnements partagés, nous allons poursuivre comme si les produits étaient joints. 

 

1. Dans la **Barre de commandes**, sélectionnez le bouton **Exécuter la commande**. 

2. Dans la fenêtre Exécuter la commande, renseignez les champs suivants :

	- **Raison du statut :** Terminé

	- **Date d’exécution :** Date du jour

3. Sélectionnez le bouton **Traiter**. 

4. Dans la **Barre de commandes** de la commande, cliquez sur le bouton **Créer la facture**. 

5. Dans la **Barre de commandes**, sélectionnez le bouton **Facture payée**. Sélectionnez OK.
