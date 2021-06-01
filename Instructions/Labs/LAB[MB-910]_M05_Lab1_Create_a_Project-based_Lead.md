---
lab:
    title: 'Labo 5.1 : Créer un prospect basé sur un projet'
    module: 'Module 5 : Découvrir les principes fondamentaux de Dynamics 365 Project Operations'
---

Module 5 : Découvrir les principes fondamentaux de Dynamics 365 Project Operations
========================

## Labo pratique 5.1 : Créer un prospect basé sur un projet

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

Les vendeurs Entreprise de la société ABC se concentrent sur les clients qui recherchent des solutions d’entreprise plus spécialisées et personnalisées. Pour cette raison, les ventes Entreprise s’étendent généralement sur plusieurs emplacements avec communication liée et requièrent souvent plusieurs ressources pour mener à bien le projet. Les cycles de vente Entreprise de la société ABC peut durer de nombreux mois et exiger l’exécution de plusieurs parties mobiles. 

Une fois qu’un système a été vendu à un client Entreprise, l’implémentation du projet peut demander plusieurs mois. Un responsable de projet est affecté à chaque projet pour superviser la planification du projet et les opérations au jour le jour. Ce suivi inclut la création de plans de projet, la mise en place des équipes du projet et la planification des ressources. 

En tant que vendeur Entreprise, vous êtes chargé de vendre des solutions de sécurité personnalisées haut de gamme aux clients. Vous avez récemment reçu un appel d’une société appelée Consolidated Sample. Elle aimerait mettre en place une solution de sécurité complètement intégrée couvrant tous ses sites. Vous allez entrer le prospect Consolidated Sample dans le système, le faire progresser dans le cycle de vente du projet et créer un projet correspondant. 

À l’issue de ce labo, vous aurez réalisé les opérations suivantes :

- Entrer un prospect de projet dans Dynamics 365 Sales

## Configuration du labo

  - **Durée estimée**: 10 minutes

## Instructions

## Exercice 1 : Créer un prospect basé sur un projet

### Tâche 1 : Créer un nouveau prospect

1. Si nécessaire, ouvrez un navigateur InPrivate et accédez à [Https://home.Dynamics.com](https://home.dynamics.com/) 

2.  À l’invite, connectez-vous avec les identifiants utilisateur que l’instructeur vous a fournis. 

3. Dans la liste d’applications qui s’affiche, sélectionnez **Project Operations**. **(Remarque :** elle peut aussi s’appeler Project Service)

4. Dans le volet de navigation de gauche, sélectionnez la zone **Projets**. 

5. Dans le menu qui s’affiche, sélectionnez **Ventes**.

6. Dans le volet de navigation de gauche, sélectionnez **Prospects**. 

7. Pour afficher tous les prospects de vente actuels dans le système, sélectionnez la flèche bas à côté de **Mes prospects ouverts**, et dans le menu qui s’affiche, sélectionnez **Prospects actifs**. 

8. Pour revenir à votre liste de prospects, sélectionnez la flèche bas à côté de Prospects actifs, et dans le menu qui s’affiche, sélectionnez **Mes prospects ouverts**. 

9. Nous allons ensuite créer un nouveau prospect pour une société appelée Consolidated Sample. Dans la vue **Mes prospects ouverts**, sélectionnez **Nouveau** dans la barre de commandes.

10. Complétez votre nouvel enregistrement de prospect comme suit :

	- **Rubrique :** Implémentation globale complète - Vos initiales

	- **Type :** Basé sur le travail

	- **Prénom :** Jean

	- **Nom :** Anderson - Vos initiales

	- **Téléphone professionnel :** 888 555-8855

	- **E-mail :** jean@sample.com

	- **Société :** Consolidated Sample - Vos initiales

	- **Rue 1 :** 219 91<sup data-htmlnode="">st</sup> Ave N

	- **Ville :** Seattle

	- **État/province :** WA

	- **Code postal :** 98001 

11. Cliquez sur le bouton **Enregistrer** dans la barre de commandes pour enregistrer le nouveau prospect et laissez-le ouvert.

12. Remarquez le flux des processus d’entreprise **prospect-opportunité** en haut de l’enregistrement. Cliquez sur la **phase de qualification** pour la sélectionner. Renseignez la phase comme suit :

	- **Période d’achat :** Ce trimestre

	- **Budget estimé :** 25 000  

	- **Processus d’achat :** Comité

	- **Identifier le décisionnaire :** Terminé

13. Cliquez sur le symbole **X** dans la fenêtre de la phase pour la fermer. 

14. Dans la **Chronologie des enregistrements** au milieu de l’écran, cliquez sur l’**icône de signe plus** pour ajouter une nouvelle activité. 

15. Dans le menu qui apparaît, sélectionnez **Appel téléphonique**.

16. Dans l’écran Création rapide d’appel téléphonique, renseignez l’appel téléphonique comme suit :

	- **Objet :** Appel de qualification initial - Vos initiales  

	- **Numéro de téléphone :** 888 555-8855

	- **Direction :** Sortant

	- **Description :** Conversation initiale avec Jean pour déterminer la qualification initiale. 

17. Cliquez sur le bouton **Enregistrer et fermer**.

18. Vous remarquerez que l’activité **Appel de qualification initiale** est maintenant affichée dans la **Chronologie des enregistrements**. Pointez sur l’activité et sélectionnez l’activité de fermeture **Icône de coche** pour marquer l’appel téléphonique comme terminé. 

19. Dans la fenêtre **Fermer un appel téléphonique**, vérifiez que l’état est défini sur **Terminé** et sélectionnez **Fermer**.

 

### Tâche 2 : Qualifier le prospect et le convertir en une opportunité en vue d’une qualification plus poussée

1. Dans la **Barre de commandes**, cliquez sur le bouton **Qualifier**. 

2. Lorsque le système qualifie le prospect, un enregistrement d’opportunité est créé et le processus d’entreprise avance à la phase **Développer**. Sélectionnez la phase **Qualifier** pour afficher l’enregistrement de prospect d’origine. 

3. Sélectionnez la phase **Développer** pour revenir à l’opportunité.

4. Cliquez sur le bouton **Enregistrer et fermer** pour fermer l’enregistrement d'opportunité créé. 

