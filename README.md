<p align="center" <a href="" target="_blank" rel="noreferrer"><img src="https://www.startpage.com/av/proxy-image?piurl=https%3A%2F%2Fwww.python.org%2Fstatic%2Fcommunity_logos%2Fpython-logo-master-v3-TM.png&sp=1678450408T4e2eae9177a1d48c962869bcfa7ae8c5f16b84722f382e576e60601b8ecd2605"></a>>
</p>

<h3 align="center">

Bienvenue ! Vous trouverez ici le Projet 4 du parcours<a href="https://openclassrooms.com/fr/paths/518-developpeur-dapplication-python" target="_blank" rel="noreferrer"> Développeur d'application - Python</a> 👋

</h3>

<h2 align="center">

# Développez un programme logiciel en Python 💻 !

</h2>

> [!Scénario] 
> ###  

Vous êtes un développeur junior depuis deux mois et vous travaillez en freelance pour écrire des scripts simples afin d’aider les petites entreprises locales à gérer leur inventaire. 

Elie, votre amie et elle aussi développeuse Python, est membre du club d'échecs local. Elle vous a expliqué que les tournois du club sont actuellement organisés à la main, mais que les membres du club aimeraient pouvoir les gérer avec un logiciel. Le club avait trouvé une application convenable, mais elle avait besoin d’une connexion Internet – qui n'est pas disponible pour tous les tournois – et l'abonnement mensuel était trop cher.

<p align="center" <a href="" class="oc-imageLink oc-imageLink--disabled"><img src="https://user.oc-static.com/upload/2020/09/22/16007793690358_chess%20club-01.png" alt="Logo du club d'échecs"></a>>
</p>


</br>

- 💬 Vous suggérez que vous pourriez écrire un outil qui permette de gérer les tournois pour aider le club, mais qui fonctionne hors ligne. Elie aime bien votre idée et elle dit qu'elle en discutera la prochaine fois qu'elle se rendra au club. Comme elle s’occupe déjà de plusieurs contrats en freelance, elle accepte de vous recommander comme candidat idéal pour développer cette application.

> [!Livrables attendus 🔭 ] 
> ##   

-   Le code de l'application, tel que prescrit dans la spécification technique ;
-   Un répertoire contenant un fichier HTML, généré par **flake8-html**, ne montrant aucune erreur de peluchage dans le code ;
-   Un fichier **README.md** contenant des instructions claires sur la manière d'exécuter le programme, de l'utiliser et de générer un nouveau fichier flake8-html.

</br>

> [!note] 
> Structure de dossiers du projet  

```
├── controllers
│   ├── __init__.py
│   ├── tournoi.py
│   ├── rapports.py
│   └── menu.py
├── models
│   ├── __init__.py
│   ├── tournoi.py
│   ├── round.py
│   └── joueur.py
└── views
    ├── __init__.py
    ├── round.py
    ├── rapports.py
    └── menu.py

```

Les fichiers `__init__.py sont nécessaires pour que Python reconnaisse le dossier comme un module.

Dans le dossier `controllers`, vous pouvez placer tous les fichiers contenant la logique de contrôle, tels que la gestion des tournois, la génération de rapports et le menu principal.

Le dossier `models` peut contenir les modèles pour les entités dans votre programme, tels que les tournois, les rondes et les joueurs.

Le dossier `views` peut contenir tous les fichiers qui concernent l'interface utilisateur, tels que les vues pour les rondes, les rapports et le menu principal.


