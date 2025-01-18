# Income Prediction 💵 - Dataset Census 

Este projeto desenvolve um algoritmo de Machine Learning para classificar registros de renda em duas categorias: superior a U$50.000 e menor ou igual a U$50.000 anuais. A base de dados foi encontrada na *UCI Machine Learning Repository* e ela foi originada por *Barry Becker* em 1994, contendo **32561 registros** com **14 atributos previsores** e **1 classe**. Segue abaixo o relatório do projeto: 

<p align="center">
  <a href="Relatório do Projeto de Machine Learning.pdf">
    Relatório
  </a>
</p>


## Etapas do Projeto

**1. Análise de Dados:** Entender como os dados estão distribuídos é essencial para identificação de possíveis problemas.

**2. Tratamento dos Dados:** Aplicação de técnicas para limpar e transformar os dados, garantindo melhor desempenho dos modelos.

**3. Treinamento dos Dados:** Treinamento dos modelos de Machine Learning com os dados tratados.

**4. Avaliação de Desempenho:** Será realizado uma avaliação com o objetivo de medir a capacidade de aprendizado de cada algoritmo.

**5. Testes:** Para evitar problemas de overfitting, será realizado mais uma vez testes com o propósito de medir o desempenho do melhor algoritmo.

# Estrutura do Dataset

## Classe:

- income: >50K, <=50K.

## Atributos Previsores:

- age : continuous.
- workclass : Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
- fnlwgt: continuous.
- education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
- education-num: continuous.
- marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, - - - Married-spouse-absent, Married-AF-spouse.
- occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
- relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
- race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
- sex: Female, Male.
- capital-gain: continuous.
- capital-loss: continuous.
- hours-per-week: continuous.
- native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.
<br>


# Como ter acesso ao projeto?

## **1. Acesso direto**:
Para visualizar o notebook no repositório sem instalar o projeto, clique no link abaixo:

<p align="center">
  <a href="1data_analyses.ipynb">
    Clique aqui
  </a>
</p>

- Observação: Certifique se a opção "Preview" esteja habilitada.
  
<img src="images/1guidelines.png" alt=""></img> 
<br>

## **2. Clonando no Terminal**: 
Recomendado para aqueles que desejam rodar o projeto no próprio sistema.

- **Avisos**: 
  - O ambiente virtual ocupa aproximadamente 800Mb.
  - O projeto foi desenvolvido em Python 3.12.7 no Windows.

Clone o repositório:

```bash 
git clone https://github.com/luccasena/Machine-Learning-Binary-Classification.git
```

Crie um ambiente virtual:

```bash 
py -m venv venv
```

Ative o ambiente virtual:

```bash 
venv/Scripts/activate
```

Instale as dependências:

```bash 
pip install -r requirements.txt
```

