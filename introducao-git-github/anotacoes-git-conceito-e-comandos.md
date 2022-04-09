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

<br>

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
# Envie os objetos, atualizando a branch main no repositório remoto
$ git push origin main
```

<br>

### Como alterar a branch em que estou trabalhando pela branch main?
📁 Clique com o botão direito na pasta do repositório local e clique em **"Git Bash Here"**.
```bash
# Alterne para a branch main
git checkout main
```
🛑 Caso exiba o erro: `error: pathspec 'main' did not match any file(s) known to git` dê um `git checkout -b main`

 <!--`git pull origin nomedabranchatual --allow-unrelated-histories` em seguida adicione uma mensagem ou aperte ESC e digite `:wq` para fechar e salvar. -->

```bash
# Mescle a branch main com a que deseja (nesse caso a que estava trabalhando e vai alterar pela main) 
git merge nomedabranch
```
```bash
# Envie os objetos atualizando a branch main no repositório remoto 
git push
```
```bash
# OPCIONAL: Delete a branch antiga do repositório local caso não deseje mais
git branch -d nomedabranch
```

<br>

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

