# LAB-2
Etape 1:
Cette étape consiste à initialiser un dépôt Git afin de permettre le suivi des versions du code, des configurations et de la structure du projet. Git est utilisé comme outil de contrôle de version pour assurer la traçabilité et la reproductibilité des modifications.
<img width="940" height="137" alt="image" src="https://github.com/user-attachments/assets/1e5867b8-1a87-405d-8564-d256a3370d1a" />
<img width="940" height="92" alt="image" src="https://github.com/user-attachments/assets/94f585ca-c9c6-4f49-8603-e0a5f5ef2c35" />
 
<img width="860" height="302" alt="image" src="https://github.com/user-attachments/assets/89424610-5640-4702-b3c8-c375cf3c4cb1" />
 
 
Etape 2:
Dans cette étape, les dossiers et fichiers principaux du projet (code source, données, registry et configuration Git) sont ajoutés à l’index Git puis enregistrés dans un premier commit. Ce commit représente l’état initial stable du projet et sert de point de référence pour les évolutions futures.
<img width="940" height="369" alt="image" src="https://github.com/user-attachments/assets/34a4c428-e762-4f26-9a88-49adc978d716" />
 
 <img width="940" height="98" alt="image" src="https://github.com/user-attachments/assets/a75994f2-8179-4301-a552-2bcb4e394d64" />

Etape 3:
Cette étape permet d’observer les changements effectués dans un fichier par rapport au dernier commit. 
Une modification du paramètre z_threshold est réalisée, puis les différences sont analysées avant et après l’ajout du fichier à l’index. Cela illustre le mécanisme de comparaison et de staging dans Git.

<img width="940" height="342" alt="image" src="https://github.com/user-attachments/assets/a8b26d67-77fb-4a2a-931c-800ff5bf7772" />

<img width="940" height="62" alt="image" src="https://github.com/user-attachments/assets/29c00e13-09fc-42d9-a83b-fbdad029fb96" />
<img width="940" height="337" alt="image" src="https://github.com/user-attachments/assets/723e2003-273f-4cd7-93a8-13581b4360d4" />

 <img width="940" height="137" alt="image" src="https://github.com/user-attachments/assets/e24a16d4-b44b-48f2-b6bd-86ad51eb5cc0" />

 
Etape 4
Une branche dédiée à une nouvelle fonctionnalité est créée afin d’isoler les modifications du code principal. La gestion automatique du request_id est ajoutée à l’API, puis les changements sont validés par un commit.
<img width="940" height="144" alt="image" src="https://github.com/user-attachments/assets/83f63bf1-78f2-48f8-9ae6-7f1c75cec59a" />
<img width="940" height="444" alt="image" src="https://github.com/user-attachments/assets/59116b55-f96e-4d54-956a-73f8409c0976" />

 
Etape 5
Une branche dédiée à une nouvelle fonctionnalité est créée afin d’isoler les modifications du code principal. La gestion automatique du request_id est ajoutée à l’API, puis les changements sont validés par un commit.
<img width="940" height="283" alt="image" src="https://github.com/user-attachments/assets/5234c0e6-1302-4879-aa8b-a8af853c95bb" />
 
Etape 6
Cette étape démontre la gestion des conflits Git lorsqu’une même ligne de code est modifiée dans deux branches différentes. Après la tentative de fusion, le conflit est résolu manuellement en choisissant une valeur finale cohérente 0.7, puis un commit de résolution est effectué.
<img width="940" height="202" alt="image" src="https://github.com/user-attachments/assets/8ca39402-680f-484d-8e31-80a23798f427" />


 
Etape 7:
La commande git stash a été utilisée pour sauvegarder temporairement une modification non committée sur le fichier rollback.py. Le dépôt a ainsi été nettoyé, permettant de poursuivre le travail sans perdre les changements en cours. Les modifications ont ensuite été récupérées depuis le stash.
 <img width="844" height="718" alt="image" src="https://github.com/user-attachments/assets/39d09c14-6a77-43b7-8488-1b04112074e7" />

 <img width="940" height="110" alt="image" src="https://github.com/user-attachments/assets/261a11f1-327e-4ec2-b4bc-972c6e7f1480" />

<img width="940" height="215" alt="image" src="https://github.com/user-attachments/assets/e24b2bf2-4a87-4592-87d9-09d080b00921" />

<img width="940" height="329" alt="image" src="https://github.com/user-attachments/assets/fc6e3a2f-6de0-4ac2-98c1-4703523f6006" />
 
Etape 8:
Cette étape a permis d’explorer le comportement de la commande git reset selon ses différents modes. Le mode --soft a supprimé un commit tout en conservant les modifications dans l’index, le mode mixed a conservé uniquement les modifications dans le répertoire de travail, et le mode --hard a supprimé définitivement les commits ainsi que les changements locaux. 
<img width="678" height="554" alt="image" src="https://github.com/user-attachments/assets/791dfafd-cf64-40a0-9b07-72f6f20224ff" />

<img width="650" height="696" alt="image" src="https://github.com/user-attachments/assets/547bbdc9-161c-4dbb-8b82-5a2ea232777b" />

Etape 9:
Cette étape a permis d’annuler un commit indésirable sans modifier l’historique Git. Après avoir ajouté un changement volontairement erroné, nous avons utilisé git revert HEAD, ce qui a créé un nouveau commit inversant exactement les modifications précédentes. Cette méthode conserve la traçabilité et est recommandée en production pour corriger des erreurs.
<img width="940" height="254" alt="image" src="https://github.com/user-attachments/assets/2ec29cbf-e19e-4dcd-95c0-a7fd99553c23" />
 
Etape 10:
Cette étape a permis de rebaser une branche de fonctionnalité sur la branche principale afin de l’aligner avec les derniers commits de master. La commande git rebase master applique les commits de la branche feature sur la base la plus récente de master, ce qui réécrit l’historique et évite la création de merge commits inutiles. 
<img width="940" height="235" alt="image" src="https://github.com/user-attachments/assets/65e44e30-4cb8-4c2b-94bd-c053ca576710" />
<img width="940" height="790" alt="image" src="https://github.com/user-attachments/assets/503f7c9c-52e2-4a71-8995-e4ac81da5ff4" />







