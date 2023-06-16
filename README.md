# aula1-git-github
Este repositório é para fins de estudo do módulo git e github.


→ Criação de pasta: Mkdir

→ Acessar a pasta: cd "nome-da-pasta"

→ Para iniciar um repositório: git init

→ Para retornar um diretorio: cd ..

→ Para renomear uma pasta do diretório: mv nome-da-pasta-deverá-sair-da-pasta-primeiro

→ Para remover arquivo do diretório: rm "nome-do-arquivo"

→ Para remover um diretorio certificar que esta sincronizado com o repositorio remoto e remova a pasta localmente com o código: git rm -r nome-da-pasta-ou-arquivo

→ Para criar um arquivo dentro de uma pasta: echo "# nome-da-pasta" >> nome-do-arquivo

→ Para listar quais arquivos existem dentro da pasta selecionada: ls

→ Para adicionar conteudo os arquivos/pastas: git add "nome-do-arquivo"

→ Para adicionar conteudo os arquivos/pastas: touch nome-do-arquivo

→ Para adicionar todos os arquivos/pastas: git add .

→ Para desfazer um add específico: git reset nome-do-arquivo

→ Para desfazer um add geral: git reset 

→ Para fazer um comentario no arquivo adicionado ANTES-DO-PUSH (commit): git commit -m "adicionar comentário"

→ Para verificar os arquivos na branch: git status

→ Caso adicione um arquivo errado utilize esse comando para restaurar o ultimo estado confirmado (com a opção --staged) o arquivo sera removido apenas da área de preparação: git resotre --staged 

→ git reset [nome-do-arquivo]: Retorna o arquivo para a stage

→ Retorna ao último commit, mantendo as alterações feitas nos arquivos: git reset --soft HEAD~1

→ Retona ao último commit, removendo as alterações feitas nos arquivos: git reset --hard HEAD~1
