### Programa em C que manipula matrizes esparsas, utilizando lista linear encadeada.

OBS: Uma matriz é considerada esparsa quando a maioria dos seus dados são zeros.

Em caso da matriz ser muito grande não é vantajoso, em termos de memória, armazenar todos os
dados, até porque a maioria são zeros. Então o objetivo do trabalho é criar uma lista encadeada e
armazenar somente os dados diferentes de zero, bem como a linha e a coluna onde esses dados
estão localizados.

```c
float dado;
int lin, int col;
float dado;
int lin, int col;
float dado;
int lin, int col;
``` 

Mas, no entanto, o programa deverá imprimir na saída a matriz inteira, tanto os dados diferentes de
zero como os zeros.
O programa deverá ser formado pela seguinte struct:

```c
    typedef struct nodo
    {
        float dado;
        int lin, col;
        struct nodo *prox;
    }Matriz_Esparsa;
``` 
### E pelas seguintes funções:
- Uma função que faz a alocação de memória para cada nodo criado para uma lista
encadeada;
- Uma função que insere na lista encadeada um nodo alocado;
- Uma função que busca os dados em uma lista encadeada;
- Uma função que libera da memória uma lista encadeada;
- Uma função que lê os dados da matriz, via teclado, e inseri na lista encadeada somente os
dados diferentes de zero;
- Uma função que soma duas matrizes;
- Uma função que subtrai duas matrizes;
- Uma função que multiplica duas matrizes;
- Uma função que gera a matriz transposta;
- Uma função que imprime todos os dados da matriz, inclusive os zeros;
- Uma função que imprime os elementos da diagonal principal, inclusive os zeros caso
existam.

### Observações:
- O usuário pode entrar com quantas matrizes desejar.
- O usuário deve informar a dimensão de cada matriz.
- O usuário poderá fazer quantas operações desejar com as matrizes.
- Exemplo: MA * MB + MC - MD
- Considerar as regras de operações com matrizes para implementar a soma, subtração,
multiplicação, transposta e diagonal principal de matrizes.
