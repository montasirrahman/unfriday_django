

# Create Virtual ENV - BASH
pip install virtualenv
virtualenv env
source ./env/bin/activate

deactivate



# Install django
pip install django

django-admin startproject frontend


# git & github
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/montasirrahman/unfriday_django.git
git push -u origin master

