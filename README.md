# Silver Pen

TODO...

## Dependências

Antes de tudo é recomendado utilizar um ambiente virtual com `venv` para evitar conflito de dependências.

```sh
python -m venv venv
source venv/bin/activate
```

Instalar o Django

```sh
python -m pip install -r requirements
```

## Como executar

Caso seja a primeira vez é necessário gerar as `migrations`:

```sh
python TODO_list_app/manage.py makemigrations
```

E criar o banco de dados (por padrão um sqlite):

```sh
python TODO_list_app/manage.py migrate
```

Aí então iniciar o servidor:

```sh
python TODO_list_app/manage.py runsever
```

