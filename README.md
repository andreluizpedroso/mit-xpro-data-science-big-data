# 🎓 MIT xPRO — Data Science e Big Data

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4051B5?style=flat&logo=python&logoColor=white)
![Featuretools](https://img.shields.io/badge/Featuretools-085078?style=flat&logo=python&logoColor=white)
![Surprise](https://img.shields.io/badge/Surprise-7B1FA2?style=flat&logo=python&logoColor=white)
![Beautiful Soup](https://img.shields.io/badge/Beautiful%20Soup-4B8BBE?style=flat&logo=python&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154F3C?style=flat&logo=python&logoColor=white)

Este repositório reúne materiais de estudo, exercícios e estudos de caso do curso **MIT xPRO — Data Science e Big Data**. 📚

Não se trata de uma aplicação única: cada notebook é uma atividade relativamente independente, dedicada à aplicação prática de conceitos de estatística, ciência de dados e aprendizado de máquina.

## 🧭 Conteúdo

### 🧩 Módulo 1 — Aprendizado não supervisionado

- **PCA e K-Means em dados genômicos:** redução da quantidade de variáveis com Análise de Componentes Principais (PCA) e identificação de grupos semelhantes com K-Means, sem utilizar rótulos previamente definidos.
- **Alocação Latente de Dirichlet (LDA):** descoberta automática dos assuntos presentes em uma coleção de textos por meio da frequência e da distribuição das palavras.
- **Identificação facial com PCA e *eigenfaces*:** representação compacta de imagens de rostos, permitindo reconstruí-las e comparar uma nova face com as existentes.
- **Agrupamento espectral de notícias:** transformação de notícias em atributos numéricos e formação de grupos de textos com conteúdo semelhante.

### 📈 Módulo 2 — Regressão, previsão e inferência causal

- **Previsão de salários:** uso de regressão para estimar salários a partir de características observadas e avaliação da capacidade do modelo de generalizar para novos dados.
- **Diferença salarial entre homens e mulheres:** investigação da desigualdade salarial com regressão linear, controlando outras características que também influenciam a remuneração.
- **Crescimento de países pobres e ricos:** análise da hipótese de convergência econômica, isto é, se países inicialmente mais pobres tendem a crescer mais rapidamente.
- **Modelos lineares e não lineares:** comparação entre modelos com diferentes níveis de flexibilidade e estudo do efeito do particionamento dos dados e da combinação de previsões.
- **Porte de armas e taxas de homicídio:** aplicação de métodos estatísticos para estimar uma possível relação causal, distinguindo correlação de causalidade e considerando fatores de confusão.

### 🧠 Módulo 3 — Classificação e redes neurais

- **Lançamento do Challenger:** modelagem da probabilidade de falha dos anéis de vedação em função da temperatura, mostrando como uma análise preditiva poderia apoiar a decisão de lançamento.
- **Limites de decisão com redes neurais:** uso de redes neurais profundas para separar classes quando a relação entre os dados não pode ser representada adequadamente por uma fronteira linear.

### 🎯 Módulo 4 — Sistemas de recomendação

- **Recomendação de filmes:** construção e comparação de recomendadores aleatórios, baseados em usuários, baseados em itens e em fatoração de matrizes.
- **Recomendação de músicas:** geração de sugestões personalizadas a partir das preferências e dos padrões de consumo dos usuários.
- **Recomendação de produtos:** aplicação das mesmas ideias ao comércio, estimando quais produtos têm maior chance de interessar a cada cliente.
- **Avaliação dos recomendadores:** uso de métricas como precisão e *recall* para verificar a qualidade das listas de recomendações mais relevantes.

### 📍 Módulo 5 — Filtros de Kalman e rastreamento

- **Rastreamento de um objeto em movimento:** combinação de previsões do movimento com medições ruidosas para estimar continuamente a posição e a velocidade reais de um objeto.
- **Filtro de Kalman em três dimensões:** extensão do rastreamento para os eixos X, Y e Z, atualizando o estado estimado à medida que novas observações são recebidas.

### ⚙️ Módulo 6 — Engenharia de atributos e modelos preditivos

- **Corridas de táxi em Nova York:** organização de tabelas relacionadas e criação de variáveis para prever comportamentos com base no histórico das corridas.
- **Engenharia automatizada de atributos:** uso do Featuretools para produzir atributos por transformação e agregação, reduzindo parte do trabalho manual de preparação dos dados.
- **Previsão de vendas no Reino Unido:** definição dos exemplos de treinamento, criação de atributos temporais e treinamento de um modelo Random Forest para realizar previsões sobre vendas futuras.

## 🗂️ Organização dos arquivos

- `.ipynb`: notebooks Jupyter/Google Colab com código, explicações e resultados.
- `.html`: enunciados e materiais de apoio dos estudos de caso.
- `.pdf`: documentos e materiais complementares do curso.
- `.png`: capturas de tela relacionadas ao material.

Os nomes seguem o padrão **tipo + número do estudo + tema**, facilitando a associação entre cada enunciado e seu notebook:

- `Enunciado - Estudo X.Y - Tema.html`
- `Notebook - Estudo X.Y - Tema.ipynb`
- `Notebook pessoal`: versão preenchida ou trabalhada durante o curso.
- `Exportação em PDF`: cópia de um notebook exportada para consulta.
- `Material do curso`: documentos gerais que não pertencem a um estudo específico.

## 🛠️ Tecnologias utilizadas

Os notebooks usam principalmente Python e bibliotecas como:

- pandas e NumPy
- scikit-learn
- matplotlib
- statsmodels
- Featuretools
- Surprise
- Beautiful Soup e NLTK

As dependências variam entre as atividades. Alguns notebooks foram preparados para o Google Colab e podem baixar dados, acessar o Google Drive ou instalar pacotes durante a execução.

## 🚀 Como utilizar

1. Abra a pasta do módulo desejado.
2. Consulte o arquivo HTML para conhecer o enunciado da atividade.
3. Abra o notebook correspondente no Jupyter Notebook, JupyterLab ou Google Colab.
4. Execute as células na ordem apresentada e verifique se os dados e pacotes solicitados ainda estão disponíveis.

> 💡 Este repositório funciona como arquivo pessoal do curso. A numeração das pastas preserva a ordem original dos módulos.
