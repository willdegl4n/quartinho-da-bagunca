# Crie uma aplicação Python online
### MySQL - Python

## Criar um repositorio no GIT

### crie dois arquivos ( cuidado com o nome dos arquivos )
```
touch app.py 
touch requirements.txt
```

### app.py
```
from flask import Flask
app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello, World!'
```

### requirements.txt ( Gunicorn + libs a ser importada)
```
Flask
Gunicorn
```

## Crie uma conta em onrender.com
### Crie um Web Services
![image](https://github.com/user-attachments/assets/260ff45f-4429-4ff0-bf6b-fb0259725577)




### Conecte na sua aplicação do github
![image](https://github.com/user-attachments/assets/eebbd76e-39d3-44b9-bbcf-9b6bff972eed)





### Faça a seguintes configurações

![image](https://github.com/user-attachments/assets/dd386fbe-fe85-424b-8671-f2335fca809e)

```
Python<br>
pip install -r requirements.txt
gunicorn app:app
```

### Acesse sua apliacação

![image](https://github.com/user-attachments/assets/fe5f616e-b29a-435b-958e-503380554a27)



### Fonte:

https://github.com/render-examples/flask-hello-world
