# players

**ANÁLISE LÓGICA, RACIONAL DO DESAFIO: "jogo hipotético muito semelhante a Banco Imobiliário"**

O descritivo do desafio possui duas falhas maiores, ou seja, 
* a) não informar claramente qual o valor do aluguel da propriedade e 
* b) não informar claramente o preço da propriedade no momento da compra, deixando apenas uma informação subentendida e não claramente informada. 

**Nos ítens 1 e 2 abaixo eu esclareço um pouco mais essas questões.**

**Ítem 1:**
Qual o preço da propriedade para compra?
Está no texto: "Ao comprar uma propriedade, o jogador perde o dinheiro e ganha a posse da propriedade."
Faço o seguinte questionamente: O jogador perde todo o saldo que possui e a propriedade passa a ter o valor do saldo que o jogador tinha até então? SE SIM, o jogador inicia com 300 ENTÃO a propriedade irá valer 300.
Veja que aqui estou fazendo uma suposição e nas empresas não devemos fazer suposições mas sim trabalhar com processos reais e muito bem esclarecidos.

**Ítem 2:**
Qual o preço do aluguel da propriedade? Ou ainda melhor, Como é definido o preço do aluguel da propriedade?
Falta informação que dentro da lógica do jogo faz grande diferença, ou seja, toda informação deve ser devidamente esclarecida.

**Faço aqui uma análise lógica dos tipos de jogadores segundo os seus comportamentos com os questionamentos acima feitos:**

**-->** O jogador impulsivo tem a OPÇÃO de compra de qualquer propriedade sobre a qual ele parar, mas só é possível comprar, segundo a regra do jogo, quando a propriedade está sem proprietário.

**-->** O jogador exigente nunca irá comprar uma propriedade porque ele só compra quando o aluguel for maior do que 50, porém, só é possivel comprar, segundo a regra do jogo, quando a propriedade está sem proprietário e ainda, não está claro no texto, qual o valor do aluguel da propriedade.

**-->** O jogador cauteloso nunca irá comprar porque para calcular uma reserva de 80 saldo é preciso saber o valor da propriedade e essa informação não foi informada com clareza, eu fiz uma suposição no ítem 1 acima.

**-->** O jogador aleatório precisa jogar uma moeda e cair a opção que ele escolheu(probabilidade de 50%) para comprar a propriedade desde que esteja sem dono. Então o jogador aleatório tem contra ele muitas variáveis contra a compra.


**Portanto**,
segundo a lógica com falta de informações conforme acima exposto, o comportamento que reune mais chances de vencer é o jogador: IMPULSIVO.

Eu entendo que um profissional Analista, Desenvolvedor deve trabalhar com informação segura, evitar teorização fundamentada no subjetivismo do 'eu acho que', e sempre esclarecer qualquer dúvida que possa ter, se ele atuar na forma de achismos estará:
* a) gastando tempo e incorrendo em retrabalho, 
* b) recursos financeiros, 
* c) a empresa perdendo a oportunidades de entregar ao mercado uma solução de software inovadora,
* d) gerando retralho,
* e) mal clima organizacional.

Eu poderia facilmente desenvolver um modelo de entidades (jogo, partida, jogadores, saldo, tabuleiro, propriedades) versus relacionamento onde as regras do jogo/negócio estaria nos laços, if, else.

O senhor deseja avaliar os meus códigos escritos em Python? Convido a **analisar os repositórios** do github valoreio onde os programas foram 100% feitos por mim. Aproveito também para convidar a **analisar os portfólios** www.valore.io e adm4orgpar.heroku.com que, de igual maneira, feitos por mim em sua totalidade.

Atenciosamente,
Marcos
