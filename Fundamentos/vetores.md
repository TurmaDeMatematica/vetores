# Fundamentos
Nestes fundamentos, mostraremos o básico de vetores, matrizes, sistemas de coordenadas. 
Tentarei colocar o máximo de ilustrações para obter uma visão geométrica de cada informação matemática. 
Além disso, tentarei passar o conteúdo numa visão top-down, passando primeiro pelos problemas do dia-a-dia, para depois 
formalizar estes problemas em conceitos matemáticos.

Um bom livro disponível na Internet na íntegra é o livro de Jacir J. Venturi de Álgebra Vetorial e Geometria Analítica. 
Certas partes se tornam narrativas históricas, tornando a leitura prazerosa. Ele cobre diversos aspectos e propriedades dos vetores 
que nós usaremos nesses tutoriais, nas disciplinas da área de Processamento Gráfico e no dia-a-dia no desenvolvimento de projetos de 
visualização gráfica.

Geralmente os vetores são utilizados para representar deslocamentos ao invés de posições imediatas. 
Em alguns momentos precisamos trabalhar com deslocamentos:

* De uma cidade para outra, traça uma seta representando seu deslocamento;
* Em um segundo, o carro se desloca de um ponto a outro. Se olharmos de cima, podemos traçar uma seta da origem para o destino;
* Os fótons dos raios solares batem na superfície do espelho e refletem como se fossem bolas quiquando. O sentido e direção desses fótons são importantes para sabermos se eles vão atingir o seu olho (se percebes o raio refletido) ou não;
* Se aplicares um soco num saco de boxe (soco num saco, parece uma cacofonia...), a parte inferior do saco vai para o sentido do murro aplicado, com uma aceleração e velocidade iniciais. A ponta no alto está presa no teto, e como a altura do saco é finita e por causa da força centrípeta, o saco tende a subir. Mas aí o sentido da velocidade se orienta para cima, contra a gravidade. A gravidade reduz a velocidade, fazendo com que o saco pare e depois ganhe velocidade no outro sentido. Devido à pressão do ar, a energia não é conservada, tornando o sistema estável. Tudo isso para dizer que velocidade, gravidade, força do soco e do vento podem ser modeladas como vetores;
* Em circuitos elétricos, existem componentes para controlar a passagem de elétrons como resistores e indutores. A resistência e reatância compõem a impedância, e é onde os campos elétricos e magnéticos são estudadas em conjunto, como campos eletromagnéticos. Porém esses campos contém polarizações diferentes (90 graus de diferença de fase). A polarização pode ser modelada como vetores;
