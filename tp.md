## TP Docker - Docker compose - Jenkins

#### Pour Ce TP, vous aller en vous basant sur ce projet :

 - Créer un dockerfile du projet.
 - Créer un docker compose avec un accés à une bdd postgreSql.
 - Vous allez automatiser les phases de developpement et deploiement du projet :
   - Créer un nouveau serveur Jenkins et le configurer. 
   - Etape 1: Récupération du projet sur votre propre dépot git de manière sécurisée avec des identifiants.
   - Etape 2: Effectuer la phase de build.
   - Etape 3: Effectuer une vérification de la qualité de votre code.
   - Etape 4: Créer une image du projet avec un tag unique et dynamiquement evolutif en fonction du build effectué.
   - Etape 5: Envoyer cette image dans un docker registry comme dockerhub.
   - Etape 6: Récupérer cette image dans votre docker compose.
   - Etape 7: Executer le docker compose dans votre serveur ubuntu et vérifier que l'application fonctionne.


