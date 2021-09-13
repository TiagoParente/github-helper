<p align="center">
 
<img src="https://www.nicepng.com/png/full/52-520535_free-files-github-github-icon-png-white.png" width="150">
<h3 align="center">GitHub - Comandos Úteis</h3>

<p align="center">Nesse repositório você encontrará comandos que são utilizados no dia a dia.</p>
</p>

## 👨🏿‍💻 Comandos

> git switch -c nome_da_branch

 ➔ Se você esqueceu de criar uma branch e acabou fazendo as alterações na branch MAIN por exemplo, use esse comando para criar uma nova branch e transferir as alterações que você fez para ela.
<hr>

> git merge nome_da_branch

 ➔ Caso precise fazer um merge de uma outra branch.
 
<hr>

> git checkout -b nome_da_branch

 ➔ Para criar uma nova branch e já acessá-la.
 
<hr>

> git branch -d nome_da_branch

 ➔ Deleta uma branch.

<hr>

> git tag -a nome_da_tag -m descricao_da_tag <br>
> git push origin nome_da_tag

 ➔ Cria uma nova tag e envia para o seu remote.
 
<hr>

> git tag

 ➔ Visualiza as tags existentes.
 
<hr>

> git tag -d nome_da_tag

 ➔ Apaga uma tags localmente.
 
 <hr>
 
 > git tag --delete origin nome_da_tag

 ➔ Apaga uma tags no seu remote.
 
 <hr>
 
 > git checkout tags/nome_da_tag

 ➔ Acessa os arquivos de uma tag especifica.
 
<hr>
 
 > git reset --hard HEAD   

 ➔ Volta para o cabeçalho do remote.
 
<hr>
 
 > git revert hash_do_commit

 ➔ Volta para um commit especifico.
 
 <hr>
 
 > git fetch

 ➔ Busca atualizações da branch.
 
 <hr>
 
 > git fetch origin pull/ID/head:BRANCHNAME

➔ Se for necessário testar uma pull request que foi criada, pode utilizar esse comando para baixar a PR para o seu repositório local.
