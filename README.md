SVG_credit_scoring_model
            
            
                         I M P L E M E N T A T I O N   D'U N   M O D E L E   D E   S C O R E. 
                          (déploiement de la partie Dashboard dans le cloud avec Streamlit).



Pour accéder ainsi au Dashboard sur le cloud il suffit d'utiliser l'URL suivant:

https://sophievel3-svg-credit-p7-sofia-velasco-1-dashboard-cloud-49prj2.streamlit.app/

---------------------------------------------------------------------------------------------------------


On retrouve ici tous les fichiers pour:
- Déployer la partie dashboard dans le cloud avec Streamlit.

---------------------------------------------------------------------------------------------------------

INVENTAIRE DES FICHIERS PRESENTS:

1. P7_Sofia_Velasco_1_Dashboard --> Code utilisé pour faire le Dashboard sur Streamlit.

2. 6. requirements.txt --> packagings et leur versions utilisés dans notre code flask.


---------------------------------------------------------------------------------------------------------

ATTENTION:

Compte tenue du fait que Heroku est devenu payant depuis le 28 novembre 2022 (500 euros le mois max selon 
le temps d'utilisation de leur serveur, mais on ne spécifie pas vraiment comment ils prennent en compte ce 
temps d'utilisation), le service gratuit étant limité à:

- une mémoire maximum utilisable du serveur de 512Mb et
- à l'exécution de taches qui prennent moins de 30s;



J'ai dû, dans la version du 'Dashboard cloud' (code: "P7_Sofia_Velasco_1_Dashboard_Cloud.py" et 
URL:https://sophievel3-svg-credit-p7-sofia-velasco-1-dashboard-cloud-49prj2.streamlit.app/):

- faire les tests sur une base de données bien réduite (que quelques lignes et uniquement de la base test, 
  afin d'éviter les erreurs de mémoire, erreur H12).
           --> Vous pouvez donc tester avec le ID: 100005 par exemple ou n'importe quel ID du fichier zippé 
               'base_test' disponible dans le repository 'SVG_credit_scoring_model_Flask'.


- lier le dashboard Streamlit, aux URL qui ne nécessitaient pas de chercher dans la base d'un client 
  spécifique. 
  En fait, même en réduisant énormément la base, cette tache prend plus de 30s à se faire sur leur serveur 
  et du coup elle génère un crash. Suite à en avoir discuté avec ma mentor, on a décidé donc de faire ainsi 
  dans le but de montrer que je sais bien lier un dashboard "Streamlit", à une app "Flask" mise dans le 
  cloud avec Heroku, comme il est demandé dans ce projet. Ce sachant bien sûr qur faisant tourner et l'app 
  Flask et le dashboard Streamlit en local, tout marche correctement et avec la base complète. 
  (cf. Repository: 'SVG_credit_scoring_model_Dashboard_Local').


Vous trouverez ici, tous les documents nécessaires pour faire tourner le dashboard sur le cloud avec Streamlit
(ie. l'adaption du code "P7_Sofia_Velasco_1_Dashboard_Cloud.py", afin de le lier aux liens décrits auparavant).