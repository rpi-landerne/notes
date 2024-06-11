# Séance du 11 Juin 2024

### Exercice 1
```py
from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def bonjour():
    return "Bonjour le Monde !"

if __name__ == '__main__':
    app.run(debug=True)
```
