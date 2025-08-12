# Sistema Acadêmico com Flask

Este é um projeto simples de um Sistema Acadêmico desenvolvido com o framework web Flask, utilizando Python. A aplicação permite o gerenciamento básico de alunos, disciplinas e notas.

## Funcionalidades

O sistema possui as seguintes funcionalidades:

- **Cadastro de Aluno**: Permite adicionar novos alunos ao sistema.
- **Cadastro de Disciplina**: Permite adicionar novas disciplinas.
- **Matrícula de Aluno**: Permite matricular um aluno em uma disciplina já cadastrada.
- **Cadastro de Notas**: Permite registrar até 4 notas para cada aluno em cada disciplina.
- **Relatório de Alunos**: Gera um relatório com as notas, média e status (Aprovado, Recuperação ou Reprovado) de cada aluno.
- **Zerar Dados**: Uma funcionalidade para limpar todos os dados do sistema, redefinindo as listas e dicionários para o estado inicial.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **Flask**: Framework web para construir a aplicação.
- **Jinja2**: Usado para renderizar os templates HTML.
- **HTML/CSS**: Para a estrutura e o estilo das páginas.

## Como Testar a Aplicação

Você pode testar a aplicação diretamente através do link abaixo. **Todos os dados são temporários** e são perdidos sempre que a aplicação é reiniciada.

- **URL da Aplicação Web:** [http://etieneteixeira.pythonanywhere.com/](http://etieneteixeira.pythonanywhere.com/)

## Estrutura do Projeto

A estrutura de pastas e arquivos do projeto é a seguinte:

mysite/
├── app.py              # Lógica principal da aplicação Flask
├── templates/
│   ├── index.html
│   ├── cadastrar_aluno.html
│   ├── cadastrar_disciplina.html
│   ├── matricular.html
│   ├── cadastrar_notas.html
│   └── listar_alunos.html
└── static/
└── python.jpg      # Arquivo de imagem para o plano de fundo
