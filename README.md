# players

**ANÁLISE LÓGICA, RACIONAL DO DESAFIO: "jogo hipotético muito semelhante a Banco Imobiliário"**

Diante de um grande dilema entre desenvolver um algorítimo imperfeito e escrever um texto analítico, escolha o segundo:

O descritivo do desafio possui duas falhas maiores, ou seja, 
* a) não informar claramente qual o valor do aluguel da propriedade e 
* b) não informar claramente o preço da propriedade no momento da compra, deixando apenas uma informação subentendida e não claramente informada. 

**Nos itens 1 e 2 abaixo as questões são um pouco mais esclarecidas.**

**Item 1:**
Qual o preço da propriedade para a compra?
Está no texto: "Ao comprar uma propriedade, o jogador perde o dinheiro e ganha a posse da propriedade."
Faço o seguinte questionamento: O jogador perde todo o saldo que possui e a propriedade passa a ter o valor do saldo que o jogador tinha até então? SE SIM, o jogador inicia com 300 ENTÃO a propriedade irá valer 300.
Veja que aqui estou fazendo uma suposição e nas empresas não devemos fazer suposições, mas sim trabalhar com processos reais e muito bem esclarecidos.

**Item 2:**
Qual o preço do aluguel da propriedade? Ou ainda melhor, como é definido o preço do aluguel da propriedade?
Falta informação que dentro da lógica do jogo faz grande diferença, ou seja, toda informação deve ser devidamente esclarecida quando estamos criando processos informáticos organizacionais.

**Faço aqui uma análise lógica dos tipos de jogadores segundo os seus comportamentos com os questionamentos acima feitos:**

**-->** O jogador impulsivo tem a OPÇÃO de compra de qualquer propriedade sobre a qual ele parar, mas só é possível comprar, segundo a regra do jogo, quando a propriedade está sem proprietário.

**-->** O jogador exigente nunca irá comprar uma propriedade porque ele só compra a propriedade quando o aluguel for maior do que 50, porém, só é possível comprar, segundo a regra do jogo, quando a propriedade está sem proprietário e ainda, não está claro no texto, qual a forma de calculo do valor do aluguel da propriedade.

**-->** O jogador cauteloso nunca irá comprar porque para calcular e o comprar permanecer com uma reserva com saldo de 80 unidades, segundo regra do jogo, é preciso saber o valor da propriedade e essa informação não foi informada com clareza, eu fiz uma suposição no item 1 acima.

**-->** O jogador aleatório precisa jogar uma moeda e cair a opção que ele escolheu(probabilidade de 50%) para comprar a propriedade desde que esteja sem dono. Então o jogador aleatório tem contra ele muitas variáveis contra a compra.


**Portanto**,
segundo a lógica com falta de informações conforme acima exposto, o comportamento que reúne mais chances de vencer é o jogador: IMPULSIVO.

Devemos entender que um profissional Analista de sistemas, Desenvolvedor de software, Funcional Organizacional de sistemas informáticos,  deve trabalhar com informação segura, evitar teorização fundamentada no subjetivismo do 'eu acho que', e sempre esclarecer qualquer dúvida que possa ter, se ele atuar na forma de achismos estará:
* a) gastando tempo que poderia ser melhor aproveitado, 
* b) desperdício de recursos financeiros, 
* c) a empresa perdendo a oportunidades de entregar ao mercado uma solução de software inovadora,
* d) gerando retrabalho,
* e) mal clima organizacional.

Desenvolva um modelo de entidades (jogo, partida, jogadores, saldo, tabuleiro, propriedades) versus relacionamento com as regras do negócio nos loops, whiles, ifs, then, calculos (saldo += valor), elses - APENAS - quando todos os requisitos funcionais organizacionais estão claramente esclarecidos.
