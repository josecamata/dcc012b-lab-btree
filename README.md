# Arvore B :smiles:

Em ciência da computação, uma árvore B é uma estrutura de dados em árvore, auto-balanceada, que armazena dados classificados e permite pesquisas, acesso sequencial, inserções e remoções em tempo logarítmico. A árvore B é uma generalização de uma árvore de pesquisa binária em que um nó pode ter mais que dois filhos. É normalmente usada em bancos de dados e sistemas de arquivos e foi projetada para funcionar especialmente em memória secundária como um disco magnético ou outros dispositivos de armazenamento secundário. 

As árvores B são semelhantes as árvores preto e vermelho, mas são melhores para minimizar operações de E/S de disco. Muitos sistemas de bancos de dados usam árvores B ou variações da mesma para armazenar informações. Dentre suas propriedades ela permite a inserção, remoção e busca de chaves numa complexidade de tempo logarítmica e, por esse motivo, é muito empregada em aplicações que necessitam manipular grandes quantidades de informação tais como um banco de dados ou um sistemas de arquivos.

## O que deve ser feito

1. Implementar uma tipo abstrato de dados para representar uma arvore B de ordem t
2. Implementar as operações básicas: insersão, remoção, pesquisa e impressão.
3. Fazer um estudo comparativo usando árvores de diferentes ordem. O que pode ser observado em relação ao desempenho?

Observação:
- a função *main* usa argumentos por linha de comando. Para executar, há
a necessidade de indicar a ordem e o numero de insersões.  Veja o exemplo:

```
./btree -o 5 -n 100
```
Use essa funcionalidade para fazer testes representativos.

## Por onde começar:

- Veja o [capitulo 18 do livro do Cormen](docs/cap18_btree.pdf). Considere os pseudocódigos disponíveis lá. 
- Implemente a TAD no arquivo btree.h. 
- No arquivo main.cpp há linhas comentadas que devem ser removidas a medida que a implementação avança. Implemente primeiro o insert e depois descomente essa parte na main. Faça o mesmo para as próximas etapas.
- A main deve estar totalmente descomentada na submissão final.


## Minhas Observações:
 * escreva aqui suas observações sobre o estudo comparativo*
 



