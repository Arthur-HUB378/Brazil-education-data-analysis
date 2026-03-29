# Analise-escolaridade-brasil
Análise exploratória de dados educacionais do Brasil utilizando Python e dados do IBGE.

# 📊 Desigualdade de Escolarização no Brasil – Análise de Dados

Este projeto tem como objetivo analisar a desigualdade de escolarização no Brasil utilizando dados reais do IBGE. A análise busca identificar padrões e disparidades no acesso à educação considerando fatores como região, sexo, raça/cor e faixa etária.

---

## 🎯 Objetivo

Realizar uma Análise Exploratória de Dados (EDA) para compreender como a escolaridade está distribuída entre diferentes grupos da população brasileira, evidenciando possíveis desigualdades.

---

## 🗂️ Fonte dos Dados

### 📌 Instituição

Dados fornecidos pelo Instituto Brasileiro de Geografia e Estatística (IBGE), órgão oficial responsável pela produção de dados estatísticos no Brasil.

### 📌 Origem

Os dados foram obtidos através do sistema SIDRA (Sistema IBGE de Recuperação Automática), que disponibiliza informações provenientes dos Censos Demográficos.

### 📌 Descrição dos Dados

- Dados quantitativos e demográficos  
- População com 10 anos ou mais de idade  
- Variáveis analisadas:
  - Nível de instrução  
  - Região geográfica  
  - Raça/cor  
  - Faixa etária  
  - Sexo  

### 📌 Confiabilidade

Os dados são altamente confiáveis, pois são provenientes de fontes oficiais e amplamente utilizados em pesquisas acadêmicas e formulação de políticas públicas.

---

## ⚠️ Problema

A desigualdade de escolarização no Brasil é uma questão relevante, evidenciando que o acesso à educação varia de acordo com fatores como região, raça/cor e sexo.

Embora a educação seja um direito universal, sua distribuição ainda ocorre de forma desigual entre diferentes grupos da população.

---

## ❓ Perguntas Analíticas

- Quais são as diferenças nos níveis de escolaridade entre as regiões do Brasil?  
- Existem diferenças significativas entre homens e mulheres?  
- Como a escolaridade se distribui entre diferentes grupos de raça/cor?  
- Como a escolaridade varia entre diferentes faixas etárias?  

---

## 🛠️ Tecnologias Utilizadas

- Python  
- Pandas  
- Matplotlib  

---

## 🔄 Etapas do Projeto

### 1. Detecção de dados ausentes
- Identificação de valores faltantes  
- Detecção de símbolos inválidos (como "-")  

### 2. Limpeza e tratamento dos dados
- Substituição de valores inválidos por NaN  
- Conversão de colunas para formato numérico  
- Renomeação de colunas para melhor entendimento  

### 3. Padronização de variáveis
- Remoção de espaços em branco  
- Padronização de texto (letras maiúsculas/minúsculas)  

### 4. Verificação de consistência
- Conferência entre valores totais e soma de subgrupos  

### 5. Preparação dos dados
- Criação de novas variáveis (ex: proporção de homens)  
- Filtragem de dados relevantes para análise  

---

## 📈 Análise Exploratória de Dados (EDA)

A análise foi realizada por meio de agrupamentos e visualizações, incluindo:

- Comparação por região  
- Comparação por sexo  
- Análise por raça/cor  
- Avaliação por faixa etária  

---

## 📊 Principais Insights

- Existem diferenças significativas nos níveis de escolaridade entre as regiões do Brasil  
- As regiões Sudeste e Sul apresentam maior proporção de pessoas com níveis educacionais mais elevados em comparação com Norte e Nordeste  
- Há desigualdades entre grupos de raça/cor, com populações pretas e pardas apresentando menor acesso a níveis mais altos de escolaridade  
- As diferenças entre homens e mulheres são menores quando comparadas às desigualdades regionais e raciais  
- A escolaridade varia entre faixas etárias, refletindo mudanças ao longo das gerações  

---

## 📊 Visualizações

![Escolaridade por Raça/Cor](C:\Users\ArtZ\Projetos\Imagens\Grafico1.png)

![Escolaridade por Sexo](C:\Users\ArtZ\Projetos\Imagens\Grafico2.png)

![Escolaridade por Região](C:\Users\ArtZ\Projetos\Imagens\Grafico3.png)

![Escolaridade entre jovens](C:\Users\ArtZ\Projetos\Imagens\Grafico4.png)

---

## ▶️ Como Executar o Projeto

1. Clone este repositório:
```bash
git clone https://github.com/Arthur-HUB378/Brazil-education-data-analysis.git
