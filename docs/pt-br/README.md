# Data Science Labs

## Visão geral

Este repositório é um laboratório central de estudos de análise de dados, estatística, ciência de dados e machine learning. Os materiais são classificados como estudos e exercícios práticos. Eles não devem ser tratados como projetos profissionais completos ou como análises prontas para produção.

Os notebooks existentes foram preservados sem alteração de conteúdo.

## Estrutura

```text
.
├── notebooks/
│   ├── pandas/
│   ├── numpy/
│   ├── statistics/
│   ├── visualization/
│   ├── machine-learning/
│   └── deep-learning/
├── datasets/
│   └── numpy/
└── docs/
    ├── pt-br/
    ├── en/
    ├── fr/
    └── es/
```

## Estudos disponíveis

### Pandas

#### Tratamento dos microdados do ENEM 2019

Notebook: [`notebooks/pandas/tratamento_enem_2019.ipynb`](../../notebooks/pandas/tratamento_enem_2019.ipynb)

Lab de estudo sobre tratamento e exploração inicial de dados com pandas e NumPy. O notebook existente inclui etapas como:

- Leitura de arquivo CSV com pandas.
- Remoção e renomeação de colunas.
- Correção e transformação de valores.
- Renomeação de registros categóricos.
- Exploração de idades, treineiros e vestibulandos.
- Análise de presença nas provas.
- Identificação de valores ausentes.
- Exploração de notas zero.
- Exportação de recortes tratados.

O notebook depende do arquivo externo `microdados_enem_2019_sp.csv`, que não está versionado neste repositório. Não publique microdados sensíveis ou arquivos grandes sem revisar licença, privacidade e necessidade.

### NumPy

Materiais de apoio: [`datasets/numpy/`](../../datasets/numpy/)

O repositório contém datasets usados em estudos de NumPy:

- `apples_ts.csv`
- `bytebank.csv`
- `citrus.csv`

Esses arquivos foram apenas reorganizados; seu conteúdo não foi alterado.

### Estatística

Diretório preparado em `notebooks/statistics/` para exercícios futuros de estatística descritiva, probabilidade e inferência.

### Visualização

Diretório preparado em `notebooks/visualization/` para estudos futuros de visualização de dados.

### Machine Learning

Diretório preparado em `notebooks/machine-learning/` para experimentos futuros de aprendizado de máquina.

### Deep Learning

Diretório preparado em `notebooks/deep-learning/` para estudos futuros de redes neurais e deep learning.

## Como executar os labs

1. Crie e ative um ambiente virtual Python.
2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Abra o Jupyter:

```bash
jupyter notebook
```

4. Execute o notebook desejado a partir da raiz do repositório.

Alguns labs podem exigir datasets externos não versionados. Confira as instruções de cada notebook antes da execução.

## Diretrizes para novos estudos

- Classifique novos notebooks pela área principal de aprendizado.
- Preserve notebooks como registros didáticos.
- Não invente resultados ou conclusões.
- Não versione datasets sensíveis, credenciais ou arquivos locais.
- Documente dependências externas necessárias para reproduzir o exercício.
- Use `datasets/` para dados de apoio adequados para versionamento.

## Limitações

- Os notebooks refletem estudos em andamento.
- Nem todos os labs possuem datasets versionados.
- Resultados presentes nos notebooks não foram reavaliados nesta reorganização.
- A estrutura foi preparada para expansão gradual do repositório.
