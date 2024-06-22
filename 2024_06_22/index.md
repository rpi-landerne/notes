## Séance du 22 Juin 2024

### Exercice 1 :
```sh
# Création d'un répertoire
mkdir test_flask
# Déplacement dans ce dernier
cd test_flask
# Création d'un Environnement Virtuel Python
python -m venv .venv
# Activation de l'Environnement Virtuel Python
source .venv/bin/activate
# Installation du Framework Flask
pip install flask
```
```py
from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def bonjour():
    return 'Bonjour, le Monde!'

if __name__ == '__main__':
    app.run(debug=True)
```
- A présent nous pouvons executer notre script Python :
```sh
python flask_bonjour.py
```

### Exercice 2 :
```py

```

### Exercice 3 :
```py

```

### Exercice 4 :
```py

```
