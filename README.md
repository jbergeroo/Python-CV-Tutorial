# Python-CV-Tutorial

Dans ce tutoriel, nous allons nous familiariser avec les bibliothèques de base de Python que l'on utilise dans le monde de la Computer Vision. Nous allons donc voir Numpy, Open-CV, Matplotlib, Pillow et Torch. Pour cela, nous allons suivre une série de notebook afin de nous familiariser avec ces librairies.

## Configuration de l'environnement

Nous supposons que vous avez quand même certaines bases et que vous n'êtes pas totalement débutant sur Python. Nous supposons alors que vous avez Python installé sur votre ordinateur et que vous savez manier les notebooks. 

Vous allez pouvoir télécharger ce dossier sur votre ordinateur. Vous allez créer un environnement virtuel python que vous utiliserez pour les notebooks suivants.

Dans l'invitation de commande, lorsque vous êtes placés dans le dossier actuel vous allez créer l'environnement virtuel ```.env``` avec la commande suivante.
```bash
python -m venv .env
```

Afin de l'activer, utilisez cela
```bash
.env\Scripts\activate (sur Windows)
source .env/bin/activate (sur MacOS ou Linus)
```

Dans chaque notebook du tutoriel, vous aurez sûrement une ou plusieurs librairies à installer. Vous devrez alors activer votre environnnement virtuel et lancer la commande indiquée. Lorsque vous utilisez un notebook, n'oubliez pas de sélectionner l'environnement que vous avez créer.