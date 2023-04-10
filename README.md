# Cálculo do Imposto de Renda em Lolipad

Cálculo do Imposto de Renda em Lolipad
Este programa em Java calcula o Imposto de Renda em Lolipad, um país fictício onde todos os habitantes ficam felizes em pagar seus impostos, pois sabem que nele não existem políticos corruptos e os recursos arrecadados são utilizados em benefício da população, sem qualquer desvio.

O programa lê do usuário o valor da renda em Lolis, que é a moeda utilizada em Lolipad, e calcula o imposto devido, segundo a tabela abaixo:

Renda em Lolis	Alíquota
Até 2000.00 Lolis	Isento
De 2000.01 até 3000.00 Lolis	8% sobre o valor que excede 2000.00 Lolis
De 3000.01 até 4500.00 Lolis	8% sobre os primeiros 1000.00 Lolis que excedem 2000.00 Lolis + 18% sobre o valor que excede 3000.00 Lolis
Acima de 4500.00 Lolis	8% sobre os primeiros 1000.00 Lolis que excedem 2000.00 Lolis + 18% sobre os primeiros 1500.00 Lolis que excedem 3000.00 Lolis + 28% sobre o valor que excede 4500.00 Lolis
Se a renda informada for menor ou igual a 2000.00 Lolis, o programa imprime "Isento" na tela.

Como utilizar
Para utilizar este programa, siga os passos abaixo:

Abra um terminal e compile o programa com o comando javac DIO.java.
Execute o programa com o comando java DIO.
Informe o valor da renda em Lolis.
O programa irá calcular o imposto devido e imprimir o resultado na tela, com o símbolo R$ seguido do valor total devido de Imposto de Renda, com duas casas após o ponto. Se o valor de entrada for menor ou igual a 2000, será impressa a mensagem "Isento".
Exemplo de utilização
Suponha que o usuário informou o valor da renda de 3002.00 Lolis. O programa irá calcular o imposto devido da seguinte forma:

A renda é maior que 2000.00 Lolis, mas menor ou igual a 3000.00 Lolis, então o imposto será calculado sobre a parte que excede 2000.00 Lolis, com uma alíquota de 8%.
O valor que excede 2000.00 Lolis é de 1002.00 Lolis.
O imposto devido será de 8% sobre 1000.00 Lolis, que é igual a 80.00 Lolis, mais 18% sobre 2.00 Lolis, que é igual a 0.36 Lolis.
O valor total devido de Imposto de Renda será de 80.36 Lolis.
O programa irá imprimir o seguinte resultado na tela:

ruby
Copy code
R$ 80.36
Autoria e Contribuições
Este programa foi desenvolvido por Maria Andrade  e disponibilizado em para desafio da DIO. 




ID	Nome	Sobrenome	Idade
1	João	Silva	27
2	Maria	Santos	35
3	Pedro	Oliveira	18
4	Ana	Souza	42
markdown
Copy code
| ID | Nome | Sobrenome | Idade |
|----|------|-----------|-------|
| 1  | João | Silva     | 27    |
| 2  | Maria | Santos    | 35    |
| 3  | Pedro | Oliveira | 18    |
| 4  | Ana  | Souza     | 42    |
