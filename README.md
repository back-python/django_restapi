# Construção de uma API utilizando Django Rest framework

![Lincença do projeto](	https://img.shields.io/github/license/robsonleal/pedroreceitas)
![Bagde status desenvolvimento](https://img.shields.io/static/v1?label=status&message=CONCLUÍDO&color=green)

## Índice

* [Título](#Título)
* [Badges](#badges)
* [Índice](#índice)
* [Descrição do Projeto](#descrição-do-projeto)
* [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
* [Acesso ao Projeto](#acesso-ao-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)

## Descrição do Projeto

Construção de API para cadastro de alunos e cursos de uma escola.

## Funcionalidades e Demonstração da Aplicação
- `Funcionalidade 1`: Cadastrar alunos e cursos;
- `Funcionalidade 2`: Realizar matricula dos alunos usando pk;
- `Funcionalidade 3`: Listar todos os alunos cadastrados em determinado curso ou listar todos os cursos de um determinado aluno;
- `Funcionalidade 4`: Modificar/Deletar alunos e cursos (PUT, PATCH, DELETE);
- `Funcionalidade 5`: Serializador para buscar os dados armazenados no DB e transformar em JSON;
- `Funcionalidade 6`: Basic authentication, para restringir o acesso aos dados;

Lista de todos os alunos:
![Screenshot_20220206_095014](https://user-images.githubusercontent.com/27708175/152682670-4f267959-8d47-44e3-8978-d73d32d23b0f.png)

Instância de um aluno:
![Screenshot_20220206_095110](https://user-images.githubusercontent.com/27708175/152682692-4aba0490-8e71-4f2e-982d-9365c1d1506a.png)

Lista de matrículas de um aluno:
![Screenshot_20220206_095231](https://user-images.githubusercontent.com/27708175/152682704-187c0206-bd61-41e5-8856-6642a37689fb.png)

## Acesso ao Projeto

```console
git clone git@github.com:robsonleal/django-restapi.git
cd django-restapi
python -m venv ./venv
source /<caminho_até_o_projeto>/venv/bin/activate
pip install 'requirements.txt'
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
- Abrir o endereço localhost:8000 no navegador de sua preferência;
- Autenticação é os dados do super usuário que foi criado.

## Tecnologias utilizadas
`Django 4`
`Python 3`
