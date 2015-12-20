## Projetos para fixar o aprendizado

Agora que você já sabe como funciona um função e sabe que pode importar módulos que possuem diversas outras funções,
a quantidade de problemas que você pode resolver aumentou muito!

Para programar bem e resolver problemas interessantes, você não pode ficar "reinventando a roda". Há muita coisa que já
foi feita e testada por outras pessoas para que outros projetos possam utilizá-las e ir mais longe. A linguagem Python já
possui diversos módulos prontos para serem importados sem que você precise baixar mais nada. Vamos explorar alguns deles
nos projetos a seguir!

### 1. Simulador de Dados

O objetivo deste projeto é simular a rolagem de um dado. Se você joga ou já jogou RPG de papel deve conhecer dados com 4, 8,
10, 12 e 20 lados, além do clássico dado de 6 lados. Faça um programa que pergunta ao usuário quantos dados ele quer jogar e
qual o tipo de dado a ser jogado. Após isso, exiba o resultado da jogada. Use a função *randrange* do módulo [random]()!

### 2. Melhorando o "Pedra, Papel e Tesoura!"

Dessa vez, vamos fazer algumas melhorias no jogo "Pedra, Papel e Tesoura" e torná-lo realmente jogável.

**Limpando o terminal** 
O módulo **os** permite que sejam dados alguns comandos direto para o sistema operacional. Usaremos a função *system* com o argumento *"clear"* para limpar o terminal logo após cada jogador inserir sua escolha.

```python
  import os
  
  os.system("clear")
```

Assim, será possível dois jogadores humanos jogarem sem que nenhum tenha desvantagem (o jogador 2 não pode espiar!).

** Jogando contra o computador **
Ao abrir o seu programa, pergunte ao usuário se deseja jogar contra o computador ou contra outra pessoa. Faça as adaptações necessárias.

Caso o usuário opte por jogar sozinho, ele faz a sua escolha e, então, o computador escolhe aleatoriamente entre *pedra*, *papel* ou *tesoura*. Talvez você precise usar uma lista, além do módulo random.
