# Comandos Linux

1 - man [nome comando] - Mostra parametro opcionais de cada comando do linux e o que o mesmo faz

2 - pwd - Mostra o diretorio em que voçê esta atualmente

3 - ls - Mostra a lista de pasta/ arquivos de um diretorio

4 - cd - Utilizado para navegar entre as pastas

5 - mkdir - Utilizado para criar uma nova pasta através do terminal

* Para criar estrutura de pasta filhas utiliza parametro -p. Exemplo: mkdir -p image/pics
* Para criar varias pastas filhas nomes comando, segue exemplo: mkdir -p names/{jonh,tom,bob}

6 - rmdir - Utilizado para remover diretorio ou estrutura de diretorio

* rmdir -p a/b/c/d/e para remover estrutura de diretório
* rmdir -pv a/b/c/d/e para remover estrutura de diretório, passado a flag v voçê pode ver como o comando esta deletando a estrutura do arquivo

*Obs: Irá apresentar erro ao tentar deletar uma estrutura de arquivo onde alguma das pastas tenha um arquivo

7 - rm - Utilizado para remover diretorio e os arquivos do diretorio: exemplo: rm -r [nome diretorio]

8 - cat - pode ser utilizado para criar arquivos, quanto para ter o output dos aquivos noterminal

* Para criar um arquivo: cat > [nome arquivo], entao o conteudo a ser digitado no arquivo (sobrescreve o arquivo)
* Para dar append em um arquivo criado: cat >> [nome arquivo], entao o conteudo a ser digitado no arquivo
* Para apresentar o que foi digitado: cat [nome arquivo], entao a informação será printada no terminal

9 - cp - utilizado para copiar arquivos
* cp options source destination
* Caso a pasta nao exista ira renomear a mesma, caso exista ira copiar uma pasta  dentro da outra
* Obs: Caso não queira sobrescrever um arquivo de outro diretório que tem o mesmo nome é o passar -i no comando

10 - mv - Move arquivos de diretório, bastante similar ao comando cp
* Obs: Caso não queira sobrescrever um arquivo de outro diretório que tem o mesmo nome é o passar -i no comando

11 - less - Usado para navegar dentro de arquivos muito grande
* Para procurar um padrao de cima pra baixo prescione /{pattern}, pressionando n para ir para o proximo resultado
* Para procurar um padrao de baixo para cima prescione ?{pattern}, pressionando n para ir para o proximo resultado
* Para navegar pagina por pagina pressione ESPAÇO para ir pra BAIXO, pra cima pressione B
* Para ir para o final do arquivo pressione SHIFT + G
* Para ir para o inicio do arquivo pressione 1G ou g minusculo

	

