# aeds1-autodidata
Curso autodidata que cobre exatamente o mesmo conteúdo do primeiro semestre de programação da UFMG



- Seção
	- Tela
		- Detalhes de conteúdo


- 1. Criando e entendendo seu primeiro programa em C
	- 1.1 Apresentação do curso
		- Para quem o curso foi pensado
			- usuários de windows, que são a maioria dos iniciantes
		- O que é AEDS 1
		- Lista de Conteúdos
		- Meu ponto de desenvolvimento quando escrevi o curso
	- 1.2 Instalando uma IDE - Codeblocks
		- O que é uma IDE
		- O que é um compilador
		- Instalando o Codeblocks
		- Instalando as bibliotecas do Codeblocks
	- 1.3 Criando um novo arquivo no Codeblocks
		- Apresentar a interface de maneira geral
		- Por enquanto não vamos usar todas as funcionalidades do Codeblocks
		- Destacar as parte da interface que utilizaremos ao longo do curso
	- 1.4 Prática de programação nº 01 - Faça o computador escrever seu nome
		- Copiar e colar o código abaixo
		- Colocar um código de printf("Computador, escreva meu nome na tela: Nome");
		- Compilando e executando
		- Eu sei que não é o programa mais empolgante do mundo. Ao longo do curso faremos coisas bem mais legais
		- Parabéns, você acabou de fazer o que talvez seja o programa menos empolgante do mundo! O que é importante entender é que mesmo esse comando simples é sim, um programa. E foi importante para você se familiarizar com a interface do CodeBlocks.
		- Na próxima página você entenderá o que significa cada linha do seu primeiro programa
	- 1.5 Entendendo o esqueleto de um programa em linguagem C
		- Vamos entender, linha por linha, o que o programa que você fez na aula passada realmente está fazendo
		- A linha #include <stdio.h>. 
			- Essa linha vincula a biblioteca stdio.h ao seu programa
			- stdio é uma sigla para standard input-output. e ".h" nada mais é do que extensão desse tipo de arquivo
			- O que são bibliotecas.
				- São conjuntos de comandos de uma linguagem. E como se fosse um dicionário, para que o computador saiba o que significa cada comando que você está dando
				- A linguagem C tem uma biblioteca padrão, que não precisa ser invocada no começo do programa, mas ela é tão limitada, que a biblioteca <stdio.h> é comumente chamada de biblioteca padrão
			- Outras bibliotecas importantes
		- A linha int main ()
			- É o bloco de código onde seu programa acontece. Na próxima página explico um pouco mais sobre esse bloco de código
			- 
			- Note que para o computador saber onde começa e onde termina seu código, você precisa usar um par de { }
			- Essa lógica será usada em muitos momentos
		- A linha printf(".....")
			- O printf é um comando que faz o computador escrever coisas no tela, como já vimos
			- Cada biblioteca posui diversos comandos para utilizarmos. É muito importante conhecer os comandos das principais bibliotecas de qualquer linguagem que você esteja aprendendo, para você entender tudo o que a linguagem é capaz de te oferecer.
		- A linha return 0
			- A linha return 0 é um feedback para o sistema operacional de que tudo deu certo.
			- Vários comandos, além de executar o que é pedido, retornam alguma coisa, como é o caso do comando soma, que retorna, dã, a soma de dois números
			- Entenderemos melhor a importância da linha de retorno quando estudarmos funções.
	- 1.6 O que acontece quando eu compilo o programa?
		- O arquivo com o seu código em C é chamado código fonte do seu programa. Ou seja, é o arquivo que contém o programa escrito de um jeito que (alguns) humanos entendem. O problema é que a máquina não sabe ler código. 
		- Pode ser uma surpresa para você, mas o que você escreveu no seu programa, é complicado demais para o computador entender. Porque a única coisa que o computador entende são impulsos de eletricidade. Tudo, absolutamente tudo, o que um computador faz depende unicamente de dois comandos: ligado (1) e desligado (0). O computador tem inúmeros interruptores que se ligam e desligam dependendo se há ou não corrente elétrica. Eu não sei você, mas eu acho incrível, e até absurdo, a vastidão de coisas que conseguimos fazer usando apenas dois comandos. É por isso que falamos que computador só entende binário.
		- Percebe como o seu código está muito longe de comandos em zeros e uns?
		- Compilar um programa significa traduzi-lo para a linguagem da máquina. No caso, ao compilar, você está transformando suas linhas de código em zeros e uns, que serão lidos como impulsos de eletricidade, que é a única coisa que um computador entende.
		- Note que quando você salva o arquivo do seu código fonte, ele tem a extensão ".c". Depois de compilar, o compilador gerou pra você um arquivo com extensão ".o". Esse arquivo é o "código objeto". É ele que tem o seu código fonte já traduzido para binário, que a máquina entende de fato. Além do arquivo.o, ele gerou também o arquivo.exe, que nada mais é do que o arquivo.o executável pela pessoa
		- O código C é lido de cima para baixo. Isso é importante para prever você o que acontece antes do que.
	- 1.7 Indo além - Porque usam linguagem C em AEDS 1
		- Diferença entre linguagem de alto nível x linguagem de baixo nível 
		- Das linguagens de alto nível, é uma das mais baixas. É considerada por muitos, uma linguagem de "médio" nível
		- Podemos manipular a memória
		- Aprendemos melhor sobre como uma linguagem de computador funciona
		- Para o que usam C no mundo real
