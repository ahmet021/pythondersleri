
**Pip ve virtualenv kurulumu**

    sudo apt-get install python-pip python-dev build-essential
    sudo apt-get install python-pip
    sudo pip install --upgrade pip
    sudo pip install --upgrade virtualenv

**Migrationların yapılması ve Projenin çalıştırılması**

    cd django-101/
    python manage.py migrate
    python manage.py runserver
