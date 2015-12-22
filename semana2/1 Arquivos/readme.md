## Projeto de fixação do Aprendizado

### Criptografando Documentos

Vamos melhorar ainda mais nosso programa de criptografia baseado na cifra de César. Você deve adicionar a opção de cifrar um arquivo de texto ao seu programa.

Caso o usuário opter por cifrar um arquivo de texto,  ele deve digitar o caminho do arquivo para o seu programa, que irá abrir o arquivo, ler o seu conteúdo, cifrá-lo e escrever o resultado cifrado em um outro arquivo.

Obs:

1. Se você é iniciante, tente colocar o arquivo a ser cifrado na mesma pasta onde se encontra o seu código; desta forma, o caminho do arquivo é dado apenas pelo nome do arquivo.
2. Você pode continuar perguntando o valor da chave para o usuário ou pode optar por gerar uma chave aleatoriamente.
3. O nome do arquivo cifrado deve ser o mesmo nome do arquivo original acrescido de "\_cifrado". Por exemplo: "segredo.txt" terá o resultado escrito em "segredo_cifrado.txt".
4. O conteúdo do arquivo cifrado deve adotar a seguinte convenção: a primeira linha contém apenas o valor da chave usada na cifra; a mensagem cifrada inicia na linha seguinte ao valor da cifra.


### Descriptografando Documentos

Desta vez, vamos fazer o processo inverso! Você deve fazer um programa que recebe o caminho de um arquivo criptografado (que tenha sido criptografado segundo o padrão do exercício anterior!), abra este arquivo, leia o seu conteúdo e escreva o resultado descriptografado em outro arquivo.

Obs:

1. Você deve ser capaz de separar a linha que contém a chave usada na criptografia do conteúdo da mensagem.
2. O nome do arquivo descriptografado deve substituir "\_cifrado" por "\_decifrado". Exemplo: "segredo_cifrado.txt" terá o resultado escrito em "segredo_decifrado.txt".
