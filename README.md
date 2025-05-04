## Estudo Dirigido 2 – Aprendizado Estatístico (CEFET-MG)

Este repositório contém o notebook do **Estudo Dirigido 2** da disciplina de Aprendizado Estatístico, desenvolvido com a linguagem **R**. O foco principal está na aplicação de técnicas de **seleção de modelos via AIC**, utilizando os métodos `backward` e `forward`.

### 📂 Arquivo Principal

* `AE_estudodirigido2.ipynb`: Notebook em R que realiza a análise estatística conforme o enunciado do Estudo Dirigido 2.

### 📊 Objetivos

* Aplicar modelos de regressão linear múltipla.
* Utilizar critérios de seleção de modelos (AIC).
* Comparar métodos `stepwise` (*backward* e *forward*).
* Interpretar os modelos ajustados.
* Discutir significância estatística das variáveis.

### 🧰 Tecnologias Utilizadas

* Linguagem: **R**
* Ambiente: **R Notebook / R Markdown**
* Pacotes: `stats`, `MASS` (função `step`), entre outros nativos do R.

### 📈 Base de Dados

O estudo utiliza os dados da Major League Baseball (MLB 2011), disponíveis em:

```r
http://www.openintro.org/stat/data/mlb11.RData
```

### 🚀 Como Executar

1. Clone este repositório.

2. Abra o arquivo `.ipynb` no RStudio ou Jupyter com kernel R.

3. Execute cada célula para reproduzir a análise.

### 📌 Resultado Esperado

Ao final da análise, é possível:

* Compreender os impactos de diferentes variáveis no número de corridas e vitórias no beisebol.
* Identificar o melhor modelo preditivo com base no critério AIC.
* Avaliar a importância estatística de cada variável incluída no modelo.

### 📎 Fonte

Este estudo está baseado no material didático do CEFET-MG para a disciplina de Aprendizado Estatístico ministrada pelo professor Fabio Rocha da Silva.