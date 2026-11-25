# Introdução

## Objetivos
- Entender o que são hardware e software;
- Familiarizar-se com os termos de programação.

## Conceitos iniciais
Desde os primórdios, o ser humano busca automatizar tarefas rotineiras para ter mais rapidez e menos esforço. 
Isso possibilitou o surgimento de instrumentos como a roda, roldana, alavanca, carro e até o computador.

No entanto, as tarefas que devem ser realizadas pelo computador de forma automática 
têm de ser anteriormente pensadas e colocadas em uma sequência de ações para, 
posteriormente, serem inseridas na máquina. 
A essa sequência de ações denomina-se **programa** e a fase de formular soluções 
que gerem programas denomina-se **lógica de programação**.

O objetivo principal dos programadores é resolver problemas por meio de soluções lógicas
para obter os melhores resultados. Porém, se as soluções não forem bem planejadas, com certeza 
essa meta não será atingida.

Antes de iniciar o estudo de lógica de programação, conheça alguns conceitos básicos importantes.

## Hardware
Todo computador é composto de duas partes essenciais para o seu funcionamento, o hardware e o software. 
Sem uma dessas partes, ele não pode funcionar. Para entender melhor o que isso significa, pense em um carro,
composto de uma parte mecânica e outra elétrica. O carro não funciona apenas com uma parte, pois é impossível 
dar a partida sem a ignição (parte elétrica) ou dirigi-lo sem o volante (parte mecânica).

**Hardware** é a parte física do computador, ou seja, é o conjunto formado pelos circuitos eletrônicos, 
processador, gabinete, pelas placas, etc. Essa palavra inglesa é bem significativa, 
onde **hard = rígido, duro (físico)** e **ware = mercadoria (parte)**.

### Funcionamento e componentes do computador
O computador funciona, basicamente, como uma máquina que recebe dados, processa-os 
e retorna um ou mais dados como resultado.

**Entrada** > **Computador (processamento)** > **Saída de dados**

Para funcionar, o computador deve conter os seguintes componentes:

- **Entrada de dados**
- **Periférico de entada de dados**
- **Memória principal**
- **UCP**
   - ULA
   - UC
- **Memória auxiliar**
- **Periférico de saída de dados**
- **Saída de dados**
  
#### Periféricos de entrada de dados (Input):
Dispositivos que recebem os dados do meio externo e são capazes de converte-los para pulsos elétricos
compreensíveis pelo computador. O teclado é um exemplo de periférico de entrada, quando uma tecla é pressionada, 
um dado é enviado para o computador, que o interpreta e executa a operação.

#### Unidade central de processamento (UCP) ou Central process unit (CPU):
Responsável por todas as operações realizadas no computador, divide-se em:

- **Unidade lógica e aritmética (ULA) ou Arithmetic logic unit (ALU):** Responsável pelas operações
  lógicas e aritméticas.

- **Unidade de controle (UC) ou Control unit (CU):** Responsável pelo fluxo de informações dentro do computador.
  Essa unidade controla a entrada e a saída de dados, envia e recebe dados das memórias e controla a
  unidade lógica e aritmética.

- **Memória principal:** Quando um programa está sendo executado, são processados vários dados através de vários
  comandos. Para que esse processamento tenha velocidade, é necessário que dados e comandos estejam sempre à
  disposição e que não sejam perdidos. Isso é viabilizado pela **memória principal**, onde a **unidade de controle** armazena dados e comandos e carrega-os, sempre que necessário, de volta para o processamento.
Cada parte da memória pode armazenar dados, cada parte da memória localiza-se em determinada posição, 
chamada endereço de memória, reconhecido pelo computador. Para que não seja preciso "decorar" os endereços, 
você pode referenciar cada parte da memória com um nome, agilizando o acesso aos dados. A memória principal divide-se em:
   - **Memória read-only memory (ROM) ou Memória somente para leitura:** Contém dados que configuram o computador ao ser ligado e que não podem ser gravados ou alterados. nessa memória são gravados os dados do fabricante da máquina, como a configuração da placa do computador, por exemplo.
     
   - **Memória random access memory (RAM) ou Memória de acesso aleatório:** Utilizada na execução de um programa para o armazenamento e a leitura de dados e comandos. Essa memória atua enquanto o computador estiver ligado, quando ele é desligado, os dados contidos nela são perdidos (apagados).

- **Memória auxiliar ou secundária:** Utilizada para guardar dados permanentemente. Exemplos de memórias auxiliares são fitas magnéticas, discos rígidos, cd-rom, dvd-rom, etc. A leitura e a gravação de dados nas memórias auxiliares são feitas pelos periféricos de entrada e saída de dados.

- **Periféricos de saída de dados (Output):** Dispositivos que recebem dados do computador, na forma de pulsos elétricos, e de, alguma maneira (definida por cada periférico), convertem esses pulsos em dados como por exemplo sons, números, letras, imagens, etc, para o meio externo. A impressora é um exemplo de periférico de saída, quando uma impressão é solicitada, o computador envia os dados para a impressora, que os interpreta e os imprime no papel. Exemplos de periféricos de saída são as impressoras, placa de vídeo, placa de som, placa de fax/modem, placa de rede, etc.

- **Periféricos de entrada e saída de dados (Input/Output ou I/O):** Observe que drivers, placa de faz/modem, modem e placa de rede aparecem nos exemplos de periféricos de entrada e nos exemplos de periféricos de saída. Isso porque eles são periféricos que tanto recebem dados para o computador como os transferem para o meio externo, isto é, são periféricos de entrada e saída de dados.

## Software
Software é o conjunto dos programas que comandam o funcionamento do hardware. Programas são feitos a partir de algoritmos, sequências de instruções para se atingir um objetivo.

Depois de pronto, o algoritmo é convertido para uma linguagem de programação. O produto dessa conversão é um programa.

### Programa
É o conjunto de instruções que contém as operações necessárias para, a partir de dados inseridos, obter um resultado que será disponibilizado por algum dispositivo de saída.

Por exemplo, quando você clica nos botões 1, +, 5 e = da calculadora do Windows, após receber os números 1 e 5, a operação + e o sinal de =, terá como instrução realizar a soma dos números 1 e 5 e retornar o resultado, que é o número 6.

### Linguagem de programação
É o conjunto de representações e/ou regras utilizadas para criar programas. Por meio delas você estabelece uma comunicação com o computador, fazendo com que ele compreenda e execute o que você determinar. A proximidade com a linguagem humana determina o nível da linguagem de programação.

Existem três níveis de linguagens de programação:

- **Linguagem de máquina:** É a linguagem compreendida pelo computador, cujas instruções são representadas por vários 0 e 1 (bits).

- **Linguagem de baixo nível:** É a linguagem que utiliza instruções próximas à compreensão da máquina (linguagem de máquina). Essa linguagem exige grande conhecimento de hardware. Exemplo: Assembler.

- **Linguagem de alto nível:** É a linguagem cujas instruções estão próximas do nível de compreensão humana (linguagem humana). Exemplos, Java, C#, Python, etc.

  **Homem** <============================================> **Maquina**

             Nível alto                       Nível baixo

  ### Sistema
  Para entender o que é sistema, pense no corpo humano, formado por vários subsistemas (respiratório, nervoso, urinário, cardiovascular, musculoesquelético, etc). Os vários subsistemas formam o sistema orgânico do corpo humano.

  Cada subsistema tem uma função no corpo e é formado por órgãos que também têm a sua função específica. Por exemplo, o subsistema cardiovascular, além das veias e outros órgãos, é formado pelo coração, que tem como função principal bombear o sangue.

  Na informática, o conceito de sistema é semelhante, ou seja, é **um conjunto de subsistemas ou módulos formados por programas que executam operações específicas**. Como exemplo temos o sistema videolocadora, que é composto por três módulos, cadastro de fitas, cadastro de clientes e locação de fitas. A sua meta neste livro é conhecer a lógica necessária para construir um sistema de informação.

  

                                            

