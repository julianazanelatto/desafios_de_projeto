# desafios_de_projeto

Desafio
Um número feliz é um número definido pelo seguinte processo:

• Começando com qualquer número inteiro positivo, substitua o número pela soma dos quadrados de seus dígitos.
• Repita o processo até que o número seja igual a 1 (onde ficará), ou faça um loop infinito em um ciclo que não inclua 1.
• Aqueles números para os quais esse processo termina em 1 são felizes.
• Retorna true se n for um número feliz e false se não for.

Escreva um algoritmo para determinar se o número n é feliz.

Entrada
A entrada será feita por um número inteiro, correpondente ao valor de entrada para verificar se  o número é feliz ou não.

Saída
Retorne true, caso o número seja feliz, e retorne false, caso o número não seja feliz.

Olhando com mais calma percebi que estava faltando dois ponto:
- Atribuir o resultado parcial a variável que é avaliada (para números maiores)
- Zerar o resultado_parcial. Assim, ele não influencia no próximo número a ser verificar (caso contrário, o número apenas cresce)


Dica para os desafios de código: Faça seu código na IDE também. Assim você poderá debugar e entender todas as instruções do seu código.

Confira o resultado abaixo:

![resultado_desafio](https://user-images.githubusercontent.com/81716096/207997798-c73e16da-ad69-494f-b27e-38190648a7dc.png)
