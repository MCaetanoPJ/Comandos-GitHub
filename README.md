# Comandos-GitHub
Resumos dos principais comandos do GitHub para gerenciar um projeto



Dentro da pasta do projeto clique com o botão direito do mouse e inicie o "Git Bash"
Obs: após digitar o comando pressione a tecla ENTER

1) Use o comando *GIT INIT* para tornar essa pasta em um repositório local

# Procedimento padrão para localizar o arquivo modificado e fazer o COMMIT no repositório online

2) Use o comando *GIT STATUS* para verificar se algum novo arquivo foi criado ou modificado
Caso exista, o nome do arquivo estará com a cor vermelha

3) Use o comando *GIT ADD * para selecionar todos os arquivos criados ou modificado exibidos no comando acima e prepara-los para adicionar ao repositório online
ou use o comando *GIT ADD "nome_do_arquivo.txt"* para selecionar um arquivo específico para preparar-lo
Caso tenha adicionado o arquivo errado use o comando GIT RESET HEAD para desfazer anular o comando GIT ADD

4) Repita o comando *GIT STATUS* para verificar se o arquivo foi preparado corretamente, o nome dos arquivos devem estar na cor verde

5) Use o comando *GIT COMMIT -M "Comentario descrevendo a alteração"* para enviar os arquivos preparados para o reposítorio online com a mensagem que foi digitada no comando

6) Use o comando *GIT LOG* para verificar o histórico de COMMIT realizados no reposítorio
O comando *GIT LOG --ONELINE* comando exibe uma versão reduzida das informações exibidas pelo *GIT STATUS*
Esse comando informa o nome de todos os autores que fizeram o COMMIT

Link do youtube de onde os comandos foram retirados: https://www.youtube.com/watch?v=_mB-TShMDvY
