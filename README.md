# 📊 Análise Quantitativa das OSCs no Rio Grande do Norte

Este repositório contém o projeto de Análise Exploratória de Dados (AED) sobre o perfil e a distribuição das Organizações da Sociedade Civil (OSCs) no estado do Rio Grande do Norte.

O [notebook](analise-osc-rn.ipynb) documenta todo o processo, desde a limpeza dos dados até a geração de visualizações e conclusões, seguindo uma metodologia quantitativa.

---

## 🎯 Sobre o Projeto

O objetivo deste projeto é caracterizar quantitativamente o universo das OSCs no Rio Grande do Norte, respondendo a perguntas como:

* Qual a **distribuição geográfica** das OSCs nos municípios do estado?
* Quais são as **áreas de atuação** (ex: Religião, Assistência Social) mais comuns?
* Qual o **perfil cadastral** das organizações, incluindo a proporção de entidades "Ativas" vs. "Inaptas"?

## 📈 Principais Descobertas

Nossa análise confirmou 3 hipóteses principais:

1.  **Concentração Geográfica:** Existe uma forte concentração de OSCs na capital, **Natal**, e nos maiores centros urbanos, como Mossoró.
2.  **Perfil de Atuação:** As áreas de **Religião** e **Desenvolvimento e Defesa de Direitos** são as mais prevalentes, indicando um foco forte em atividades de base comunitária.
3.  **Saúde Cadastral:** Quase **27%** das organizações no RN estão com o status de **"Inapta"**, sinalizando um desafio significativo de sustentabilidade e regularização.

*Para ver os gráficos e a análise completa, abra o notebook `analise-osc-rn.ipynb`.*

---

## 📂 Fonte e Estrutura dos Dados

Os dados utilizados são um recorte do [Mapa das OSCs (IPEA)](https://mapaosc.ipea.gov.br/).

* `dados/osc_dados_RN.csv`: Contém os **12.664** registros de OSCs do **Rio Grande do Norte**, já limpos e tratados, prontos para análise.
* `analise-osc-rn.ipynb`: O notebook Jupyter com todo o código Python (Pandas, Matplotlib, Seaborn) e a metodologia.
* **Dados Brutos (Nacional):** O dataset bruto original (com 917 mil linhas do Brasil inteiro) é muito grande para este repositório, mas está disponível publicamente no meu **[Dataset no Kaggle](https://www.kaggle.com/code/jadsonchagas/osc-dados-rn)**.
---

## 🛠️ Ferramentas Utilizadas

* **Python 3**
* **Pandas:** Para manipulação e limpeza de dados.
* **Matplotlib:** Para visualização de dados.
* **Seaborn:** Para visualização estatística.
* **Jupyter Notebook:** Para a análise interativa.
