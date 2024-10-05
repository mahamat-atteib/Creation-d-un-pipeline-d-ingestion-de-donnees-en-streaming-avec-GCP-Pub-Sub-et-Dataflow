# Pipeline d'ingestion de donnes depuis une-machine-locale-vers-le-stockage-GCP



## 1. Création de Pub/Sub sur GCP

Pour créer un sujet Pub/Sub et publier des messages (unités de données), vous devez vous authentifier sur GCP, créer un compte de service, télécharger la clé associée, et configurer le SDK et la CLI. 

Par la suite, il faut créer un topic pour communiquer des messages sur Pub/Sub. Nous créons un sujet nommé "gcp-yelp-bigdata". Une fois le sujet créé, une souscription (gcp-yelp-bigdata-sub) est également générée. Cette souscription permet à une application de recevoir et traiter les messages provenant d'un sujet Pub/Sub spécifique.

![image](https://github.com/user-attachments/assets/fbe2c707-d20a-4040-bc07-4ac1e6da0fd4)


