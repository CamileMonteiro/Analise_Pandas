# 📈 Análise Exploratória de Dados com Pandas
## 📝 Descrição do Projeto

Este projeto consiste em uma Análise Exploratória de Dados realizada sobre um conjunto de dados de vendas globais.
O principal objetivo foi **desenvolver o raciocínio analítico** e a **proficiência na biblioteca Pandas** (Python) para entender a estrutura dos dados, identificar padrões e extrair métricas de negócio relevantes.

## 📊 Principais Descobertas e Respostas Analíticas

### 1. Qualidade e Integridade dos Dados

* **Identificação de Valores Ausentes:** Foi verificado que **nenhuma coluna possui valores nulos/ausentes**, garantindo a integridade do conjunto de dados para as análises subsequentes. *(Referência: Código `vendas_df.isnull().sum()`)*

### 2. Métricas de Negócio Chave

  * **Valor Médio:**
  * Média de **Total_Vendas**: $246.49$
  * Média de **Lucro**: $28.61$

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/d65991a2-86b9-45cd-8182-5e3a3e1a2c70"/>
    
> *Nota Analítica:* A média positiva de Lucro ($28.61$) indica que, no geral, a empresa está sendo lucrativa. No entanto, o **valor mínimo de Lucro é extremamente negativo** ($-6599.98$), o que sinaliza a existência de transações com perdas muito altas. A próxima etapa seria investigar a fundo os fatores (como 'Desconto' ou 'Região') que levam a essas perdas.

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Bibliotecas:** Pandas, Matplotlib e Seaborn.
* **Ambiente:** Jupyter Notebook

## 📂 Conteúdo do Repositório

* `analise_pandas.ipynb`: O Notebook principal contendo todo o código de importação, limpeza, análise exploratória e as respostas às perguntas.
* `[dataset.xlsx]`: O arquivo Excel utilizado na análise.

## ✍️ Como Rodar o Projeto

1.  Clone este repositório.
2.  Certifique-se de ter Python e as bibliotecas Pandas (e outras) instaladas.
3.  Abra o arquivo `analise_pandas.ipynb` em um ambiente Jupyter (JupyterLab, VS Code, Google Colab).
