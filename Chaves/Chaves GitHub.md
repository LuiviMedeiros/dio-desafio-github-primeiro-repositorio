# <mark>**<u>CHAVES e TOKEN GIT GITHUB</u>**</mark>

## `BOOTCAMP SANTANDER - CODEGIRLS`

**Aula:** *Navegação via Command line*

**Intrutor:** *Otávio Reis, Desenvolvedor Web*

***Chaves e Token Git-GitHub***

## **Passo Inicial**

1. Entrar e se cadastrar no GitHub.com

## Chave SSH Windows

É como o GitHub vai reconhecer você e é a forma mais prática de realizar projetos no GitHub

#### **Passo a Passo para gerar a Chave SSH**

1. Acessar Git Bash no Deskop e digitar:
   
   ssh-keygen -t ed25519 -C lsgs@gmail.com (Enter)

2. colocar uma senha (Enter)

Automaticamente será criado uma pasta chamada .ssh/ no seu diretorio com dois arquivos:

id_ed25519   id_ed25519.pub

3. Entre na pasta .ssh/ com o comando cd/ e digite:
   
   cat id_ed25519.pub (Enter)

Selecione a chave ssh e copie

4. Acessar seu Profile do GitHub, em Settings

SSH and GPG keys

SSH keys

Add new, coloque um titulo para sua chave e depois cole a chave no campo key



**Comando cd** *(entra na pasta ou arquivo desejado)* 

Ex: `C:\DIO\Desafios\Git_GitHub`

`$ cd dio-desafio-github-primeiro-repositorio` (Enter)

`C:\DIO\Desafios\Git_GitHub\dio-desafio-github-primeiro-repositorio`

**Comando cd ..** *(retorna para pasta ou arquivo anterior)*

Ex: $ cd .. (Enter)

**Comando Ctrl + L** *(Limpa a tela)*

Ex: $ Ctrl + L  (Enter)

**Comando mkdir** *(Cria uma nova pasta)*

Ex: `C:\DIO\Desafios\Git_GitHub`

`$ mkdir Hello` (Enter)

`C:\DIO\Desafios\Git_GitHub\Hello`

**Comando rmdir** *(Deleta uma nova pasta ou arquivo)*

Ex: `C:\DIO\Desafios\Git_GitHub`

`$ rmdir Hello` (Enter)
