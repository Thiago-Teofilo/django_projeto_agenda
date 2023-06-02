# Iniciar um projeto Django
python -m venv venv
. venv/bin/activate
pip install django
django-admin startproject project .
python manage.py startapp contact

# Configure o .gitignore

# Configurar o git (Apenas na primeira vez)
git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
git init
git remote add origin URL_DO_GIT

# Atualizar o repositório 
git add .
git commit -m 'Mensagem'
git push origin main
