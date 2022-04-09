<div align="center">
  <img alt="Git" height="100" src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/git.svg">
</div>

# 💻 Introdução ao Git
🗃 Sistema de controle de versões de arquivos distribuídas.
<br>
📑 [Leia a documentação](https://git-scm.com/docs/git/pt_BR)

## 🔗 Instalação
⬇️ [Download Git](https://git-scm.com/).
<br>
✅  Durante a instalação deixe marcada as opções: **"Git Bash Here"** e **"Git GUI Here"**.


## ⚙️ Funcionalidades básicas 

### Como subir um repositório local para a branch main do repositório remoto no GitHub?
📁 Clique com o botão direito na pasta e clique em **"Git Bash Here"**.
```bash
# Transforme a pasta existente em um repositório
$ git init
```
```bash
# Caso haja arquivos dê um "git add ." para adicionar todos ao índice
$ git add .
```
```bash
# Crie um commit e adicione uma mensagem descritiva
$ git commit -m "first commit"
```
```bash
# Adicione a URL do repositório remoto onde deseja upar o seu local
$ git remote add origin https://github.com/username/nome-do-repositorio.git
```
```bash
# Envia os objetos, atualizando a branch main no repositório remoto
$ git push origin main
```

## ⌨️ Comandos básicos 

Comando                                 | Função
--------------------------------------- | -------------------------------------------------------------------------------
git --version                           | Consulta a versão instalada
git init                                | Cria um repositório
git status                              | Exibe o status da árvore de trabalho 
git add                                 | Adiciona os arquivos ao índice
git commit - m"commit message"          | Cria um commit (grava as alterações) adicionando mensagem sobre o que se trata
git push                                | Upa os arquivos atualizando a branch no repositório remoto
git branch                              | Cria, lista ou exclui branches
git clone                               | Clona um repositório

