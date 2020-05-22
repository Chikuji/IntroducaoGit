# IntroducaoGit
Anotações sobre a utilização de comandos Git

## Comandos

***mkdir nomePastaProjeto**** : realiza a criação de uma pasta para o projeto

***cd nomePastaProjeto***

***git init*** :  

***git clone urlRepositorio*** : possibilita a realização de uma especie de 'download' do que está contido em um repositorio remoto

***git add .*** : realiza a inserção das ultimas modificações para o commit

***git add nomeArquivo*** : realiza a inserção de um arquivo especifico para o commit 

***git commit -m 'mensagem do commit'*** : realiza o commit das modificações que foram adicionadas, possuindo uma mensagem que é aconselhada ser um resumo simplificado do que foi realizado nas modificações

***git push***

***git pull***

***git merge***

***git status***

***git log***

***git branch nomeBranch*** : realiza a criação de uma nova branch

***git checkout -b nomeBranch*** : realiza a criação de uma nova branch e troca para a mesma

***git branch*** : possibilita a vizualização das branches  

***git checkout nomeBranch** : realiza a troca da branch atual para a que foi indicada 

***git branch -D nomneBranch*** : deleta a branch indicada 

***git push origin nomeBranch*** : realiza o envio da branch para o git  

***git rebase nomeArquivo*** - juntar duas branchs sem gerar um novo elemento 

***git tag 'texto'*** -- marcar compromissos especificos no git

git remote -v -- lista os repositorios remotos com a url 

git commit -a <comentario> -- adicionar um arquivo e fazer o commit em apenas um passo 

git log --stat --consultar os commits e suas estatisticas abreviadas

git remote -- ver um repositorio remoto

git merge <<nome-branch>> -- iguala a branch onde voce está com a <<nome-branch>>

git checkout --Nome_do_Arquivo -- resetar as alterações de um arquivo 

git commit --amend -- editar a mensagem do ultimo commit

git diff nome_do_arquivo -- ver modificações feitas no arquivo

git reset HEAD nome_do_arquivo -- retirar um arquivo que foi adicionado para commitar

 
