
Na última aula você criou um programa que escrevia coisas na tela do computador. Nessa aula vamos entender o que significa cada linha do seu código e porque ele funciona

A linha #include <stdio.h>. 
Uma linguagem de programação executa diversos comandos. Esses comandos ficam listados no que chamamos de bibliotecas. Para que o compilador entenda cada comando, precisamos dizer a ele onde estão listados aquele comandos. É como se fosse um dicionário para o compilador. No código da aula passada, utilizamos o comando "printf", que está listado na biblioteca stdio. STDIO é uma sigla para standard input-output, o que em português significa "entrada e saída padrão". E ".h" nada mais é do que extensão dos arquivos de biblioteca da linguagem C.

Em geral as linguagem têm mais de uma biblioteca. Cada biblioteca tem seu conjunto de comandos específicos. Invocamos cada biblioteca na medida em que precisamos dos seus comandos. Existe, por exemplo, a biblioteca "math.h" que traz comados matemáticos mais avançados como raiz quadrada e expoentes. O conjunto de bibliotecas de uma linguagem representa do que uma linguagem é capaz. Conhecê-las é fundamental para dizer que você realmente sabe utilizar uma linguagem de forma avançada. 

No link abaixo, você encontra a lista completa de bibliotecas da Linguagem C, bem como todos os comandos de cada biblioteca. Mas ainda não temos conhecimento para entender o que tudo aquilo quer dizer. Assim que prendermos "Funções", você compreenderá o que está escrito e como utilizar cada comando. Por ora, explore um pouco para ver como a linguagem C é rica de possibilidades.
https://www.tutorialspoint.com/c_standard_library/index.htm


A linha int main ()
"int main ()" é um comando assim como o comando "printf". O que esse comando faz é dizer ao computador que alí dentro está o código principal. "Main", do inglês, quer dizer principal. A palavra int é uma redução da palavra "inteiro". Na aula de funções, você entenderá por que comando "main" é um comando do tipo "inteiro". Por ora, importa você saber que quando o computador executa seu programa, ele vai procurar a função main e executar tudo, e somente, o que estiver ali dentro. 

Observe que a chamada da main é seguida por um par de chaves {}. Isso para que o computador entenda onde começa e onde termina seu bloco de código. 


A linha printf(".....")
Na aula anterior, você já deve ter entendido o que faz essa linha: ela é um comando que faz coisas serem escritas na tela. Esse comando admite muitas variantes. Podemos escrever coisas linhadas à direita, podemo escrever nºs com a quantidade de casas decimais que desejarmos, podemos escrever na tela outras partes do código. Enfim, o comando é bem rico e vamos utilizá-lo muito. Muito mesmo!

Atenção! Observe que ao final da linha, vem um ponto-e-vírgula. Sem ele,o computador não sabe que o comando chegou ao fim. Esquecer um ponto-e-vírgula é uma das causas mais frequentes de um programa não compilar!


A linha return 0
O comando return é a finalização da função main. Retornar 0 significa (mais ou menos) que o programa terminou sem problemas. Quando estudarmos funções, vai ficar bem claro o quão útil pode ser o retorno de uma função. Já deu pra ver que entender sobre funções é muito importante né!

Percebeu o ponto-e-vírgula??? Nunca se esqueça dele!


No próximo módulo
Terminamos o Módulo 1 - Criando e entendendo seu primeiro programa em C. No módulo 2, vamos aprender a lidar com número e letras. Aprender a capturar o que o usuário digita e manipular o que ele digitou. A seguir você encontra duas aulas extras, opcionais para o curso. Se você pretende trabalhar com computação ou gosta de saber as coisas a fundo, recomendo fortemente que você leia essas aulas. Nos vemos no Módulo 2. 

Abraço!





