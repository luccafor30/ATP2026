# Manifesto

* **Título:** TPC 6 - Aplicação de Gestão e Análise Meteorológica
* **Autor:** Lucca Forestieri Pires de Araujo, A114414
* **Resumo:** 
  Neste sexto trabalho prático, foi desenvolvida uma aplicação em Python para gerir, analisar e visualizar um conjunto de dados meteorológicos. 
  O modelo de dados baseia-se numa lista de tuplos, onde cada registo obedece à estrutura rigorosa.
  
  O programa é operado através de um menu interativo construído com um ciclo e validações através de manuseamento de strings. As funcionalidades implementadas incluem:
  
  - **Cálculos Analíticos:** Funções algorítmicas puras para calcular médias diárias, amplitudes térmicas, a temperatura mínima absoluta e o dia com a precipitação máxima.
  - **Pesquisa por Limites:** Identificação de dias de chuva acima de um limiar e o cálculo do período mais longo de dias secos, utilizando contadores matemáticos.
  - **Persistência de Dados (Opções 2 e 3):** Gravação e carregamento de dados em ficheiro de texto. A leitura foi blindada com verificações manuais de cabeçalho sequenciais para garantir a extração imaculada de números flutuantes e inteiros, gerindo manualmente a abertura e fecho do ficheiro.
  - **Visualização de Dados (Opção 9):** Integração com a biblioteca `matplotlib.pyplot` para a geração automática de um gráfico de linhas (para as temperaturas máximas e mínimas diárias) e um gráfico de barras (para a pluviosidade).

* **Lista de resultados:**
  * [Código fonte da aplicação](codigoTPC6.ipynb)
  * [Base de dados meteorológica (exemplo)](meteorologia.txt)