# O Caso do Vestível Controlador - Fase 1,5

1) Contexto: Após o jogador entrar no politecnico, passando da fase 1, ele passa por uma nova fase, anterior a fase 2, a fase 1,5. Essa fase se passa no hall de entrada do Departamento de informática, para receber as dicas da Ressurgência quer precisa saber se o jogador é confiavel mesmo, então ele fazem um teste, a fase 1,5.

2) Problema: O problema computacional abordado é uma busca no espaço de estados junto a um problema de satisfação de restrições. Há um conjunto ded palavras, e dentro desse conjuto há um subconjunto que satisfaz as restrições propostas, e para encontrar esse conjunto, deve ser feito uma busca dentro do cunjunto original.

3) Texto: ta no drive

4) Solução trivial: fazer um busca por força bruta, testando letra a letra, e verificando se bate com uma das palavras do conjunto, e ao encontrar a palavra, verificar se satisfaz as condições necessarias.

5) Solução esperta: Verificar os tamanhos das palavras, e separar os conjuntos de palavras que cabem em cada sequencia de espaços.Após isso, fazer uma busca com retocesso, e, a cada conjunto possivelmente valido, testar se ele atende as restrições. 