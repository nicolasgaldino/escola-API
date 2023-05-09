# Instalação e configuração do ambiente

## Pré-requisitos

- Python 3.8 ou superior

## Instalação

1. Clone o repositório:

```
git clone https://github.com/nicolasgaldino/escola-API.git
```

2. Crie um ambiente virtual:

```
python -m venv nome-do-ambiente
```

3. Ative o ambiente virtual:

```
source nome-do-ambiente/bin/activate  # Linux/MacOS
nome-do-ambiente\Scripts\activate  # Windows
```

4. Instale as dependências:

```
pip install -r requirements.txt
```

## Dependências

As seguintes dependências foram utilizadas na versão atual do projeto:

| Dependência                | Versão    |
|----------------------------|-----------|
| asgiref                    | 3.3.1     |
| Django                     | 3.1.3     |
| djangorestframework        | 3.12.2    |
| Faker                      | 4.14.2    |
| mypy                       | 1.2.0     |
| mypy-extensions            | 1.0.0     |
| python-dateutil            | 2.8.1     |
| pytz                       | 2020.4    |
| six                        | 1.15.0    |
| sqlparse                   | 0.4.1     |
| text-unicode               | 1.3       |
| tomli                      | 2.0.1     |
| typing_extensions          | 4.5.0     |
| validate-docbr             | 1.8.2     |

## Inicializando o Projeto

Depois de instalar as dependências, você deve executar os seguintes comandos no terminal para ativar o servidor local:

1. Acesse a pasta raiz do seu projeto Django:

```
cd /caminho/para/o/projeto
```

2. Execute o seguinte comando para rodar as migrações do banco de dados:

```
python manage.py migrate
```

3. Por fim, execute o comando para iniciar o servidor local:

```
python manage.py runserver
```

Pronto! O servidor local estará rodando na porta 8000 por padrão.
Acesse o seu navegador e digite "<http://localhost:8000>" para visualizar a sua aplicação.
