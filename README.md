# tarefa-metodo-bubble-sort
estou fazendo uma tarefa da faculdade onde é preciso Implementar o método Bolha e escrever um código que leia os vetors  a seguir e gere automaticamente os gráficos (tempo de processamento). Tamanho = [500, 1000, 2000, 5000, 10000, 50000, 100000]  Atenção:  Gerar números aleatórios para 'popular' o vetor. Contador de tempo (timestamp). Plotar gráfico.

de forma resumida, o script funciona da seguinte forma:

1) a função adicionarValores() usa o indice dos elementos da lista tamanhoVetoresX que serve para indicar quantos valores serão gerados de forma aletatoria. Ou seja, no primeiro loop(r), serão gerados 500 valores aleatórios(entre 0 e 100), que sera adicionado na lista interna vetorFinal.
2) a função ordenar pega a lista interna, ordena e adiciona na lista interna vetorFinal(o tempo de é calculado com o inicio e termino da função, e depois de calculado adicionado na lista tempoY)

3) o grafico com tempo de execução é gerado, e como ja era de se esperar:
  1)quanto maior o vetor, mais tempo levara para realizar a ordenarção
  2)um vetor maior sera ordenado mais rapido que um vetor menor quando o maior tiver mais qunatidade de     valores repetidos.
    Ex. a = [1, 1, 1, 1, 2, 2, 2, 2, 7, 24, 24, 98, 98]
        b = [7, 7, 7, 7, 8, 8, 98] -> o vetor 'a', sera ordenado com mais velocidade.
