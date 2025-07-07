# Análise de Dados e Boas Práticas - Previsão de Obesidade

Este repositório contém o notebook utilizado no projeto de análise exploratória e pré-processamento de dados para previsão de obesidade a partir de variáveis comportamentais e fisiológicas.

## 📘 Sobre o Projeto

O projeto teve como foco principal **analisar, explorar e preparar** um conjunto de dados relacionados a hábitos alimentares, estilo de vida e condições de saúde de indivíduos de diferentes perfis. A base de dados foi descrita no artigo científico:

> Palechor, F. M., & Manotas, I. D. A. (2019). Dataset for estimation of obesity levels based on eating habits and physical condition in individuals from Colombia, Peru and Mexico. *Data in Brief*, 25, 104344. [https://doi.org/10.1016/j.dib.2019.104344](https://doi.org/10.1016/j.dib.2019.104344)

O modelo preditivo **não foi implementado** neste projeto. O foco esteve em compreender o comportamento dos dados e prepará-los de forma adequada para uma futura aplicação de Machine Learning.

## 🧪 Objetivos

- Analisar os padrões e tendências relacionados à obesidade
- Verificar hipóteses baseadas em comportamentos de saúde
- Realizar o pré-processamento completo dos dados
- Preparar o conjunto para uso em modelos preditivos

## 🔍 Hipóteses Avaliadas

1. Indivíduos que monitoram a ingestão calórica tendem a apresentar menor obesidade
2. Maiores níveis de atividade física estão associados a menor obesidade
3. Maior consumo de água está relacionado a menor obesidade
4. Maior frequência de consumo de fast food aumenta a propensão à obesidade
5. Histórico familiar de obesidade está associado a maior risco de obesidade

## ⚙️ Pré-processamento Realizado

- Conversão de variáveis categóricas com **One-Hot Encoding**
- Manutenção de variáveis ordinais em formato contínuo
- Normalização com **Min-Max Scaling**
- Tratamento de duplicatas, reduzindo amostras idênticas para no máximo 2 ocorrências
- Verificação de tipos, escalas, valores nulos e consistência geral dos dados

## 📈 Ferramentas e Bibliotecas

- Python 3.10+
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 📎 Arquivo Principal

- `MVP_3_Analise_de_Dados_e_Boas_Praticas.ipynb`: Notebook com todo o fluxo de trabalho, desde a análise exploratória até o tratamento final do dataset.

## 👩‍💻 Autora

**Thayssa Ribeiro**  
Projeto acadêmico desenvolvido como parte do curso de pós-graduação em Ciência de Dados e Analytics na PUC-Rio.

---

**🔗 Acesse o notebook diretamente no Google Colab:**  
[Colab Link](https://colab.research.google.com/github/TPRibeiro/mvp_ADeBP/blob/main/MVP_3_Analise_de_Dados_e_Boas_Praticas.ipynb)

**📄 Acesse a versão raw para download automático:**  
[Raw .ipynb](https://raw.githubusercontent.com/TPRibeiro/mvp_ADeBP/refs/heads/main/MVP_3_Analise_de_Dados_e_Boas_Praticas.ipynb)

