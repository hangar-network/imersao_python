## Projeto de Fixação do Aprendizado

### Criptografia Básica!

Neste projeto, empregaremos nosso conhecimento de Strings e estruturas de repetição para implementar uma 
[Cifra de César](https://pt.wikipedia.org/wiki/Cifra_de_César).

A Cifra de César é um tipo de cifra de substituição, uma técnica bastante simples de criptografia. A ideia consiste em fazer um *shift* (um deslocamento) nas letras da mensagem original, substituindo-as por uma outra letra que esteja a uma distância K no alfabeto.

Por exemplo, para K = 3 faríamos as seguintes trocas:

      A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
      D E F G H I J K L M N O P Q R S T U V W X Y Z A B C

A mensagem "a ligeira raposa marrom saltou sobre o cachorro cansado", seria substituída por 

    D OLJHLUD UDSRVD PDUURP VDOWRX VREUH R FDFKRUUR FDQVDGR

Indecifrável assim de cara, não?

O parâmetro K é chamado de chave. **Trabalharemos com K fixo e igual a 3 neste projeto**, quando aprendermos a lidar com funções, faremos algo um pouco melhor. Repare que este deslocamento é circular, ou seja, após o Z retorna-se para o A.

**Você deve fazer um programa que pede que o usuário escreva uma frase e, então, escreve o resultado cifrado desta frase usando a cifra de César com chave igual a 3**.

Obs:

1. Não utilizaremos acentos no momento.
2. Cada caracter de uma string possui uma representação por um número inteiro, segundo a [tabela ASCII](https://pt.wikipedia.org/wiki/ASCII). Este número pode ser obtido por meio da função *ord*. Exemplo: ord('A') retorna 65. Da mesma forma, a função *chr* fornece o caracter correspondente ao número: chr(65) retorna 'A'.
