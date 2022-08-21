# curso-frontend
### EBAC

# GIT 
## Versionamento
 - Histórico 
 - Controle de Versão
 - Quem alterou
 - O que alterou
 - Quando alterou
 - Todos os arquivos
 - Evolução continua 


 Arquivo A | Versão 1 | Versão 2
 Arquivo B | Versão 1 | Versão 2

## Instalação do Git

 - Windows: https://git-scm.com/download/win
 - Linux (apt-get): sudo apt-get install git
 - Mac (Brew): brew isntall git

## Criar uma conta no GitHub
git clone https://github.com/roselimariano38/curso-frontend.git

## Clonar o projeto

## Commits
Informação de alteração
 -após testado todo seu código
 - Git add *
 - Git commit -m *mensagem*
 
 
  ### Branchs
 São ramificações / Versões paralelas

 -main/master ( vai para produção,quando o projeto é publicado)
 -develop
 -DOD Definition of Done: critérios de aceite
 -versionamento 1.0.0
 
  git checkout -b dev (cria uam branch)

### Merge
Mescla de Branchs



 ## GitFlow
 Fluxo do Git

 ### Branchs
 São ramificações / Versões paralelas

 -main/master ( vai para produção,quando o projeto é publicado)
 -develop
 -DOD Definition of Done: critérios de aceite
 -versionamento 1.0.0

 git checkout -b dev (cria uam branch)
 git checkout master ( muda de branch)
 
### Merge
Mescla de Branchs

 git checkout -b dev (cria uam branch)
 git checkout master ( muda de branch)


### Merge
Mescla de Branchs
você pode resolver conflitos manualmente

 git merge main

### Pull Requests
Mescla de Branchs no Repositório
Permite code review
o repositório resolve os conflitos automaticamente

### Configurar o GitFlow
git flow init
git flow feature start [melhoria-html]
