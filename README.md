# Previsão da Satisfação de Passageiros de Companhias Aéreas

## 1. Sobre o projeto

Este projeto foi desenvolvido como avaliação da disciplina de Reconhecimento de Padrões do Mestrado em Computação Aplicada do IFES.
trata-se de um estudo de aprendizado de máquina, utilizando dados da competição **Kaggle Playground Series S6E10** (disponível em: https://www.kaggle.com/competitions/playground-series-s6e10).

O objetivo é desenvolver modelos de classificação capazes de prever a satisfação dos passageiros de companhias aéreas, considerando características relacionadas ao perfil dos clientes, às condições da viagem e à experiência com os serviços oferecidos.

## 2. Objetivo

Aplicar e comparar diferentes algoritmos de aprendizado de máquina para identificar padrões associados à satisfação dos passageiros, avaliando o desempenho dos modelos por meio de métricas de classificação.

## 3. Conjunto de dados

Os dados utilizados foram disponibilizados pela competição Kaggle Playground Series S6E10.

Os arquivos necessários são:

- `train.csv`: conjunto de dados utilizado no treinamento e na avaliação dos modelos.
- `test.csv`: conjunto de dados destinado à geração de previsões.

A variável-alvo utilizada na classificação é `satisfaction`.

Os dados incluem informações sobre características dos passageiros, distância dos voos, atrasos e avaliações de diferentes serviços oferecidos pelas companhias aéreas.

**Fonte dos dados:** [Kaggle – Playground Series S6E10](https://www.kaggle.com/competitions/playground-series-s6e10)

## 4. Tecnologias e bibliotecas

O projeto foi desenvolvido em Python, utilizando Jupyter Notebook e as seguintes bibliotecas:

- **Pandas:** manipulação e análise dos dados.
- **NumPy:** operações numéricas.
- **Matplotlib:** visualização dos dados.
- **Seaborn:** construção de gráficos estatísticos.
- **Scikit-learn:** pré-processamento, treinamento, validação e avaliação dos modelos.


## 5. Como reproduzir o projeto

Para reproduzir os experimentos, siga as instruções:

### Pré-requisitos

- Python instalado;
- Jupyter Notebook ou Visual Studio Code;
- Bibliotecas utilizadas no projeto.

### Instalação das bibliotecas

Execute o comando abaixo no terminal:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### Obtenção dos dados

1. Acesse a página da competição no Kaggle.
2. Baixe os arquivos `train.csv` e `test.csv`.
3. Coloque os arquivos na mesma pasta do notebook.

### Execução

1. Clone ou baixe este repositório.
2. Abra a pasta do projeto no Jupyter Notebook ou Visual Studio Code.
3. Abra o arquivo `notebook_kaggle_s6e10_JulioScopel_IFES.ipynb`.
4. Execute as células sequencialmente, desde o carregamento dos dados até a avaliação dos modelos.

Para reproduzir os resultados, utilize os mesmos arquivos de entrada e as configurações de execução definidas no notebook, incluindo a semente aleatória e os procedimentos de validação.

## 6. Estrutura do projeto

```text
projeto-kaggle-satisfacao/
│
├── notebook_kaggle_s6e10_JulioScopel_IFES.ipynb
├── README.md
│
├── train.rar
├── test.rar
```

Os arquivos CSV estão compactados nos arquivos .rar e também podem ser obtidos diretamente na página da competição.
