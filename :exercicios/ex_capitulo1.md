# Atividade 1 - Montando uma sequência lógica

## Objetivo: Organizar sequências lógicas de ações para chegar a um resultado esperado.

## Tarefa: Organizar placas de trânsito em uma sequência lógica.

### Problema
Um carro sai da cidade de Osasco e vai para a cidade de Embu das Artes percorrendo uma rodovia de 12 quilômetros.
Nessa rodovia, há um trecho em obras no quilômetro 3, uma curva perigosa no quilômetro 5 e uma escola no 
quilômetro 7. Qual a sequência das placas de indicação da estrada?

### Solução

Estou pensando em separar as doze placas referentes a cada um dos quilômetros, o aviso de trecho em obras no quilômetro 3, a curva perigosa no quilômetro 5, a escola no quilômetro 7, também estou pensando em mais duas placas, uma na saída da cidade de Osasco indicando a cidade de Embu das Artes e quantos quilômetros faltam até lá e uma de bem-vindo a Embu das Artes no final.

1. Embu das Artes a 12 KM;
2. 1 KM;
3. 2 KM;
4. Obras no KM 3;
5. 4 KM;
6. Curva perigosa no KM 5;
7. 6 KM;
8. Escola no KM 7;
9. 8 KM;
10. 9 KM;
11. 10 KM;
12. 11 KM;
13. 12 KM - Bem vindo a Embu das Artes.

---

# Atividade 2 - Criando o primeiro algoritmo

## Objetivo: Conhecer a forma de estruturar um algoritmo.

## Tarefa: Descrever os passos necessários para colocar um carro em movimento.

### Problema
Criar um algoritmo para colocar um carro em movimento.

### Solução
Para criar o algoritmo que vai solucionar o problema, você deve colocar as ações na sequência, um em cada linha. Para isso, execute 
os passos a seguir.

1. No começo e fim do algoritmo, deve-se colocar as ações de início e fim, para informar que é daquele ponto que ele inicia e onde termina:

```text
  início

  fim
```
2. Deve-se colocar as ações passo a passo, na ordem entre as ações de início e fim:
   
```text
  início
    Entrar no carro
    Ajustar o banco e os espelhos retrovisores
    Colocar o cinto de segurança
    Colocar o câmbio em "ponto morto"
    Ligar o carro
    Colocar o câmbio na primeira marcha
    Pisar no acelarador
    Soltar o freio de mão
    Soltar a embreagem devagar
  fim
```
---

# Atividade 3 - Refinando as ações do primeiro algoritmo

## Objetivo: Aprender a refinar um algoritmo.

## Tarefa: Montar os refinamentos de um algoritmo.

### Problema
Baseado no algoritmo da atividade 2, refine as ações **Entrar no carro** e **Colocar o câmbio na primeira marcha**.

### Solução

1. O primeiro passo é refinar a ação **Entrar no carro**
   - Para entrar, é necessário abrir a porta do carro. Deve-se prever que a pessoa já esteja diante da porta;
   - Depois, sentar no banco do motorista;
   - Finalmente, fechar a porta do carro e finalizar o refinamento.

   ```
     ref. Entrar no carro
       Abrir a porta
       Sentar no banco
       Fechar a porta
     fim-ref.
   ```
2. O segundo passo é refinar a ação **Colocar o câmbio na primeira marcha**.
   - A primeira ação deve ser pisar na embreagem;
   - A segunda ação, pegar o câmbio;
   - A última ação do refinamento deve ser colocar o câmbio na primeira marcha.
  
   ```
     ref. Colocar o câmbio na primeira marcha
       Pisar na embreagem
       Pegar o câmbio
       Colocar o câmbio na primeira marcha
     fim-ref
   ```
3. Substituindo os refinamentos, veja como fica o algoritmo.

   ```
     início
       Abrir a porta
       Sentar no banco
       Fechar a porta
       Ajustar o banco e os espelhos
       Colocar o cinto de segurança
       Pisar na embreagem
       Pegar o câmbio
       Colocar o câmbio em "ponto morto"
       Soltar a embreagem
       Ligar o carro
       Pisar na embreagem
       Pegar o câmbio
       Colocar o câmbio na primeira marcha
       Acelerar o carro
       Soltar o freio de mão
       Soltar a embreagem devagar
     fim
   ```
   **Obs.: Somente as ações inicio e fim estão em letras minúsculas, pois somente elas e a ação refinamento (ref.) foram apresentadas como comandos ou ações primitivas**. 

