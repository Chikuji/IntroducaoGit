# IntroducaoGit
Anotações sobre a utilização de comandos Git

## Comandos

***mkdir nomePastaProjeto**** : realiza a criação de uma pasta para o projeto

***cd nomePastaProjeto*** : 

***git config --global user.name "nomeUsuario"*** : configura o nome de usuario do git local
***git config --globaluser.email "email"** : configura o email do usuario do git local

***git init*** :  realiza a criação de um novo subdiretorio (uma pasta .git) no diretorio atual que contém alguns arquivos que são necessarios para o repositorio

***git clone urlRepositorio*** : possibilita a realização de uma especie de 'download' do que está contido em um repositorio remoto

***git remote add origin urlRepositorioRemoto*** : adiciona uma origem ao repositorio

***git add .*** : realiza a inserção das ultimas modificações para o commit, 'prepara' as modificações para o commit

***git add nomeArquivo*** : realiza a inserção de um arquivo especifico para o commit 

***git commit -m 'mensagem do commit'*** : realiza o commit das modificações que foram adicionadas, possuindo uma mensagem que é aconselhada ser um resumo simplificado do que foi realizado nas modificações

***git push*** : 

***git pull*** : possibilita a copia de mudanças do repositorio remoto para o local

***git status*** : possibilita vizualização do status dos commits incluindo quais arquivos não foram adicionados ao commit 

***git branch nomeBranch*** : realiza a criação de uma nova branch

***git checkout -b nomeBranch*** : realiza a criação de uma nova branch e troca para a mesma

***git branch*** : possibilita a vizualização das branches  

***git checkout nomeBranch** : realiza a troca da branch atual para a que foi indicada 

***git branch -D nomneBranch*** : deleta a branch indicada 

***git push origin nomeBranch*** : realiza o envio da branch para o git  

***git rebase nomeArquivo*** - juntar duas branchs sem gerar um novo elemento 

***git tag 'texto'*** : realiza a marcação de compromissos especificos no git

***git remote -v*** : realiza a listagem de todos os repositorios remotos com a url 

***git commit -a 'comentario'*** -- adicionar um arquivo e fazer o commit em apenas um passo 

***git log*** : possibilita a consulta de commits

***git log --stat*** : consultar os commits e suas estatisticas abreviadas

***git remote** : utilizado para vizualizar um repositorio remoto

***git merge nomeBranch*** : realiza o processo de 'mesclagem' das branchs (atual e indicada), igualando a branch onde se está com a branch que foi indicada

***git checkout --Nome_do_Arquivo*** : reseta alterações do arquivo especificado

**git commit --amend*** : possibilita a edição da mensagem do ultimo commit

***git diff nomeArquivo*** possibilita vizualização das modificações realizadas no arquivo especificado

***git reset HEAD nomeArquivo*** : retira um arquivo que foi adicionado para o commit

 
