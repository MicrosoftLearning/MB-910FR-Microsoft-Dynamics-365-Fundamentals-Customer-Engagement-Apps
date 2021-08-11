---
lab:
    title: 'Labo 4.3 : Laboratoire Capstone Dynamics 365 Field Service'
    module: 'Module 4 : Découvrir les principes fondamentaux de Dynamics 365 Field Service'
---

Module 4 : Découvrir les principes fondamentaux de Dynamics 365 Field Service
========================

## Labo pratique 4.3 - Laboratoire Capstone Dynamics 365 Field Service

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

En général, la société ABC répartit les techniciens de terrain sur site pour qu’ils travaillent sur des tâches client couvrant l’un de ces trois scénarios : 

- Lorsqu’un nouveau système de sécurité est acheté et doit être installé.

- Lorsqu’un agent du support technique n’est pas en mesure résoudre un incident client à distance.

- Lorsqu’un client nous contacte directement pour demander une intervention sur site. 

Récemment, un client Entreprise, Active Transport, Inc., a contacté le support au sujet d’un problème avec une des caméras de leur système de sécurité. Le technicien du support technique n’a pas pu résoudre leur problème à distance si bien qu’il sera nécessaire d’envoyer un technicien de terrain. Dans ce scénario, vous allez procéder ainsi :

- Convertir un enregistrement d’incident en ordre de travail

- Planifier un ordre de travail

- Résoudre un ordre de travail à l’aide de l’application mobile 

## Configuration du labo

  - **Durée estimée **: 45 minutes

## Instructions

## Exercice 1 : Créer un incident et le transformer en un ordre de travail 

### Tâche 1 : Créer un enregistrement d’incident

1. Ouvrez l’application **Dynamics 365 Field Service** si elle n’est pas déjà ouverte. 

2. Dans le volet de navigation de gauche, sélectionnez ** Incidents**. 

3. Dans la **Barre de commandes**, sélectionnez le bouton **Nouveau** pour créer un nouvel enregistrement d’incident.

4. Complétez votre nouvel enregistrement d’incident comme suit :

	- **Titre de l’incident :** Caméra hors service

	- **Client :** Société Best For You Organics

	- **Origine :** Téléphone

	Sauvegardez l’enregistrement.

5. Sélectionnez l’onglet **Field Service**

6. Définissez le champ **Type d’incident** sur **Caméra hors service**. (créer un nouveau)

7. Dans la **Barre de commandes**, sélectionnez le bouton **Enregistrer et fermer** pour enregistrer et quitter l’enregistrement d’incident. 

 

### Tâche 2 : Créer manuellement un ordre de travail

Nous reviendrons ultérieurement à l’enregistrement d’incident que vous avez créé. Examinons ensuite comment créer manuellement un ordre de travail. 

 

1. Dans le volet de navigation de gauche, sélectionnez **Ordres de travail**.

2. Dans la **Barre de commandes**, sélectionnez le bouton **Nouveau** pour créer un nouvel ordre de travail.

3. Renseignez les détails de l’ordre de travail comme suit :

	- **Compte de service :** Déplacements de Margie

	- **Tarifs :** Office 365 US (exemple)

	- **Type d’ordre de travail **: Service

	- **Imposable :** Non

	Sauvegardez l’enregistrement et attribuez-lui le type Incident principal

	- **Type d’incident principal :** Ventilateur hors service (créer un nouveau)

4. Notez le n° de l’ordre de travail pour être sûr de travailler ultérieurement sur l’ordre de travail correct. 

5. Sélectionnez l’onglet **Paramètres**.

6. Définissez le champ **Secteur de vente du service** sur **WA**.

7. Sous **Préférences**, configurez les préférences temporelles comme suit :

	- **Temps écoulé depuis la promesse :** Aujourd’hui à 9h00

	- **Temps jusqu’à la promesse :** Aujourd’hui à 11:00

8. Sélectionnez **Enregistrer et fermer** pour enregistrer vos modifications et quitter le nouvel ordre de travail.

 

### Tâche 3 : Générer un ordre de travail à partir d’un incident

Une autre manière de générer des ordres de travail consiste à réaffecter des enregistrements d’incident. Dans cet exemple, nous allons réaffecter l’enregistrement d’incident Caméra hors service que nous avons créé précédemment. 

 

1. Dans le volet de navigation de gauche, sélectionnez **Incidents**. 

2. Ouvrez l’incident **Caméra hors service** que vous avez créé précédemment. 

3. Dans la **Barre de commandes**, sélectionnez le bouton **Convertir en ordre de travail**. 

4. Une fois la création de l’ordre de travail terminée, sélectionnez le bouton **OK** dans l’écran contextuel pour consulter les détails de l’ordre de travail. 

 

Les deux ordres de travail que vous avez créés récemment sont tous deux prêts à être planifiés. 

## Exercice 2 : Planifier des éléments avec Dynamics 365 Field Service  

### Tâche 1 : Planifier directement à partir d’un ordre de travail

1. Dans le volet de navigation de gauche, sélectionnez **Tableau de planification**.

2. Dans l’écran à haut à droite, définissez **Nouveau tableau de planification** sur **ACTIVÉ**. 

3. À l’aide du champ de recherche **Rechercher des ressources**, entrez Aidan Knaggs. 

4. Au bas de l’écran du volet Besoins, sélectionnez **Ordres de travail non planifiés**.  (Si le volet Besoins ne s’affiche pas, sélectionnez la flèche au bas de l’écran pour le développer.) 

5. Localisez l’ordre de travail **Munson’s Pickles** que vous avez créé à partir de l’enregistrement d’incident. (Rappelez-vous du n° d’ordre de travail). 

6. Faites glisser l’enregistrement **Munson’s Pickles** et placez-le à un emplacement libre de l’enregistrement de contact d’Aiden. 

7. Il peut arriver que vous deviez replanifier un ordre de travail en raison de conflits entre techniciens ou autres facteurs. Les répartiteurs peuvent facilement effectuer cette tâche à l’aide du tableau de planification. 

 

### Tâche 2 : Planifier à l’aide du tableau de planification

1. Dans le volet de navigation de gauche, sélectionnez **Tableau de planification**.

2. À l’aide du champ de recherche **Rechercher des ressources**, entrez le nom de votre compte d’utilisateur. (Votre enregistrement de ressource devrait s’afficher.)

3. Au bas de l’écran du volet Besoins, sélectionnez **Ordres de travail non planifiés**.  (Si le volet Besoins ne s’affiche pas, sélectionnez la flèche au bas de l’écran pour le développer.) 

4. Localisez l’ordre de travail **Active Transport** que vous avez créé à partir de l’enregistrement d’incident. (Rappelez-vous du n° d’ordre de travail). 

5. Faites glisser l’enregistrement **Active Transport** et placez-le à un emplacement libre de votre enregistrement d’utilisateur. Le texte s’affichera en vert si le créneau horaire correspond au créneau horaire préféré du client.

6. Il peut arriver que vous deviez replanifier un ordre de travail en raison de conflits entre techniciens ou autres facteurs. Les répartiteurs peuvent facilement effectuer cette tâche à l’aide du tableau de planification. 

7. Sélectionnez la zone Rechercher des ressources dans le tableau de planification (à droite au-dessus de la colonne du nom de la ressource), entrez **Brady** et localisez l’ordre de travail planifié pour **Brady Hannon** à une heure ultérieure du jour. 

8. **Faites un clic droit** sur l’élément planifié. Dans le menu qui s’affiche, sélectionnez **Substituer la ressource**. Sélectionnez la zone Sélectionner/Rechercher, sélectionnez votre enregistrement puis sélectionnez **Nouvelle attribution**.
