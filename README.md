# Análise de Preços - Airbnb em Nova York

## Instalação

### Pré-requisitos
Python (3.8 ou superior)
Anaconda
Miniconda

### Configurando o Ambiente
Clone este repositório:
  ```bash
  git clone https://github.com/pedrowsxz/Analise_de_Precos_NY_Airbnb.git
  cd Analise_de_Precos_NY_Airbnb
  ```

Crie um ambiente virtual.
Ative o ambiente.
  ```bash
  conda activate airbnb-analysis
  conda install --file requirements.txt
  ```

Instale as dependências necessárias.
  ```bash
  pip install -r requirements.txt
  ```

## Executando o Projeto

1. Abra o Jupyter Notebook pelo Anaconda Navigator ou execute no terminal:
  ```bash
  jupyter notebook
  ```

2. Navegue até o diretório do projeto e abra o arquivo Jupyter Notebook (.ipynb).

3. Execute as células na sequência para realizar a análise e o treinamento do modelo.

## Visão Geral do Projeto

Este projeto analisa os preços das listas do Airbnb na cidade de Nova York. Ele aplica técnicas de aprendizado de máquina, como Regressão Polinomial e Regressão por Vetores de Suporte (SVR), para prever os preços das listas com base em características como localização, tipo de quarto e disponibilidade.

## Bibliotecas Utilizadas

- **NumPy & Pandas**: Manipulação e tratamento de dados
- **Matplotlib & Seaborn**: Visualização de dados
- **Scikit-learn**: Modelos de aprendizado de máquina e ferramentas de pré-processamento
