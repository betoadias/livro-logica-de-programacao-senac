# Capítulo 1 - Lógica de programação e suas representações

## Objetivos
- Entender o conceito de lógica de programação;
- Entender o conceito de algoritmo;
- Utilizar refinamentos sucessivos;
- Conhecer as formas de representação de um algoritmo.

## Lógica
As pessoas utilizam lógica no cotidiano sem perceber, chegam mesmo a citá-la, sem entender direito o seu significado.

Segundo o dicionário Aurélio, **lógica é a coerência de raciocínio** ou ainda **lógica é a sequência coerente, 
regular e necessária de acontecimentos**.

Por exemplo: 

- O número 3 é menor do que o número 5;
- O número 7 é maior do que o número 5;
- Logo, o número 3 é menor do que os números 5 e 7.

---

- Quando chove, não é preciso regar as plantas do jardim;
- Hoje choveu;
- Logo, hoje não é preciso regar as plantas do jardim.

---

- O Brasil fica na América do Sul;
- A América do Sul fica no continente americano;
- Logo, os brasileiros são americanos.

Porém, às vezes, o raciocínio funciona desordenadamente. Quantas vezes você já ouviu as frases 
**"E se acontecer aquilo?"** ou **"É, mas eu não tinha pensado nisso!"**.

No exemplo abaixo, estão descritas as ações de quem vai a um banco, porém, veja se seria possível retirar o 
dinheiro obedecendo à sequência descrita.

1. Sair do banco;
2. Aguardar a vez de ser atendido;
3. Entrar na fila do caixa;
4. Digitar a senha;
5. Entrar no banco;
6. Informar o valor a ser retirado;
7. Procurar a fila do caixa;
8. Pegar o comprovante do saque, o cartão eletrônico e o dinheiro;
9. Entregar o cartão eletrônico ao funcionário que atende no caixa;
10. Conferir o valor em dinheiro.

Você conseguiria retirar o dinheiro? Com  certeza não, pois embora as ações estejam corretas, a sequência
está errada. 

**Utiliza-se a lógica para ordenar e corrigir pensamentos e ações voltados para a solução de problemas**.

Na ordem acima, a primeira ação é sair do banco, como se pode sacar dinheiro em um banco estando fora dele? 
Após parar para analisar os passos e usar a lógica, chegamos aos passos corretos abaixo:

1. Entrar no banco;
2. Procurar a fila do caixa;
3. Entrar na fila do caixa;
4. Aguardar a vez de ser atendido;
5. Entregar o cartão eletrônico ao funcionário que atende no caixa;
6. Informar o valor a ser retirado;
7. Digitar a senha;
8. Pegar o comprovante do saque, o cartão eletrônico e o dinheiro;
9. Conferir o valor em dinheiro.
10. Sair do banco;

## Lógica de programação
Falar em lógica de programação significa apenas contextualizar a lógica na programação de computadores, buscando a melhor 
sequência de ações para solucionar determinado problema.

Na programação de computadores, o nome dessa sequência de ações é algoritmo, que é, de maneira bem simples, a sequência 
passos ou ações para atingir um objetivo.

Já a ação, é um fato que, a partir de um estado inicial, após um período de tempo finito, produz um estado final previsível 
e definido. 

Por exemplo: a ação de abrir uma porta.

<img width="717" height="157" alt="ação abrir" src="https://github.com/user-attachments/assets/3b852e53-3eef-403f-9305-55f0ed9acfff" />

Ao objeto porta no estado inicial fechada, é aplicada a ação abrir por um tempo 
determinado em segundos, levando ao estado final porta aberta, previsível e definido, pois é esperado que, quando se abre algo, 
principalmente qualquer porta, no final, ela esteja aberta.

A partir desse exemplo, pode-se redefinir o conceito de algoritmo como a descrição de um conjunto de ações que, quando obedecidos, 
seguindo um padrão de comportamento definido (qualquer pessoa vai agir da mesma forma), resulta uma sucessão finita de passos, 
atingindo-se o objetivo.

Veja a seguir dois exemplos de padrão de comportamento.

### Problema 1: Determine o sétimo número da sequência: 1, 3, 5, 7, 9, 11

**Solução:** Analisando-se o problema, pode-se constatar que o padrão de comportamento, ou seja, a regra de formação, é sempre 
somar 2 ao número anterior para obter o próximo número. Então, o sétimo número é o 13, obtido pela soma de 2 ao sexto número que 
é o 11, logo 11 + 2 = 13.

---

### Problema 2: Qual a sequência de ações para se abrir uma porta?

**Solução:**
1. Andar até a porta;
2. Pegar na maçaneta;
3. Girar a maçaneta;
4. Puxar a porta;

Ao se estabelecerem as ações, é definida uma sequência que seria naturalmente executada por qualquer pessoa, determinando-se um 
padrão de comportamento (qualquer pessoa agiria da mesma forma, executando as ações descritas na mesma ordem).








