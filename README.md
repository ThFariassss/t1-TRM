# t1-TRM
Trabalho de Assembly TRM -  Thiago Farias e Yan Pantoja

#Programa 1:
O programa foi projetado para gerar e armazenar os 15 primeiros números ímpares em posições consecutivas da memória. O programa inicializa um contador e um registrador com o primeiro número ímpar. Em seguida, entra em um loop que se repete 15 vezes. A cada iteração, o número ímpar atual é salvo em uma posição de memória, e tanto o número (incrementado em 2 para obter o próximo ímpar) quanto o ponteiro de memória são atualizados

#Programa 2:
O programa gera os 15 primeiros números da sequência de Fibonacci e os armazena em posições de memória consecutivas. A lógica começa inicializando dois registradores com os primeiros termos da sequência, 0 e 1. O programa então entra em um loop que se repete 15 vezes.

#Programa 3:
O programa inicializa um registrador  com o primeiro elemento do array, tratando-o como o maior valor encontrado até o momento. Em seguida, ele percorre o restante do array, elemento por elemento. A cada iteração, o valor do elemento atual é comparado com o maior valor já registrado. Se o elemento atual for maior, ele substitui o valor antigo, tornando-se o novo "maior número". Caso contrário, o programa simplesmente avança para o próximo elemento.

#Programa 4:
O programa transforma todos os números de um array em ímpares. Ele verifica cada número: se um número for par, o programa soma 1 a ele; se já for ímpar, ele o mantém como está. O novo array, contendo apenas números ímpares, é salvo em outra área da memória.

#Programa 5:
O programa procura em um array por dois números diferentes que somem exatamente 10. Ele compara cada número com todos os outros até encontrar um par que funcione. Ao encontrar o par, o programa salva os endereços de memória desses dois números e termina.

#Programa 6:
O programa  implementa um algoritmo para inverter a ordem dos elementos de um array diretamente na memória (uma operação conhecida como "in-place"). Ele faz isso trocando os elementos das extremidades do array e movendo-se progressivamente para o centro.

#Programa 7:
Não conseguimos implementar.

#Programa 8:
O programa imprime dois nomes, um após o outro, no console. Ele faz isso enviando o endereço de memória de cada nome para a porta de saída do sistema, localizada no endereço 0xf008.

#Programa 9:
O código determina se uma string é um palíndromo. A lógica compara o primeiro caractere com o último, o segundo com o penúltimo, e assim por diante, caminhando das extremidades para o meio. Se o programa encontrar um par de caracteres que não combinam, ele para e retorna 0 (falso). Se chegar ao centro sem encontrar falhas, ele retorna 1 (verdadeiro).

#Programa 10:
O programa conta quantas vezes cada vogal (A, E, I, O, U) aparece em uma string, ignorando se a letra é maiúscula ou minúscula. Ele percorre a string caractere por caractere e, ao encontrar uma vogal, incrementa o contador correspondente. No final, os totais de cada vogal são salvos na memória.
