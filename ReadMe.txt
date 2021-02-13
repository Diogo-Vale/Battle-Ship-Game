O trabalho encontra-se dividido em três módulos seguindo assim a seguinte a
linha lógica:

1-Recolha de informações necessárias para a formação do campo de jogo e
características dos barcos a serem utilizados

2-Utilização das informações recolhidas para realizar a escolha da posição e
colocação dos diferentes barcos no campo já corretamente inicializado

3-Após toda a estrutura do jogo ser devidamente inicializada começa então a fase
de jogar propriamente dita, onde cada jogador intercaladamente tem a
opurtunidade de atingir os barcos do adversário


1:
No começo do jogo é pedido a cada jogador para que escolha o seu nickmane, sendo
estes testados para que não ocorra ambos os jogadores possuirem o mesmo nome;

Seguidamente é perguntado ao jogadores se querem as dimensões do campo
escolhidas aleatoriamente ou não (ambas sendo dentro dos requisitos pré
definidos);

A partir da escolha anterior é então determinada a dimensão do campo de jogo e
consequentemente o número máximo de barcos que poderão ser utilizados;

É então inicializado o campo e todas as suas células são preenchidas com os
valores iniciais;

A parte que se segue é um conjunto de printf onde é esclarecido ao jogador os
diferentes tipos de barcos e a forma como estes devem ser colocados;

Consoante essas diretrizes os jogadores escolhem o número de cada tipo de barco
que pretendem, esta seleção pode ser feita manualmente ou aleatoriamente e
baseado no produto dessa seleção afere-se o número de células a que pertencem
barcos, sendo este valor utilizado para saber quando o jogo acaba;

2:
Ambos os jogadores podem escolher colocar os barcos manualmente, ou seja, 1 a 1
vão indicando a posição que pretendem através do input da fila, coluna e rotação;

Como alternativa podem escolher que a colocação de todos os barcos seja feia
aleatoriamente;

As posições são aceites apenas se corresponderem aos parametros necessários;

3:
Iniciando a fase de gameplay, é pedido a cada jogador alternadamente que
indiquem uma posição no tabuleiro;

A posição em questão é verificada e caso corresponda a um barco o seu valor é
modificado e assinala-se que o tiro foi realmente bem sucedido;

Caso a posição escolhida não corresponda a nenhum barco também o seu valor é
modificado e assinala-se que o tiro não foi bem sucedido;

Este processo decorre até que um dos jogadores tenha todos os seus barcos
destruídos.

Para compilar: após o unzip escrever make na consola e depois make exec para
correr o programa.
Para limpar os ficheiros criados neste processo make clean

