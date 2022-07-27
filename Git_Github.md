# Introdução

## Entendendo o que é Git e sua importância

“Software não é feito sozinho”

GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo. 

# Navegação via command line interface e instalação

## Comandos básicos para um bom desempenho no terminal

## Realizando a instalação do GIT

[https://www.youtube.com/watch?v=NgWExh3bswg](https://www.youtube.com/watch?v=NgWExh3bswg)

# ****Entendendo como o Git funciona por baixo dos panos****

## Tópicos fundamentais para entender o funcionamento do Git

- **SHA1**
    
    A função **SHA1** usa a função de hash criptográfica **SHA1** para converter uma string de comprimento variável em uma string de 40 caracteres que é uma representação de texto do valor hexadecimal de uma soma de verificação de 160 bits. Uma forma curta de representar um arquivo.
    

## Objetos internos do Git

### Objetos fundamentais

**Blobs**

**Contém:**

- Tipo do objeto
- Tamanho
- \0
- Conteúdo

**Trees**

**Contém:**

- \0 (apontando para um blob)
- Tamanho
- blob
- Nome do arquivo
- Conteúdo

**Commits**

**Contém:**

- Tree
- Tamanho
- Parente(último commit)
- Autor
- Mensagem
- Timestamp

## **Chave SSH e Token**

### SSH

- **Passo a passo:**
    
    [Gerar uma nova chave SSH e adicioná-la ao ssh-agent - GitHub Docs](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)    

### Token

[Criar um token de acesso pessoal - GitHub Docs](https://docs.github.com/pt/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

# **Primeiros comandos com Git**

## Iniciando o Git e criando um commit

Git init

Git config

**Tipos de arquivo:**

**No Github** mesmo, você pode **usar** no README.md, que é um arquivo que fica na raiz do seu projeto, e é renderizado pelo **Github** abaixo da lista de arquivos. Aquele texto que você lê quando acessa um repositório é um arquivo README.md, escrito em **Markdown.**

[Guia da Linguagem Markdown - Curso de Git e GitHub](https://www.youtube.com/watch?v=LntSB-gl-ZI)