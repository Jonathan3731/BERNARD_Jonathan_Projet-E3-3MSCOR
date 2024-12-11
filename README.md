# BERNARD_Jonathan_Projet-E3-3MSCOR
Repository de BERNARD Jonathan pour le Projet E3 3MSCOR

Outils que j'ai utilisé

![Capture d'écran 2024-12-11 095925](https://github.com/user-attachments/assets/4bde3793-7173-4829-ab28-c7ba7281210e)

Téléchargement des applications

![Capture d'écran 2024-12-11 100000](https://github.com/user-attachments/assets/d55d561d-788e-492d-ab01-31064d5b90dd)
![Capture d'écran 2024-12-11 100011](https://github.com/user-attachments/assets/4645eb78-cc07-459a-a0ee-acbd15e3f292)
![Capture d'écran 2024-12-11 100027](https://github.com/user-attachments/assets/c309497a-441f-457e-a684-cba52e465caa)
![Capture d'écran 2024-12-11 100043](https://github.com/user-attachments/assets/b5fd7718-6793-4056-9a4a-b4862977f5a7)
![Capture d'écran 2024-12-11 100103](https://github.com/user-attachments/assets/89476c5d-aa28-426e-b09a-631d3dcf1dc2)
![Capture d'écran 2024-12-11 100142](https://github.com/user-attachments/assets/beaf1672-98cc-4546-99fd-75d3b94feb12)

Téléchargement du site HTML

![Capture d'écran 2024-12-11 095801](https://github.com/user-attachments/assets/7f76ab05-01d3-43fb-a3b0-003391fbaa01)

J’ai supprimé le fichier docker-compose et le dossier nginx de chaque application pour n’en garder qu’un seul de chaque. Le docker-compose permettra de déployer toutes les applications en une commande et le nginx permettra de réunir toutes les applications derrière un 
seul reverse proxy.

![Capture d'écran 2024-12-11 100819](https://github.com/user-attachments/assets/a3346a6a-ae22-4abe-b774-d9c333fd304f)

Finalisation du docker-compose :  
Lignes du Docker compose pour toutes les applications

![Capture d'écran 2024-12-11 103144](https://github.com/user-attachments/assets/92d3e4ed-bc9d-4b63-a5f1-4e0dc7a6e71b)

Lignes pour NGINX :

![image](https://github.com/user-attachments/assets/415e8d51-eb25-4600-a41a-b1e2a679ae14)

Optimisation des Dockerfile :

![Capture d'écran 2024-12-11 101210](https://github.com/user-attachments/assets/669b72d2-381a-44e4-b911-b57d54fd4c39)

Dockerfile de l'application HTML :

![image](https://github.com/user-attachments/assets/04ef877b-a230-409f-b5d3-f671e83afa9c)

Modification du dossier de l’application HTML en conséquence, je mets aussi le dossier HTML dans le dossier nginx pour faciliter son déploiement et son accès. Pour mon application HTML il suffit juste de prendre une image NGINX optimisé, copier les fichiers HTML dans le dossier NGINX du container pour que l'application fonctionne.

![image](https://github.com/user-attachments/assets/1d776a03-8a03-48e2-ae7e-10ff521c0b0f)

