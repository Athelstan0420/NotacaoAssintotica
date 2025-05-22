    
    """
    # busca linear = Algoritmo usado para encontrar um determinado valor em uma lista ou vetor;
    buscaLinear(vetor, n, k):
        i = 1
        enquanto i ≤ n faça
        se vetor i == k então
            retorne i
        caso contrário
            i = i + 1
        retorne -1
    """
    
    # # Deploy:
    # # Busca a posição de um elemento em um vetor não ordenado:
    # def buscaLinear(vetor, lenvetor, busca):
    #     i = 0
    #     while i <= lenvetor:
    #         if vetor[i] == busca:
    #             return i
    #         else:
    #             i = i + 1
    #     return -1
    # array = [5,67,3,6,54,56,42,45,454]
    # len = len(array)
    # quero = int(input("Quero: "))
    # print(buscaLinear(array,len,quero))
    
    
    """
    
    # Algoritmo: Busca linear(vetor ordenado):
    BuscaLinear(vetor, n, k)
        i = 0
        enquanto i ≤ n e k ≥ vetor[i] faça
        se vetor i == k então
        retorne i
        caso contrário
        i = i + 1
        retorne -1
    """
    
    # # Deploy:
    # def buscaLinear_ordenado(vetor, n, k):
    #     i = 0
    #     while i <= n and k >= vetor[i]:
    #         if vetor[i] == k:
    #            return i
    #         else:
    #             i = i + 1
    #     return -1
    
    # array = [5,67,3,6,54,56,42,45,454]
    # vetord = sorted(array) # Ordena o vetor;
    # len = len(array)
    # quero = int(input("Quero: "))
    # print(buscaLinear_ordenado(vetord,len,quero))
    
    
    """
    ------------------------------------------------------------------------------
    A busca linear em um vetor qualquer parece mais eficiente do que a busca em
    um vetor ordenado;
    
    No melhor caso eles são iguais;
    No pior caso, na média, a busca linear é melhor;
    
    - A linha 2 tem um custo maior e é executada n + 1 vezes em ambos os
    casos. (Mais tempos);
    - Esse custo a mais faz com que o fator multiplicativo e a constante
    aumentem.
    -------------------------------------------------------------------------------
    
    # Notação Assintótica:
    
        ("Esse algoritmo vai continuar sendo eficiente mesmo com uma entrada muito grande ?")
        
        Utilizada para analisar e descrever o desempenho de um algoritmo:
        
            - Analisa o Tempo de execução;
            - Analisa Memória gasta;
            - Tamanho da entrada
            - Identificar o melhor e o pior caso;
            - Independe da linguagem, hardware ou algoritmo(Necessidade apenas da lógica do algoritmos);
            - Importante! pois permite comparar a eficiência de diferentes algoritmos.

    
    -------------------------------------------------------------------------------
    
    0(1) = Melhor solução(vetor de tamanho 0) - tempo de execução;
    
    0(log n) = Aumento logaritmico (Busca Binária);
    
    0(n) = Algoritmo linear - crescimento proporcional ao temanho da entrada;
    
    0 (n log n ) = componente linear e logaritmo (Quick Sort, Merge Sort);
    
    0(N_aoQuadrado) = (Selection Sort, Bubble Sort) Se aumenta a entrada aumenta o tempo de execução ao quadrado;
    
    0(N_aoCubo) = Aumenta a entrada, triplica o tempo de execução;
    
    0(2 elevado a N) = algoritmo exponencial (aumento exponencial);
    
    0(n!) = algoritmo fatorial (cresce fatorialmente); 
    
    -------------------------------------------------------------------------------
    
    """

