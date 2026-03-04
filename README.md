🎯 Objetivo

Desenvolver e avaliar modelos de Aprendizagem Automática capazes de estimar a probabilidade de evasão de clientes da TelecomX, recorrendo a dados previamente tratados e estruturados, com vista à identificação de fatores determinantes e à otimização da capacidade preditiva.

🧰 Tecnologias e Bibliotecas Utilizadas

Python – Linguagem de programação adotada para o desenvolvimento integral do projeto.

Jupyter Notebook – Ambiente computacional interativo utilizado para implementação, documentação e apresentação dos resultados.

Pandas – Biblioteca destinada à manipulação, transformação e análise de dados estruturados.

NumPy – Ferramenta de suporte a operações matemáticas e computação numérica.

Matplotlib – Biblioteca para visualização gráfica e representação de dados.

Seaborn – Utilizada para análise estatística exploratória e construção de matrizes de correlação (heatmaps).

Scikit-learn – Framework aplicada na implementação, validação e comparação de modelos de classificação.

📂 Estrutura do Projeto

README.md – Documento descritivo contendo o enquadramento, objetivos e metodologia adotada.

TelecomX-parte2.ipynb – Notebook com a implementação integral do processo analítico e relatório técnico final.

dados_tratados.csv – Conjunto de dados previamente preparado na fase anterior do projeto.

🔄 Metodologia e Etapas do Desenvolvimento

O projeto foi estruturado segundo um fluxo metodológico sequencial, conforme descrito abaixo:

1️⃣ Preparação e Tratamento dos Dados

Importação do ficheiro CSV previamente processado.

Exclusão de variáveis consideradas irrelevantes ou redundantes.

Codificação de variáveis categóricas através do método One-Hot Encoding, garantindo compatibilidade com algoritmos de classificação.

Análise da distribuição da variável-alvo, com verificação da proporção entre clientes ativos e clientes que cancelaram o serviço.

2️⃣ Análise Exploratória e Seleção de Variáveis

Construção e interpretação da matriz de correlação entre variáveis numéricas.

Realização de análises exploratórias direcionadas, recorrendo a representações gráficas como boxplots e gráficos de dispersão, com o intuito de compreender a relação entre variáveis independentes e a evasão.

3️⃣ Modelação Preditiva

Divisão do conjunto de dados em subconjuntos de treino e teste.

Implementação de diferentes algoritmos de classificação.

Avaliação comparativa com base em métricas como acurácia, precisão, recall, F1-score e matriz de confusão.

Análise crítica do desempenho dos modelos, incluindo verificação de fenómenos de overfitting e underfitting.

4️⃣ Análise da Importância das Variáveis

Identificação e interpretação das variáveis com maior contributo para a previsão da evasão.

5️⃣ Conclusão

Elaboração de um relatório final com discussão fundamentada dos resultados obtidos, destacando os fatores com maior impacto na evasão e o modelo com melhor desempenho preditivo.
