# Aprenda Git - Versão via GitHub Classroom

Uma breve introdução aos conceitos básicos de Git, com uma linguagem simples e sem complicações.

Nesse repositório iremos apresenta-lo a alguns conceitos essenciais para utilizar o Git de um forma fácil e prática. Utilizando o mesmo ambiente que você irá encontrar na submissão dos seus exercicios

## Primeiros passos

### Iniciando o ambiente

Se você ainda não tem o git no seu computador, [instale-o aqui](https://git-scm.com/downloads)

Abra o terminal _ou cmd_ e digite:

```
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

### Aceite o exercício

[Clique neste link e aceite o exercício](https://classroom.github.com/a/wzv8BIRG), isto irá criar um repositório para você com o nome aprenda-git-classroom-SeuUsuario

### Clone o seu repositório

<img align="right" width="280" src="assets/clone.png" alt="clone este repositorio" />

**Clone** o seu **repositório** para a sua máquina, este comando irá relizar o donwload do repositório, assim você poderá editar os arquivos localmente para depois enviá-los de volta para o GitHub.

Para clonar digite em seu terminal:

```
git clone https://github.com/seuUsuario/Nome-Do-Repositorio.git

```

### Crie um Branch

Um **branch** é uma ramificação do repositório inicial ele serve como uma forma de adicionar novidades sem modificar o código "Principal do projeto".

```markdown
git checkout -b nome-do-branch
```

Faça suas modificações adicionando um arquivo em python com um print para informar seu nome e o que mais você achar interessante para compartilhar com a turma, utilizando um editor de texto a sua escolha.

### Adicione os arquivos modificados a zona de stage

Nem sempre você irá querer "salvar" todos os arquivos que foram modificados naquele momento no git, apenas os arquivos adicionados à zona de **stage** são commitados, você pode especificar arquivo por arquivo a ser adicionado ou utilizar o símbolo: `.` para indicar todos os arquivos da pasta, assim:

``` markdown
git add .
```

### Faça um "Commit"

- Assim você irá salvar suas modificações no repositório local

- Dê um "Push" para que as modificações sejam enviadas para o servidor do GitHub!

```markdown
git commit -m 'Adicionando fulano ao repositorio'
git push origin nome-do-branch
```

## Dicas para a contribuição

### Arquivo Python

- Crie um arquivo com seuNome.py
- Adicione um print("Seu Nome")
- adicione um print("Alguma informação legal para mostrar a turma")
