Este projeto aborda a construção de um modelo de Regressão Linear para prever o impacto de investimentos em diferentes canais de marketing (YouTube, Facebook e jornal) sobre as vendas. A análise busca identificar relações entre os gastos e os resultados de vendas para orientar decisões estratégicas.

Etapas do Projeto

Importação de Bibliotecas e Carregamento de Dados:
Utilização de bibliotecas como pandas, numpy, matplotlib, seaborn e scikit-learn.
Carregamento dos dados de marketing a partir de um arquivo CSV.

Exploração Inicial e Limpeza de Dados:
Visualização das primeiras linhas e informações gerais do DataFrame.
Estatísticas descritivas para entender a distribuição dos dados.
Identificação e tratamento de outliers utilizando o método do IQR (Intervalo Interquartil).

Análise Exploratória:
Criação de histogramas para visualizar a distribuição das variáveis.
Gráficos de dispersão para identificar relações entre os investimentos em marketing e as vendas.

Preparação dos Dados:
Divisão dos dados em variáveis independentes (YouTube, Facebook, Newspaper) e dependente (Sales).
Separação dos dados em conjuntos de treino e teste com train_test_split.

Construção e Treinamento do Modelo:
Aplicação de um modelo de Regressão Linear utilizando a biblioteca scikit-learn.
Ajuste do modelo com os dados de treino e avaliação nos dados de teste.

Avaliação do Modelo:
Cálculo de métricas como R² para medir o desempenho do modelo.
Análise residual para verificar a qualidade do ajuste.

Visualização e Interpretação:
Geração de gráficos para comparar os valores reais e previstos.
Interpretação dos coeficientes do modelo para entender a influência de cada canal no resultado final.

Como Executar
Certifique-se de que as bibliotecas necessárias estão instaladas.
Baixe o arquivo de dados (MKT.csv) e ajuste o caminho no código, se necessário.
Execute o notebook para reproduzir a análise e os resultados.

Resultados
Este projeto oferece insights sobre a eficácia de diferentes canais de marketing e como os investimentos influenciam as vendas, sendo uma ferramenta poderosa para tomada de decisões baseada em dados.
