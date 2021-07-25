

Sobre funções
- que significa "int main ()" - parte 1
	- O que é uma "função"
	- Para que serve a função main
		- Quando um programa em C é executado, a função main
	- Se existe uma função principal, podem haver outras? 
		- Sim, um programa em C pode ser constituído de várias funções, mas a main sempre será invocada primeiro 
	- Exemplo do printf: nome completo dela é int printf(texto). Esse texto que vai dentro dos parênteses tem várias peculiaridade de como ele pode ou deve ser escrito para que a função printf saiba o que fazer. Veremos mais detalhes em outro momento.
	- Funções diferentes da main precisam estar invocadas dentro da main para que sejam lidas pelo programa
	- O que vem dentro dos parênteses são chamados de parâmetros. São as informações que a função precisa para executar corretamente. 
	- O "nome completo" de uma função é chamado de protótipo ou assinatura.
- O que significa "int main (void)" - parte 2
	- O que significa "int"
		- Toda função recebe parâmetros, realiza algumas operações com esses parâmetros e devolve alguma coisa em retorno
		- Ou seja, toda função tem um retorno
		- A palavra int antes de uma função significa que o retorno da função é um valor do tipo inteiro.
		- O que a função main retorna
		- O que a função printf retorna
	- O que significa (void)
