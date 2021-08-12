---
lab:
    title: 'Labo 3.3 : Laboratoire Capstone Dynamics 365 Customer Service'
    module: 'Module 3 : Découvrir les principes fondamentaux de Dynamics 365 Customer Service'
---

Module 3 : Découvrir les principes fondamentaux de Dynamics 365 Customer Service
========================

## Labo pratique 3.3 - Laboratoire Capstone Dynamics 365 Customer Service

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

Il arrive souvent que les clients rencontrent des problèmes avec leur équipement. Dans ce cas, les problèmes sont signalés au support technique de la société ABC. Les problèmes peuvent être signalés de différentes manières. Dans certains cas, l’équipement peut signaler les problèmes de manière proactive. Lorsque des problèmes sont signalés, les agents tentent de les résoudre à distance. S’ils échouent, un technicien de terrain est dépêché sur place pour résoudre le problème. Vous avez récemment réparé un grand nombre de capteurs qui avaient cessé de fonctionner. Vous avez remarqué que le problème était dû à un bogue logiciel. Vous souhaitez créer un article de Base de connaissances pour que les autres agents puissent s’y référer lorsqu’ils rencontrent le même problème. 

En tant qu’agent du support technique, vous êtes responsable de la résolution des problèmes signalés par les clients. Vous avez récemment reçu un appel de Piper Smith. Piper signale que l’un des capteurs de son système ne fonctionne pas. Vous devez enregistrer l’appel de Piper et tenter de trouver une solution à son problème. 

À l’issue de ce labo, vous aurez réalisé les opérations suivantes :

- Création d’un article de Base de connaissances 

- Gestion des incidents à l’aide du Concentrateur de service client

- Création et enregistrement d’un incident 

- Gestion d’un enregistrement d’incident tout au long de son cycle de vie. 

## Configuration du labo

  - **Durée estimée **: 45 minutes

## Instructions

## Exercice 1 : Créer et publier un article de Base de connaissances

### Tâche 1 : Créer un article de Base de connaissances

1. Ouvrez l’application **Concentrateur du service client Dynamics 365** si elle n’est pas déjà ouverte. 

2. Dans le volet de navigation de gauche, sélectionnez ** Articles de la Base de connaissances **. 

3. Pour voir rapidement quels articles sont dans différentes phases, sélectionnez la flèche déroulante à côté de **Mes articles actifs**. 

4. Sélectionnez **Brouillons d’article**. 

5. Utilisez le sélecteur de vue pour sélectionner **Articles approuvés**.  

6. Utilisez le sélecteur de vue pour revenir à **Mes articles actifs**

7. Dans la **Barre de commandes**, cliquez sur le bouton **Nouveau**. Une fois que le nouvel enregistrement est ouvert, sélectionnez la flèche déroulante à côté du champ **Raison de l’état** dans l’en-tête de l’enregistrement en haut. Définissez **Langue** sur **Français - France**.

8. Renseignez l’article comme suit :

	- **Titre :** Capteur hors service - Vos initiales

	- **Mots clés :** Capteur, endommagé, ne fonctionne pas

	- **Description :** Résoudre les cas de dysfonctionnement d’un capteur. 

9. Entrez le texte suivant dans le texte du **Concepteur de contenu** :   

	Capteur actuellement hors service

	Si un capteur ne fonctionne pas comme prévu, procédez comme suit :

	1. Localisez et remplacez les piles de l’appareil. 

	2. Maintenez le bouton d’alimentation enfoncé pendant 3 secondes. 

	3. L’appareil s’ouvre en mode administrateur. 

	4. Maintenez le bouton d’appairage enfoncé jusqu’à ce que le voyant passe du rouge au bleu. 

	5. Appuyez sur le bouton Réinitialiser. 

	Une fois qu’il aura redémarré, l’appareil sera de nouveau en ligne. 

10. Dans l’éditeur de contenu, sélectionnez le texte Capteur actuellement hors service

11. Modifiez la taille de caractère en **22** et sélectionnez le bouton **Gras**. 

12. Dans la **Barre de commandes**, sélectionnez le bouton **Enregistrer** pour enregistrer l’article de la Base de connaissances et laissez-le ouvert. 

13. Dans **Nouveau processus**, sélectionnez la phase **Auteur**, définissez le champ **Sujet de l’article** sur **Service**. 

14. Définissez le champ **Marquer pour révision** sur **Terminé**.

15. Cliquez sur le bouton **Phase suivante** pour passer à la phase **Réviser**.

16. Dans la **Barre de commandes**, sélectionnez le bouton **Enregistrer et fermer** pour enregistrer et fermer l’article.

 

### Tâche 2 : Gérer un article tout au long du processus d’approbation

Dans la plupart des organisations, une fois que l’auteur a créé l’article initial, ce dernier passe généralement par un processus d’approbation avant sa mise en ligne. Cette tâche est généralement effectuée par un individu différent. Dans cette instance, nous allons endosser le rôle d’approbateur. 

1. Dans les articles de la Base de connaissances, basculez sur la vue **Articles proposés** pour voir les articles qui ont besoin de votre approbation. 

2. Ouvrez l’article **Capteur hors service - Vos initiales** que vous venez de créer.

3. Dans **Nouveau processus**, sélectionnez la phase **Réviser**. Définissez le champ **Réviser** sur **Rejeté**.

4. Dans l’écran Rejeter l’article de base de connaissances, entrez le texte **Cette procédure ne fonctionne pas lorsque je tente de la répliquer**.

5. Sélectionnez le bouton **Rejeter**

6. Cliquez sur le bouton **Enregistrer et fermer** pour fermer l’enregistrement d’article.

7. Utilisez le **Sélecteur de vue** pour revenir à **Mes articles actifs**. 

8. Ouvrez l’enregistrement **Capteur hors service - Vos initiales**.

9. Une fois que l’enregistrement est ouvert, sélectionnez l’onglet **Résumé**. 

10. Dans l’enregistrement **Chronologie**, remarquez la note indiquant que l’article a été rejeté et les raisons de ce rejet. 

11. Sélectionnez l’onglet **Contenu**

12. Dans le champ **Contenu**, placez votre curseur avant le mot **Appuyer** à l’Étape 5. 

13. Appuyez sur la touche **Entrée**. 

14. Entrez le texte « Appuyez sur le bouton Confirmer ». 

15. Dans la **Barre de commandes**, sélectionnez le bouton **Enregistrer et fermer**.

16. Utilisez le **Sélecteur de vue** et basculez sur la vue **Articles proposés**.

17. Ouvrez l’article **Capteur hors service - Vos initiales**. 

18. Dans le flux de processus d’entreprise **Nouveau processus**, sélectionnez la phase **Réviser**.

19. Modifiez le statut sur **Approuvé**. 

20. Il vous sera demandé de confirmer l’approbation de l’article. Cliquez sur **OK**. 


### Tâche 3 : Approuver l’article de la Base de connaissances

Maintenant que l’article a été approuvé, nous allons le publier pour le mettre à disposition des personnes travaillant sur les incidents. 

1. Appuyez sur le bouton **Phase suivante** pour passer à la phase **Publier**. 

2. Marquez **Définir les associations de produits** comme étant **terminées**. 

3. Définissez la **Date d’expiration** sur **une année à compter de ce jour à 00h00**. 

4. Sélectionnez le bouton **Terminer** pour terminer le processus. 

5. Dans la **Barre de commandes** de l’article, sélectionnez le bouton **Publier**. 

6. Vérifiez que les champs suivants sont sélectionnés :

	- **Publier :** Maintenant

	- **État de publication :** Publié

	- **Date d’expiration :** Une année à compter de ce jour à 00h00

	- **État d’expiration :** Expiré

	- **Statut d’expiration :** Expiré

7. Sélectionnez le bouton **Publier** pour publier l’article.


## Exercice 2 : Gérer un incident de support tout au long de son cycle de vie


### Tâche 1 : Créer et gérer un incident

1. Ouvrez l’application **Concentrateur du service client Dynamics 365** si elle n’est pas déjà ouverte. 

2. Dans le volet de navigation de gauche, sélectionnez ** Tableaux de bord**. Le tableau de bord de **niveau 1** s’ouvre. 

3. Dans la **Barre de commandes**, sélectionnez le bouton **Afficher le filtre visuel**.


4. Des tableaux de bord supplémentaires fournissent des détails sur la charge d’incidents actuelle. Vous pouvez utiliser d’autres tableaux de bord à l’aide du sélecteur de tableaux de bord. Modifiez le tableau de bord de **Tableau de bord de niveau 1** en **Tableau de bord de niveau 2**. 

 

Maintenant que vous êtes familiarisé avec quelques vues et tableaux de bord, nous allons créer un nouvel enregistrement d’incident pour résoudre le problème de Piper.

 

10. Dans le volet de navigation de gauche, sélectionnez ** Incidents**. 

11. Dans la **Barre de commandes**, sélectionnez le bouton **Nouveau** pour créer un nouvel enregistrement d’incident.

12. Complétez votre nouvel enregistrement d’incident comme suit :

	- **Titre de l’incident :** Capteur hors service - Vos initiales

	- **Client :** Piper Smith

	- **Origine :** Téléphone

	- **Description :** Piper signale que l’un des capteurs reçus ne fonctionne pas correctement. 

13. Sélectionnez le bouton **Enregistrer** pour enregistrer l’enregistrement et laissez-le ouvert. 

14. À l’aide de la **Chronologie des enregistrements**, sélectionnez l’**icône de signe Plus** pour créer une nouvelle activité. 

15. Dans le menu qui apparaît, sélectionnez **Appel téléphonique**.

16. Dans le formulaire **Création rapide : Appel téléphonique**, remplissez l’activité comme suit :

	- **Objet :** Retourner l’appel de Piper

	- **Direction :** Sortant

	- **Numéro de téléphone :**  888 555-1762

	- **Durée :** 15 minutes.

17. Sélectionnez le bouton **Enregistrer et fermer**. 

18. Dans **Processus téléphone-incident**, sélectionnez la phase **Identifier**.

19. Appuyez sur le bouton **Phase suivante** pour passer à la phase **Rechercher**. 

20. Sélectionnez le symbole **X** dans la fenêtre de la phase **Rechercher** pour la fermer et pouvoir continuer à travailler. 

21. À l’aide de la **Chronologie des enregistrements**, sélectionnez l’**icône de signe Plus** pour créer une nouvelle activité. 

22. Dans le menu qui s’affiche, sélectionnez **Tâche**.

23. Dans le formulaire **Création rapide : Appel téléphonique**, remplissez l’activité comme suit :

	- **Objet :** Mener des recherches sur le problème de Piper

	- **Description :** Exploiter la Base de connaissances pour résoudre le problème de Piper. 

	- **Durée :** 30 minutes.

24. Sélectionnez le bouton **Enregistrer et fermer**. 

25. Sur le côté droit de l’écran des incidents, localisez et sélectionnez l’icône représentant un livre **Base de connaissances**. (Elle se trouve directement sous l’icône représentant une clé anglaise).

26. Notez que le titre de l’incident est automatiquement utilisé en tant que texte de recherche. Localisez et sélectionnez l’article **Capteur hors service - Vos initiales** que vous avez créé précédemment. 

27. Le contenu complet de l’article s’affiche. Sélectionnez l’icône **Avis positif** au bas de l’article pour indiquer que l’article était utile. 

28. Sélectionnez l’icône **Lier cet article à l’enregistrement actuel**. Vérifiez que le texte **Lié à l’incident** apparaît. 

 

### Tâche 2 : Fermer l’incident

Maintenant que nous avons identifié une solution pour le problème du client, nous sommes prêts à résoudre l’incident. La première étape de clôture d’un incident consiste à fermer toutes les activités ouvertes qui y étaient associées. 

1. Dans l’enregistrement d’incident **Chronologie**, survolez la tâche **Mener des recherches sur le problème de Piper** que vous avez créée précédemment**.** Sélectionnez Marquer comme terminé (**icône de coche**) pour terminer l’activité. 

2. Dans l’écran **Fermer la tâche**, vérifiez que l’état est défini sur Terminé et sélectionnez le bouton **Fermer**. Le statut de la tâche devrait indiquer **Fermé**. 

3. Survolez **Appel téléphonique - Retourner l’appel de Piper** que vous avez créé précédemment**.** Sélectionnez Marquer comme terminé (**icône de coche**) pour terminer l’activité. 

4. Dans l’écran **Fermer un appel téléphonique**, vérifiez que l’**État** est défini sur **Terminé** et que le **Statut** est **Effectué**. Sélectionnez le bouton **Fermer**. Vérifiez que l’activité s’affiche comme fermée dans la Chronologie. 

5. Dans **Processus téléphone-incident**, sélectionnez la phase **Rechercher** et sélectionnez **Phase suivante** pour passer à la phase **Résoudre**. 

6. Dans la phase **Résoudre**, sélectionnez le bouton **Terminer** pour terminer le flux du processus. 

7. Dans la **Barre de commandes** de l’enregistrement d’incident, sélectionnez le bouton **Résoudre l’indicent**.

8. Dans la fenêtre **Résoudre l’incident**, définissez le champ **Résolution** sur **Article de la Base de connaissances**. 

9. Vérifiez que les champs **Durée totale** et **Durée à facturer** sont définis sur **45 minutes** (Ce chiffre représente la durée totale consacrée à la fois aux activités Appel téléphonique+Tâche et ajoutée à l’enregistrement.) 

10. Sélectionnez le bouton **Résoudre** pour terminer le processus. 

