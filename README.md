## Ordenação

### bubble_sort --> Algoritmo de ordenação bolha
   O algoritmo de ordenação bolha (bubble sort) compara pares adjacentes de valores e "flutua" o maior valor (ou menor se for descrescente) para a posição correta (última). 
   O laço interno garante que todos os valores serão comparados e o maior valor da vez será selecionado. Enquanto o laço externo garante que o laço interno se repetirá e selecionará o valor (primeiro maior, segundo maior, terceiro maior, etc...) conforme quantidade de vezes necessária. 
   Obs: Após ser colocado na posição correta, o valor não precisa mais ser comparado. Mas mesmo que as comparações sigam de forma redundante nas próximas "passadas" pelo laço interno, o algoritmo conseguirá ordenar o vetor da mesma forma, embora execute passos desnecessários.

### insertion_sort --> Algoritmo de ordenação por inserção
   O algoritmo de ordenação por inserção (insertion sort) compara determinado valor (a partir da segunda posição) com todos os valores anteriores e troca se algum valor anterior for maior que o valor da posição comparada.
   O laço interno garante que todos os valores anteriores a posição definida (2 - n) serão comparados. Enquanto o laço externo garante que o laço interno se repetirá a quantidade de vezes necessárias para que todos os valores tomem suas respectivas posições.

### selection_sort --> Algoritmo de ordenação por seleção
   O algoritmo de ordenação por seleção (selection sort) percorre o vetor em busca do menor valor. Em seguida transfere-o para a posição esperada.
   O laço interno busca o menor valor, o laço externo posiciona-o conforme esperado e garante qu eo laço externo se repita a quantidade de vezes necessárias para buscar o próximo menor valor até que todos estejam ordenados.  

### quick_sort --> Algoritmo de ordenação por divisão e conquista 
   No metodo quick sort, um valor 'pivô' é escolhido como valor inicial para a ordenação (geralmente é escolhido o primeiro ou ultimo valor). A partir dele, os elementos são comparados entre si e irão trocar de lugar até
   'alcançarem' o pivô, onde serão organizados acima (maior) ou abaixo (menor) do que ele. Após a primeira execução, vão existir duas  partições - os valores menores e os valores maiores do que o pivô (que estará na sua
   posição correta). Recursivamente, serão escolhidos novos pivôs em ambos os lados até que todos os valores estejam ordenados.
   
### coctail_sort --> Algoritmo de ordenação por comparação
   O método Cocktail Sort, começa comparando os valores da esquerda para a direita, se o valor da direita é menor que o da esquerda, faz-se a troca se for verdadeiro, assim até que não haja mais possibilidade de troca. Quando não há mais valores para trocar, ele volta comparando, mas agora ele trás o menor valor para a esquerda assim sucessivamente(quantas vezes for necessário, ir do começo ao final e voltar) até que o vetor esteja completamente ordenado.
