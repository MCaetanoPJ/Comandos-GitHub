# Comandos-GitHub
Resumos dos principais comandos do GitHub para gerenciar um projeto



Dentro da pasta do projeto clique com o botão direito do mouse e inicie o "Git Bash"
Obs: após digitar o comando pressione a tecla ENTER

1) Use o comando *git init* para tornar essa pasta em um repositório local

# Procedimento padrão para localizar o arquivo modificado e fazer o commit no repositório online

# git status
2) Use esse comando para verificar se algum novo arquivo foi criado ou modificado
Caso exista, o nome do arquivo estará com a cor vermelha

# git add * ou git add "nome_do_arquivo.txt"

3) Use o comando git add * para selecionar todos os arquivos criados ou modificado exibidos no comando acima e prepara-los para adicionar ao repositório online
ou use o comando git add "nome_do_arquivo.txt"* para selecionar um arquivo específico para preparar-lo
Caso tenha adicionado o arquivo errado use o comando git RESET HEAD para desfazer anular o comando git add

4) Repita o comando *git status* para verificar se o arquivo foi preparado corretamente, o nome dos arquivos devem estar na cor verde

# git commit -M "Comentario descrevendo a alteração"
5) Use esse comando para enviar os arquivos preparados para o reposítorio online com a mensagem que foi digitada no comando

# git log ou git log --oneline
6) Use o comando *git log* para verificar o histórico de commit realizados no reposítorio
O comando *git log --oneline* comando exibe uma versão reduzida das informações exibidas pelo *git status*
Esse comando informa o nome de todos os autores que fizeram o commit

Link do youtube de onde os comandos foram retirados: https://www.youtube.com/watch?v=_mB-TShMDvY
