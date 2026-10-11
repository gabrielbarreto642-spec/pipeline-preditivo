# Pipeline Preditivo para Indústria 4.0 ⚙️🤖

Projeto avaliativo do Módulo 1 do curso de Desenvolvimento de IA para Análise Preditiva (SENAI/SC).

## 📌 Sobre o Projeto
O objetivo deste sistema é prever quebras mecânicas em equipamentos industriais monitorados por sensores, permitindo a manutenção preditiva e evitando paradas na linha de produção da fábrica. A variável alvo é binária (`falha_maquina`), onde 1 representa falha e 0 operação normal.

## 🛠️ Tecnologias Utilizadas
* **Python 3**
* **Pandas** e **NumPy** (tratamento e manipulação de dados)
* **Matplotlib** e **Seaborn** (visualização e gráficos)
* **Scikit-Learn** (modelos preditivos KNN e Árvore de Decisão, escalonamento)
* **Imbalanced-Learn** (balanceamento de classes com SMOTE)

## 🌿 Estrutura de Branches (GitFlow)
* `main`: Versão final e estável do projeto.
* `develop`: Integração das etapas desenvolvidas.
* `feature/eda`: Análise exploratória dos dados e gráficos de correlação e dispersão.
* `feature/data-prep`: Remoção de nulos pela mediana e análise de outliers com boxplot.
* `feature/feature-engineering`: Criação da variável de potência mecânica (Rotação x Torque).
* `feature/modelagem`: Balanceamento com SMOTE, escalonamento e treinamento dos modelos preditivos.

## 🚀 Como Executar o Projeto
1. Clone este repositório ou faça o download dos arquivos.
2. Certifique-se de ter o Python instalado e instale as dependências:
   ```bash
   pip install -r requirements.txt
