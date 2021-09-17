PARTE 01 - ATIVIDADE 01

Altere sua implementação do programa Labirinto para apresentar o tabuleiro com as posições de início e destino, como mostrado nesta parte da aula. Tente não copiar o código mostrado, mas fazer sem olhar o material da aula. Relate se você conseguiu fazer a implementação sem copiar, se você fez algo de diferente em termos de implementação ou se a sua implementação ficou igual à mostrada na aula.
  Consegui fazer partes, outras partes precisei olhar no código do professor, e no fim, ficou mais ou menos igual à implementação mostrada na aula.


Execute várias vezes o programa Labirinto e relate se houve mudanças na posição dos pontos de início e destino do labirinto.
  Houve

Teste o uso de outros caracteres para as constantes de INICIO e DESTINO usadas no programa e indique se você encontrou valores mais adequados (para deixar o tabuleiro mais bonito, mais simples de ser visualizado etc. que os mostrados na aula).
  Gostei dos caracteres I-para início e X-para o fim

Altere a função "inicializarMatriz()" para posicionar o caractere de início na parte inferior à esquerda do tabuleiro, e para posicionar o caractere de destino na parte superior à direita do tabuleiro. Execute e confira se sua implementação está correta.
  linhaInicio = gerarNumero(TAMANHO / 2, TAMANHO);
  int linhaDestino = gerarNumero(1, TAMANHO / 2 - 1);


PARTE 01 - ATIVIDADE 02
Altere sua implementação do programa Labirinto para ele procurar e mostrar um caminho válido, como mostrado nesta última parte da aula. Tente não copiar o código mostrado, mas fazer sem olhar o material da aula. Relate se você conseguiu fazer a implementação sem copiar, se você fez algo de diferente em termos de implementação ou se a sua implementação ficou igual à mostrada na aula.
  Consegui fazer partes, outras partes precisei olhar no código do professor, e no fim, ficou mais ou menos igual à implementação mostrada na aula.

Execute várias vezes o programa Labirinto e relate se houve mudanças na posição dos pontos de início e destino e nos caminhos encontrados. Eles foram os menores caminhos possíveis dentro do tabuleiro? Sempre foi possível encontrar caminhos válidos?
  Eles não foram pelos menores caminhos possíveis e nem sempre foi possível encontrar caminhos válidos


Teste o uso de outros caracteres para as constantes de CAMINHO e SEM_SAIDA usadas no programa e indique se você encontrou valores mais adequados (para deixar o tabuleiro mais bonito, mais simples de ser visualizado etc.) que os mostrados na aula.


Altere o tempo em "milissegundo"s do comando "Thread.sleep()" para mais e para menos. Relate o que acontece com essas mudanças, e qual seria o melhor valor para você poder acompanhar a execução do algoritmo de busca.

PARTE 01 - AUTOAVALIAÇÃO
Qual a estrutura de dados que se pode utilizar para representar o tabuleiro do jogo de labirinto?
  Matriz
  
Como podemos preencher os obstáculos (paredes internas) no tabuleiro do jogo, de forma que toda vez que se jogue, um novo tabuleiro seja mostrado?
  Math.random() * (10 - 1)

PARTE 02 - ATIVIDADE 01
Implemente o programa Labirinto, de acordo com a versão mostrada, só para apresentar o tabuleiro vazio. Tente não copiar o código mostrado, mas fazer sem olhar o material da aula. Relate o que você fez de diferente em termos de implementação ou se a sua implementação ficou igual à mostrada na aula.
  Consegui fazer partes, outras partes precisei olhar no código do professor, e no fim, ficou mais ou menos igual à implementação mostrada na aula.
  
Altere o valor da constante que representa o tamanho do tabuleiro. Relate o que houve com o tabuleiro mostrado pelo programa e explique como a alteração dessa constante afetou o resto do programa.
  O tabuleiro muda de tamanho proporcionalmente, o que faz com que todos os outros elementos possuam diferentes possibilidades de locação.
 
PARTE 02 - ATIVIDADE 02
Altere sua implementação do programa Labirinto para apresentar o tabuleiro com as paredes internas (obstáculos), como mostrado nessa segunda parte da aula. Tente não copiar o código mostrado, mas fazer sem olhar o material da aula. Relate o que você fez de diferente em termos de implementação ou se a sua implementação ficou igual à mostrada na aula.
  Consegui fazer partes, outras partes precisei olhar no código do professor, e no fim, ficou mais ou menos igual à implementação mostrada na aula.

Execute várias vezes o programa Labirinto e relate se houve mudanças na posição e quantidade de obstáculos que formam as paredes internas do labirinto.
  Houve
  
Teste o uso de outros caracteres para as constantes usadas no programa e indique se você encontrou valores mais adequados que os mostrados na aula (deixam o tabuleiro mais bonito, são mais simples de serem visualizados etc.).
  Gostei do caracter '8'
  
Altere o valor da constante PROBABILIDADE e relate o que acontece quando aumentamos ou diminuímos o seu valor.
  A quantidade de obstaculos é alterada


PARTE 02 - AUTOAVALIAÇÃO
Qual a ideia do uso da recursão utilizada na programação do programa Labirinto.
  A ideia da recursão utilizada no labirinto é de repetir várias tentativas até achar o caminho correto.

Na sua opinião, códigos que utilizam recursão são intuitivos? Você conseguiu entender facilmente o código recursivo do programa Labirinto?
  Acho que os codigos que utilizam recursão não são tão intuitivos. Consegui entender tranquilamente o código utilizado no labirinto, porém quando comecei a estudar programação    tive bastante dificuldade para entender códigos recursivos














