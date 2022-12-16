# MyTeacher API
API desenvolvida com o framework Django durante um workshop da Treinaweb
#

### Criando e ativando virtualenv:

· Linux/MacOS
```bash
python -m venv .venv
```
```bash
source .venv/bin/activate
```

<br>

· Windows
```bash
python -m venv .venv
```
```bash
.\.venv\Script\activate
```

<br>

### Instalando o Django:
```bash
pip install django
```

<br>

### Instalando Django REST framework:
```bash
pip install djangorestframework
```

<br>

#### Instalando o CORS:
```bash
pip install django-cors-headers
```

<br>

### Executando migrations:
```bash
python .\manage.py migrate
```

<br>

### Populando o banco de dados manualmente:
1) Executar o shell do django
```bash
python .\manage.py shell
```

<br>

2) Importando model de Professor
```bash
from teacher.models import Professor
```

<br>

3) Gravando dados na tabela
```bash
Professor(nome="Nome Professor", valor_hora=50, descricao="Descrição", foto="url da imagem professor").save()
```

<br>

### Executando o projeto:
```bash
pyhton .\manage.py runserver
```
