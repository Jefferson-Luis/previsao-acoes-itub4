# 📈 Previsão de Preços de Ativos (ITUB4) com Machine Learning

## 🎯 Sobre o Projeto
Este projeto aplica técnicas de Machine Learning (Aprendizado Supervisionado) para prever o preço de fechamento das ações do Itaú Unibanco (ITUB4). 

A iniciativa faz parte do meu portfólio prático, unindo a visão de riscos, compliance e governança adquirida em operações críticas do setor financeiro com ferramentas modernas de Ciência de Dados e Inteligência Artificial. O objetivo é demonstrar como a transformação de dados brutos em inteligência preditiva pode apoiar a tomada de decisão no mercado de capitais.

## 🛠️ Tecnologias e Stack
* **Linguagem:** Python
* **Coleta de Dados:** `yfinance` (API do Yahoo Finance)
* **Manipulação e Análise:** `pandas`, `numpy`
* **Machine Learning:** `scikit-learn` (Modelo de Regressão Linear)
* **Visualização de Dados:** `matplotlib` (Storytelling Visual)

## ⚙️ Pipeline do Modelo
O desenvolvimento seguiu as melhores práticas de análise de dados:
1. **Ingestão:** Extração de dados históricos reais da bolsa de valores (preços de Abertura, Alta, Baixa e Fechamento).
2. **Pré-processamento:** Tratamento de valores inconsistentes/nulos e seleção das variáveis independentes (Features) e dependentes (Target).
3. **Divisão de Dados:** Separação da base histórica em Treino (80%) e Teste (20%) para garantir a confiabilidade e evitar *overfitting*.
4. **Treinamento:** Ajuste do modelo preditivo utilizando o algoritmo de Regressão Linear.
5. **Avaliação e Monitoramento:** Medição de performance utilizando a métrica R² e plotagem de gráficos para comparar a predição algorítmica com a realidade do mercado.

## 💼 Visão de Negócio
No cenário bancário atual, antecipar flutuações e entender padrões é essencial. A lógica matemática e estatística aplicada na construção deste modelo de previsão de ativos é a mesma fundação utilizada para modernizar operações financeiras complexas, como:
* Detecção automatizada de fraudes em tempo real.
* Modelagem de *score* e análise de risco de crédito.
* Segmentação e recomendação personalizada de produtos para correntistas.

## 🚀 Como Executar Localmente
1. Clone este repositório: `git clone [URL_DO_SEU_REPOSITORIO]`
2. Instale as bibliotecas necessárias: 
   ```bash
   pip install yfinance pandas scikit-learn matplotlib
