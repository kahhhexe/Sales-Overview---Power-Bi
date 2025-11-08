# 📊 Projeto Power BI – Sales Overview

---

## 🧠 Sobre o Projeto
Esse projeto faz parte do meu aprendizado desenvolvido ao longo do curso de **SQL**.  
O **Sales Overview** é um dashboard criado em **Power BI** com o objetivo de analisar o desempenho de vendas por **região e planta**, considerando coordenadas de **latitude e longitude** e segmentações por **Business Line**, como **aditivos e lubrificantes**.

O projeto consolida dados de vendas e custos, oferecendo uma visão estratégica sobre a performance comercial e permitindo identificar **tendências regionais**, **margens de lucro** e **oportunidades de otimização**.

<p align="center">
  <img src="Imagens/Página inicial.png" alt="Página Inicial do Dashboard" width="700"/>
</p>

---

## 🚀 Objetivo Principal
Analisar as **vendas por região e planta**, explorando diferentes níveis de detalhe e interatividade, como **tooltips**, **drill-throughs** e **filtros dinâmicos**, para facilitar insights sobre o negócio.

---

## 📈 Principais Métricas e KPIs
- 💰 **Receita Total**
- 📉 **Custo Total**
- 📊 **Lucro (%)**
- 💹 **Margem (%)**
- 🔢 **Vendas Mensais**
- 🧾 **Análise de Margem e Rentabilidade por Linha de Negócio**

---

## 🛠️ Tecnologias Utilizadas
- 🟡 **Power BI Desktop**
- 🧩 **Power Query** (ETL – Extração e Transformação de Dados)
- 🔢 **DAX** (Data Analysis Expressions) para medidas e KPIs
- 📈 **Power BI Service** (publicação e compartilhamento)
- 📊 **Excel / CSV** como fonte de dados

---

## 🧩 Etapas do Projeto

### 1️⃣ **Transformação de Dados – Power Query**
Modelagem, tratamento e limpeza das tabelas antes da carga no modelo.  
Nesta etapa foi realizada a importação dos dados para o Power BI, seguida da organização e padronização dos tipos de dados (texto, decimal, datas, longitude e latitude) — um processo essencial antes de iniciarmos a construção dos gráficos.

<p align="center">
  <img src="Imagens/Power Query.png" alt="Etapa Power Query" width="700"/>
</p>

---

### 2️⃣ **Criação de Medidas – DAX**
Construção das principais medidas de desempenho e KPIs.  
Neste projeto, foram criadas medidas utilizando DAX para calcular **custo**, **custo percentual**, **margem**, **margem percentual**, **total de vendas** e **volume de vendas em toneladas**.

<p align="center">
  <img src="Imagens/Dax.png" alt="Etapa DAX" width="700"/>
</p>

---

### 3️⃣ **Página Inicial do Dashboard**
Resumo executivo com KPIs e visão geral das vendas.  
Após a modelagem dos dados no Power Query e a criação das medidas em DAX, foi construída a página inicial do dashboard com os principais indicadores de performance.

<p align="center">
  <img src="Imagens/Página inicial.png" alt="Página Inicial" width="700"/>
</p>

---

### 4️⃣ **Tool Tip Personalizado**
Exibe detalhes dinâmicos ao passar o mouse sobre os gráficos.  
Essa ferramenta do Power BI é extremamente útil para visualizar informações rapidamente apenas passando o mouse sobre cada elemento, ajudando o gestor a responder perguntas-chave sem precisar navegar entre páginas.

<p align="center">
  <img src="Imagens/Tool Tip.png" alt="Tool Tip" width="700"/>
</p>

---

### 5️⃣ **Drill-through**
Permite navegar para outra página que contém informações detalhadas de cada venda.  
É uma ferramenta muito útil quando é necessário consultar dados específicos de um segmento.

<p align="center">
  <img src="Imagens/Drill-through.png" alt="Drill-through" width="700"/>
</p>

<p align="center">
  <img src="Imagens/Drill-through in.png" alt="Drill-through Detalhado" width="700"/>
</p>

---

### 6️⃣ **Filtros e Segmentações**
Filtros interativos que permitem refinar as análises conforme **segmento**, **divisão**, **planta** e **período** (Quartil, Ano e Mês).

a) Na primeira imagem eu realizado o desenvolvimento do indicador que ira abrir o meu menu ao clicar no botão.
<p align="center">
  <img src="Imagens/Filtro-in.png" alt="Filtros e Segmentações" width="700"/>
</p>

b) Na segunda imagem eu realizado o mesmo procedimento criando um novo indicador, mas agora para fechar o filtro ao clicar no botão voltar.
<p align="center">
  <img src="Imagens/Filtro-out.png" alt="Filtros e Segmentações" width="700"/>
</p>

c) E por último o resultado, ficou muito legal.
<p align="center">
  <img src="Imagens/Filtro.png" alt="Filtros e Segmentações" width="700"/>
</p>

---

## 🔗 Acesso ao Dashboard Online
Você pode visualizar o relatório completo no Power BI Service:  
👉 [**Acessar Dashboard Interativo**](https://app.powerbi.com/view?r=eyJrIjoiYjI5Y2E4Y2MtNzkwMy00YjFiLWFmYTYtOGFlYjZlM2E4YmM2IiwidCI6IjY1OWNlMmI4LTA3MTQtNDE5OC04YzM4LWRjOWI2MGFhYmI1NyJ9)

---

## 💡 Principais Insights
- 🌎 A região com maior receita é o **Sul**, concentrando mais de 40% do total.  
- 🏙️ As cidades com melhor performance apresentam maior margem percentual.  
- ⚙️ **Lubrificantes** têm margem superior à de **aditivos** em quase todas as regiões.  
- 📆 A receita apresentou **crescimento consistente mês a mês**, indicando boa tendência de mercado.

---

## 📚 Aprendizados Técnicos
Durante o desenvolvimento deste projeto, aprimorei habilidades importantes, como:

- 🔄 **Modelagem de Dados** no Power BI utilizando o conceito de **esquema estrela**.  
- 🧹 **Limpeza e padronização de dados** com Power Query.  
- ⚙️ **Criação de medidas DAX** aplicando funções como `CALCULATE`, `DIVIDE`, `SUMX`, e `FILTER`.  
- 📊 **Criação de dashboards interativos** e dinâmicos com recursos avançados (Drill-through, Tooltip e filtros personalizados).  
- 📈 **Publicação e compartilhamento** do relatório no Power BI Service.  
- 🧠 **Interpretação de KPIs** e geração de insights estratégicos a partir dos dados.

Esses aprendizados fortaleceram minha base em **análise de dados**, **visualização de informações** e **tomada de decisão orientada a dados**.

---

⭐ Se este projeto te inspirou, **deixe uma estrela no repositório** para apoiar o trabalho!
