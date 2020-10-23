# IntroducaoGit
Anotações sobre a utilização de comandos Git mostrados nos cursos 'Introdução ao GitHub e comandos para trabalhar em equipe' e 'Introdução ao Git e Controle de Versões ', na Digital e Innovation One

## Comandos

`mkdir nomePastaProjeto `
Realiza a criação de uma pasta para o projeto

`cd nomePastaProjeto`


 `git config --global user.name "nomeUsuario"`
 Configura o nome de usuario do git local

` git config --globaluser.email "email" `
 Configura o email do usuario do git local
 
 ` git config core.editor `
 Exibe o editor vinculado ao Git ex: Vs Code
 
  ` git config --global core.editor "nomeNovoEditor"`
 Altera o editor
 
 `git init`
 Realiza a criação de um novo subdiretorio (uma pasta .git) no diretorio atual que contém alguns arquivos que são necessarios para o repositorio

 `git clone urlRepositorio `
 Possibilita a realização de uma especie de 'download' do que está contido em um repositorio remoto

 `git remote add origin urlRepositorioRemoto`
 Adiciona uma origem ao repositorio

 `git add  .`
 Realiza a inserção das ultimas modificações para o commit, 'prepara' as modificações para o commit

 `git add nomeArquivo`
 Realiza a inserção de um arquivo especifico para o commit 

 `git commit -m 'mensagem do commit' `
 Realiza o commit das modificações que foram adicionadas, possuindo uma mensagem que é aconselhada ser um resumo simplificado do que foi realizado nas modificações

 `git push  `

 `git pull  `
Possibilita a copia de mudanças do repositorio remoto para o local

 `git status `
 Possibilita vizualização do status dos commits incluindo quais arquivos não foram adicionados ao commit 

 `git branch nomeBranch`
Realiza a criação de uma nova branch

 `git checkout -b nomeBranch`
 Realiza a criação de uma nova branch e troca para a mesma

 `git branch`
Possibilita a vizualização das branches

 `git checkout nomeBranch`
 Realiza a troca da branch atual para a que foi indicada 

 `git branch -D nomneBranch`
 Deleta a branch indicada 

 `git push origin nomeBranch` Realiza o envio da branch para o git  

 `git rebase nomeArquivo `
 Juntar duas branchs sem gerar um novo elemento 

 `git tag 'texto'`
 Realiza a marcação de compromissos especificos no git

 `git remote -v `
 Realiza a listagem de todos os repositorios remotos com a url 

 `git commit -a 'comentario' ` Adicionar um arquivo e fazer o commit em apenas um passo 

 `git log`
 Possibilita a consulta de commits

 `git log --stat`
 Consultar os commits e suas estatisticas abreviadas

 `git remote`
 Utilizado para vizualizar um repositorio remoto

 `git merge nomeBranch`
 Realiza o processo de 'mesclagem' das branchs (atual e indicada), igualando a branch onde se está com a branch que foi indicada

 `git checkout --Nome_do_Arquivo `
 Reseta alterações do arquivo especificado

`git commit --amend`
Possibilita a edição da mensagem do ultimo commit

 `git diff nomeArquivo  `
 Possibilita vizualização das modificações realizadas no arquivo especificado

 `git reset HEAD nomeArquivo ` Retira um arquivo que foi adicionado para o commit


