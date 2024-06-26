# Installation

Clonez le dépôt du projet depuis GitHub :

    git clone https://github.com/Nadaaeee/Django_TP.git

Accédez au répertoire du projet :

    cd projet search

Créez un environnement virtuel Python :

    python3 -m venv .venv

Activez l'environnement virtuel sur Windows :

    .venv\Scripts\activate


Installez les dépendances du projet :

    pip3 install -r requirements.txt

# Configuration

Effectuez les migrations de la base de données :

    python3 manage.py migrate

Créez un superutilisateur pour s'authentifier à l'application :

    python3 manage.py createsuperuser

Lancez le serveur de développement :

    python3 manage.py runserver

L'application devrait maintenant être accessible à l'adresse http://localhost:8000.

Une page de login devrait s'afficher dans un premier temps, les identifiants de connexion correspondent au superutilisateur créé précédemment.
