# Integration-IA-In-App
Le modèle a été entrainé dans Google Colab.
#Comment ça marche :
!git clone https://github.com/Bachir-Bouhafs/Integration-IA-In-App.git
Pour démarrer le processus d'apprentissage, un dossier nommé training_dataset doit être créé à la racine du dossier du projet dans colab.
!bash /content/Integration-IA-In-App/train.sh
!python /content/Integration-IA-In-App/classify.py
!pip install flask-ngrok
!python /content/Integration-IA-In-App/application.py

PS: pour tester une image il faut la rajouter dans ./Integration-IA-In-App/static/images/


