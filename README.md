# Comandos-GitHub e GitLab
Resumos dos principais comandos do GitHub para gerenciar um projeto



Dentro da pasta do projeto clique com o botão direito do mouse e inicie o "Git Bash"
Obs: após digitar o comando pressione a tecla ENTER

# git config --global user.name nomeDoUsuario
Use esse comando para configurar o gitHub com o seu usuário

# git clone github.com/nome_repositorio.git
Use esse comando para baixar o repositório do gitHub para sua máquina

# git init
Use esse comando para tornar essa pasta em um repositório local

# git status
Use esse comando para verificar se algum novo arquivo foi criado ou modificado
Caso exista, o nome do arquivo estará com a cor vermelha

# git add * ou git add "nome_do_arquivo.txt"
Use o comando git add * para selecionar todos os arquivos criados ou modificado exibidos no comando acima e prepara-los para adicionar ao repositório online
ou use o comando git add "nome_do_arquivo.txt"* para selecionar um arquivo específico para preparar-lo
Caso tenha adicionado o arquivo errado use o comando git RESET HEAD para desfazer anular o comando git add
Repita o comando *git status* para verificar se o arquivo foi preparado corretamente, o nome dos arquivos devem estar na cor verde

# git commit -m "Comentario descrevendo a alteração"
Use esse comando para enviar os arquivos preparados para o reposítorio online com a mensagem que foi digitada no comando

# git push origin master
Use esse comando para enviar suas alterações para o servidor

# git pull
Use esse comando para atualizar os seus arquivos locais com a versão mais recente que está no servidor

# git reset --hard
Use esse comando quando o repositório local tiver alterações e você precise ignorar essas alterações para usar o git pull

# git log ou git log --oneline
Use o comando *git log* para verificar o histórico de commit realizados no reposítorio
O comando *git log --oneline* comando exibe uma versão reduzida das informações exibidas pelo *git status*
Esse comando informa o nome de todos os autores que fizeram o commit

Link do youtube de onde os comandos foram retirados: https://www.youtube.com/watch?v=_mB-TShMDvY

Link de artigo: https://dev.to/juni/git-and-github---must-know-commands-to-make-your-first-commit-333c#:~:text=You%20are%20ready%20to%20push,always%20exists%20on%20any%20repository.
