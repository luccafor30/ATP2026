# Manifesto

* **Título:** TPC 5 - Aplicação para Gestão de Alunos
* **Autor:** Lucca Forestieri Pires de Araujo, A114414
* **Resumo:** 
  Neste quinto trabalho prático, foi desenvolvida uma aplicação interativa em Python para a gestão de uma turma. 
  O modelo de dados implementado gira em torno de uma lista principal, onde cada aluno é armazenado internamente num tuplo com a formatação rigorosa (nome, id, [notaTPC, notaProj, notaTeste]).
  
  A aplicação funciona de forma contínua através de um ciclo e disponibiliza o seguinte menu de operações, construído apenas com lógicas de programação estruturada:
  - **Opção 1:** Criar/Inicializar uma turma vazia.
  - **Opção 2:** Inserir um aluno na turma (com a implementação de geração aleatória das três notas de avaliação para agilizar o processo de testes).
  - **Opção 3:** Listar a informação completa de todos os alunos.
  - **Opção 4:** Consultar um aluno por ID. A lógica de pesquisa foi construída de forma puramente algorítmica, utilizando variáveis de controlo nas condições do ciclo para parar a procura imediatamente após encontrar.
  - **Opção 5:** Guardar a turma num ficheiro de texto, exportando os dados de forma ordenada com separação por vírgulas.
  - **Opção 6:** Carregar a turma de um ficheiro de texto. A leitura reconstrói a estrutura de dados manualmente através da manipulação de strings.
  - **Opção 0:** Encerrar a aplicação.

* **Lista de resultados:**
  * [Código fonte da aplicação](codigoTPC5.ipynb)