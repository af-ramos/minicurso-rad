# Setup at Windows 10

## Environment setup

Instale o Git utilizando o seguinte link: https://git-scm.com/

Instale o Python utilizando o seguinte link: https://www.python.org/

**OBS:** O Miniconda/Anaconda não foi utilizado por mim.

## Python setup

Para definir um virtual environment para os pacotes do Python é necessário rodar esses comandos:
```bat
python -m venv venv
.\venv\Scripts\activate
```

Para fazer as instalações dos pacotes, vamos utilizar os seguintes comandos:
```bat
pip install -r dev-requirements.txt
```