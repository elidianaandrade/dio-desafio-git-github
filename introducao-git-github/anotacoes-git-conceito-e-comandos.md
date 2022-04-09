# 💻 Git
Sistema de controle de versões de arquivos distribuídas.

## 🔗 Instalação
- [Download Git](https://git-scm.com/).
- Durante a instalação deixe marcada as opções "Git Bash Here" e "Git GUI Here".

## ⚙️ Funcionalidades básicas 

### Como subir repositório local para a branch main do repositório no GitHub?
📁 Clique com o botão direito na pasta e clique em "Git Bash Here"
```bash
# Transforme a pasta existente em um repositório
$ git init
```
```bash
# Adicione os arquivos
$ git add .
```
```bash
# Crie o commit e adicione uma mensagem descritiva
$ git commit -m "first commit"
```
```bash
# Adicione a URL do repositório remoto onde deseja upar o seu local
$ git remote add origin https://github.com/username/nome-do-repositorio.git
```
```bash
# Suba a branch para o repositório remoto
$ git push origin main
```


## ⌨️ Comandos básicos 

Comando                                 | Função
--------------------------------------- | -------------------------------------------------------
git --version                           | Consultar versão instalada
git init                                | Criar repositório ou transformar pasta existente em um
git status                              | Consultar informações sobre a branch
git add                                 | Adicionar arquivo ou diretório
git commit - m"commit message"          | Criar commit adicionando mensagem sobre o que se trata
git push                                | Upar branch para o repositório remoto
git branch                              | Criar, excluir ou modificar arquivo 
git clone                               | Clonar um repositório
