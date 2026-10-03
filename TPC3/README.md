# Manifesto

* **Título:** TPC 3 - Corrida para o 100
* **Autor:** Lucca Forestieri Pires de Araujo, A114414
* **Resumo:** 

  Neste terceiro trabalho prático, o objetivo consistiu em desenvolver em Python o jogo Corrida para o 100, no qual o jogador e o computador somam alternadamente números entre 1 e 10 a um total que começa em 0, vencendo quem alcançar exatamente o número 100.
  Durante o desenvolvimento do código, a primeira parte, em que o computador começa a jogar, foi mais direta de estruturar após compreender a estratégia matemática vencedora, que consistia no computador iniciar sempre a jogar 1 e, nas rondas seguintes, responde com um número chave 11, garantindo que o total passa sempre pelos números (1, 12, 23, 34, 45, 56, 67, 78, 89) até chegar a 100.
  Quanto à segunda parte, em que o utilizador começa a jogar, o desenvolvimento revelou-se mais desafiante por dois motivos principais. O primeiro foi a necessidade de programar as contas com o resto da divisão por 11, para que o computador jogasse um valor aleatório caso o jogador seguisse a estratégia certa, mas conseguisse calcular exatamente quanto faltava para o próximo número-chave assim que o jogador cometesse uma falha. O segundo desafio foi agrupar e alinhar corretamente toda a lógica e as validações, usando ciclos while e uma lista de opções válidas de 1 a 10, além de impedir que a soma ultrapasse 100, dentro do ciclo principal. Apesar dessas dificuldades com a matemática e com a indentação dos blocos, foi possível conjugar as estruturas cíclicas e condicionais dadas em aula para que o jogo funcionasse de forma fluida nas duas vertentes.

* **Lista de resultados:**
  * [Código](codigo2.ipynb)