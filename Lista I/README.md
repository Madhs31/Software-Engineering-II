
# LISTA DE EXERCICIOS 01

## 1. Crie uma aplicação para efetuar o cálculo do índice de massa corporal. Considere os seguintes critérios: 
1) Ao executar o script a aplicação deve solicitar a entrada do nome da pessoa. 
2) Na sequência a aplicação deve solicitar que seja informada a altura da pessoa em centímetros. 
3) Na sequência a aplicação deve solicitar que seja informado o peso da pessoa. 
4) Após as estradas de dados, atente-se a conversão das informações para dados do tipo float. 
5) Converta a altura recebida em centímetros para metros. (basta dividir a altura por 100). 
6) Internamente a aplicação deve executar o cálculo do índice de massa corporal através da expressão: M = peso (quilos) ÷ altura² 
7) Após identificar o índice de massa corporal o sistema deverá classificar em faixas descritivas utilizando os critérios abaixo:

- Se M estiver abaixo de 16 : Baixo peso muito grave
- Se M estiver entre 16 e 16,99: Baixo peso grave
- Se M estiver entre 17 e 18,49: Baixo peso
- M estiver entre 18,50 e 24,99: Peso normal
- Se M estiver entre 25 e 29,99: Sobrepeso
- Se M estiver entre 30 e 34,99: Obesidade grau I
- Se M estiver entre 35 e 39,99: Obesidade grau II
- Se M for maior que 40: Obesidade grau III
  
8) Ao término o sistema deve fornecer a seguinte saída para o usuário: **“<Nome> possui índice de massa corporal igual a <m> , sendo classificado como: .”** (As informações em vermelho são variáveis e devem ser substituídas pelos seus respectivos valores calculadas dentro da aplicação)

## 2. Crie uma aplicação capaz de identificar a faixa etária com base na idade informada pelo usuário. Considere os seguintes critérios: 

- Se a idade informada for maior ou igual a 0 e menor que 15, exibir a mensagem “Criança”. 
- Se a idade informada for maior ou igual a 15 e menor que 30, exibir a mensagem “Jovem”. 
- Se a idade informada for maior ou igual a 30 e menor que 60, exibir a mensagem “Adulto”. 
- Se a idade informada for maior ou igual a 60, exibir a mensagem “Idoso”.
  
Fique à vontade para utilizar qualquer uma das funções aprendidas para exibição de dados para o usuário.

## 3. Desenvolva uma aplicação em JS que receba as 3 notas, calcule e imprima a média ponderada.

Um aluno está encontrando dificuldades para entender como é composta a média final de determinada disciplina, a qual é composta pelas três notas seguintes:

| Nota | Peso da Nota |
| --- | --- |
| Atividade prática em laboratório | 2 |
| Prova do semestre | 5 |
| Trabalho Teórico | 3 | 
 
A média ponderada é calculada pela fórmula:
((peso1 * nota1) + (peso2*nota2)+(peso3*nota3))/ (soma dos pesos)
Após concluir a média, o algoritmo deverá classificá-la conforme tabela abaixo.

| Média ponderada | Classificação |
| --- | --- |
| Acima de 9 a 10 | A |
| Acima de 8 a 9 | B |
| Acima de 7 a 8 | C | 
| Acida de 6 a 7 | D |
| Acima de 5 a 6 | E |
| 0 (zero) a 5 | F | 
 
Ao término, a aplicação deverá gerar como saída:

**A média do aluno é: 99,99 e a sua classificação é X**
 
## 4. Desenvolva uma aplicação JS que efetue a leitura da distância em quilômetros do frete, a quantidade de peças que serão transportadas, a região (em número) e determine se o cliente quer rastreamento e calcule e imprima o valor final do frete. 

<br> Uma empresa do ramo metalmecânico está realizando uma pesquisa com transportadoras para verificar o preço do transporte de seus produtos destinados a clientes em outros estados. Após a pesquisa, foi selecionada uma transportadora, com o qual foi fechado o contrato para a entrega dos produtos.

<br> O cliente pode escolher se deseja rastrear sua entrega ou não. Assim, deve ser feita a seguinte pergunta:
<br>**"Deseja rastreamento? (S - Sim / N - Não)"**
<br> Se a resposta for "Sim" , será cobrada uma taxa adicional de R$ 200,00 pelo frete.

<br>  O valor do frete é calculado com base no número de peças transportadas, na região de entrega e na distância percorrida (em milhas).

- Até 1.000 peças → O valor do frete é determinado pela região, conforme tabela específica. O custo é cobrado pela peça transportada.
- Acima de 1.000 peças →
- O valor normal é aplicado para as primeiras 1.000 peças.
- Para as peças excedentes, há um desconto conforme a região de destino.

**Exemplo:**
Um cliente compra 1.200 peças para entrega na Região 1 (Sudeste) . O valor base do frete na região é R$ 1,20 por peça . Para as 200 peças excedentes , aplica-se um desconto de 12% , resultando em um valor de R$ 1.056 por peça .

<br> O cálculo será realizado da seguinte forma:

- 1.000 peças → 1.000 × 1,20 = R$ 1.200,00
- 200 peças excedentes → 200 × 1.056 = R$ 211,20
- Total do frete = R$ 1.411,20

A distância percorrida no transporte deve ser informada, pois, para cada milha percorrida , será consumido 1 litro de combustível . Esse dado deve ser registrado no início do algoritmo.

<br>Por questões logísticas, a empresa realiza entregas apenas para as seguintes regiões:

- Sul
- Sudeste
- Centro-Oeste

Cada uma dessas regiões possui um valor de frete específico, de acordo com a quantidade de peças transportadas, conforme a tabela:


| Região | Nome da região | Valor do frete para até mil peças | Valor do frete para mais de mil peças |
| --- | --- | --- | --- |
| 1 | Sul | R$ 1,00 | 10% |
| 2 | Sudeste | R$ 1,20 | 12% |
| 3 | Centro- | R$ 1,30 | 13% |

**Ao término, devem ser exibidas as seguintes informações:**
- Taxa do rastreamento: 999,99
- Valor do frete pelas peças: 9999.99 
- Valor do frete por quilômetro: 999.99 
- Total do frete: 999.99 
 

## 5. Desenvolva uma aplicação que Calcule o valor da hora trabalhada, conforme as regras apresentadas na tabela

 Sabendo que uma rede hoteleira deseja informatizar sua folha de pagamento, desenvolva em pseudocódigo uma solução conforme regras apresentadas pela empresa, de acordo com as especificações abaixo: O funcionário possui os seguintes dados de entrada: código, número de horas trabalhadas no mês, turno de trabalho (M – matutino, V – vespertino ou N – noturno), categoria (F – funcionário, G – gerente). Faça um algoritmo que: - Leia as informações dos funcionários: código (inteiro), número de horas trabalhadas (inteiro) no mês, turno (caractere) e categoria (caractere). Não leia somente o valor da hora trabalhada (real), pois será calculada. - Considere sempre a digitação de uma única letra para representar o turno de trabalho e a categoria do funcionário, conforme as tabelas:

| Turno | Descrição do turno |
| --- | --- |
| M | Matutino |
| V | Vespertino |
| N | Noturno |

| Categoria | Descrição da categoria |
| --- | --- |
| G | Gerente |
| F | Funcionário |
 
**- O valor do salário-mínimo deve ser solicitado pelo algoritmo, pois ele varia de estado para estado e a rede de hotéis está distribuída por todo o País. Utilizar o comando de seleção múltipla (ou um comando escolha e outro pode ser se encadeado – não utilizar se simples para esse item) para testar a categoria e o turno para calcular o valor da hora trabalhada.**

| Categoria | Turno | Porcentagem |  |
| --- | --- | --- | --- |
| G | M ou V | 4% do salário mínimo estadual |  |
| F | N | 2% do salário mínimo estadual |  |
| F | M ou V | 1% do salário mínimo estadual |  |

 
 **- Calcule o salário inicial do funcionário com base no valor da hora trabalhada e no número de horas trabalhadas. - Calcule o valor do auxílio-alimentação recebido pelo funcionário de acordo com seu salário inicial, conforme a tabela a seguir. Utilizar o comando de seleção composto encadeado.**

| Salário Inicial | Auxílio-Alimentação |
| --- | --- |
| Até 800,00 | 25% do salário inicial |
| Acima de 800,00 até 1.200,00 | 20% do salário inicial |
| Acima de 1.200,00 | 15% do salário inicial | 
 
 **- Imprima como saída o código, número de horas trabalhadas, valor da hora trabalhada, salário inicial, auxílio alimentação e salário final (salário inicial + auxílio-alimentação).**

## 6. Crie uma aplicação para efetuar cálculo aritméticos de soma e subtração.
Considere os seguintes critérios:
1) Ao executar o script a aplicação deve solicitar a entrada de um número, seguido de uma operação de soma ou subtração e posteriormente seguido de um segundo número.
2) A operação deve ser inserida pelo usuário de forma textual, ou seja, quando o sistema solicita a operação o usuário deve informar o texto ‘soma’ ou ‘subtração’ (sem as aspas).
3) Na sequência o sistema deve enviar os parâmetros para uma função efetuar o devido cálculo. Exemplo: calculo(num1, num2, operacao).
4) A função deve executar o cálculo com base na operação informada pelo usuário e na sequência deve retornar o valor encontrado.
5) Ao término o sistema deve fornecer a seguinte saída para o usuário:
**“O resultado é: <resultado>.”** (A informação em vermelho é uma variável e deve ser substituída pelo seu respectivo valor calculada dentro da aplicação)

## 7. Faça um script que receba uma data no formato “dd/mm/aaaa” e escreva a data por extenso. 
**Dica:** use a função “split” de uma string que quebra a string em pedaços dado um separador como argumento da função. Nesse caso, o separador é a barra (/) da data. 
**Exemplo: Para a entrada “31/08/2012” deve ser escrito “31 de agosto de 2012”.**

