<p align="center">
 
<img src="https://www.nicepng.com/png/full/52-520535_free-files-github-github-icon-png-white.png" width="150">
<h3 align="center">GitHub - Comandos Úteis</h3>

<p align="center">Nesse repositório você encontrará comandos que são utilizados no dia a dia.</p>
<p align="center"><a href="https://docs.google.com/presentation/d/1MUGOmkU1VH8HdjD3rP4Rr4PyHQ_VtfSzShA08pXtwJU/edit?usp=sharing">Apresentação</a></p>
</p>

## 👨🏿‍💻 Comandos


| Comando | Descrição |
|--|--|
|    **git switch -c <nome_da_branch>** | Se você esqueceu de criar uma branch e acabou fazendo as alterações na branch MAIN por exemplo, use esse comando para criar uma nova branch e transferir as alterações que você fez para ela. |
|    **git merge <nome_da_branch>** | Caso precise fazer um merge de uma outra branch.
|    **git checkout -b <nome_da_branch>** | Para criar uma nova branch e já acessá-la.
|    **git branch -d <nome_da_branch>** | Deleta uma branch.
|    **git tag -a <nome_da_tag> -m <descricao_da_tag> && git push origin <nome_da_tag>** | Cria uma nova tag e envia para o seu remote.
|    **git tag** | Visualiza as tags existentes.
|    **git tag -d <nome_da_tag>** | Apaga uma tag localmente.
|    **git tag --delete origin <nome_da_tag>** | Apaga uma tags no seu remote.
|    **git checkout tags/nome_da_tag** | Acessa os arquivos de uma tag especifica.
|    **git reset --hard HEAD** | Volta para o cabeçalho do remote.
|    **git revert <hash_do_commit>** | Volta para um commit especifico.
|    **git fetch** | Busca atualizações da branch.
|    **git fetch origin pull/ID/head:BRANCHNAME** | Se for necessário testar uma pull request que foi criada, pode utilizar esse comando para baixar a PR para o seu repositório local.
|    **git reset --soft HEAD~1** | Caso tenha digitado "git comit ..." por engano, use esse comando para reverter a ação
|    **git reset** | Caso tenha digitado "git add ." por engano, use esse comando para reverter a ação
|    **git reset --hard <hash_do_commit>** | Caso precise voltar a um commit especifico, utilize esse comando
|    **git log** | Veja o histórico de commits e tenha acesso aos hash dos commits

## Tipos de Commits
| Tipo | Descrição |
|--|--|
| **feat** | Nova Funcionalidade |
| **fix** | Correção de bug |
| **docs** | Documentação |
| **style** | Formatação sem mudança lógica |
| **refactor** | Refatoração sem alterar comportamento |
| **test** | Testes |
| **chore** | Usado para alterações que não afetam o código de produção diretamente |
| **perf** | Melhoria de performance |
| **build** | Alterações de build |
| **ci** | Alterações de integração contínua |
| **revert** | Revertendo commit |
