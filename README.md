# 📊 Dashboard de Análise de Salários na Área de Dados

Um painel interativo construído com Streamlit para explorar e analisar dados de salários na área de tecnologia e dados. O dashboard permite que os usuários filtrem os dados por diversos critérios e visualizem as informações através de métricas-chave e gráficos dinâmicos.


## 🚀 Funcionalidades

O dashboard oferece uma série de recursos para uma análise completa:

  * **Métricas Principais (KPIs):** Visualização rápida de indicadores importantes como:

      * Salário Médio Anual (USD)
      * Salário Máximo Registrado
      * Total de Registros na base filtrada
      * Cargo Mais Frequente

  * **Filtros Interativos:** Refine a análise com filtros detalhados na barra lateral:

      * Ano do registro
      * Nível de Senioridade (Júnior, Pleno, Sênior, etc.)
      * Tipo de Contrato (CLT, PJ)
      * Tamanho da Empresa

  * **Visualizações Dinâmicas:** Gráficos interativos para explorar os dados sob diferentes perspectivas:

      * **Top 10 Cargos por Salário Médio:** Um gráfico de barras horizontais que mostra os cargos com as maiores médias salariais.
      * **Distribuição de Salários:** Um histograma que exibe a frequência das diferentes faixas salariais.
      * **Proporção de Tipos de Trabalho:** Um gráfico de pizza (donut) que mostra a distribuição entre trabalho remoto, híbrido e presencial.
      * **Salário Médio de Cientistas de Dados por País:** Um mapa coroplético que ilustra a média salarial para a posição de *Data Scientist* em diferentes países.

  * **Tabela de Dados Detalhada:** Uma tabela interativa que exibe os dados brutos de acordo com os filtros aplicados, permitindo ordenação e busca.

-----

## 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando as seguintes tecnologias e bibliotecas Python:

  * **[Streamlit](https://streamlit.io/):** Para a criação e prototipação rápida da aplicação web interativa.
  * **[Pandas](https://pandas.pydata.org/):** Para a manipulação, limpeza e análise dos dados.
  * **[Plotly Express](https://plotly.com/python/plotly-express/):** Para a geração dos gráficos dinâmicos e interativos.

-----

## 📂 Fonte dos Dados

Os dados utilizados neste dashboard foram obtidos a partir de um arquivo CSV público, disponível no seguinte repositório do GitHub:
[vqrca/dashboard\_salarios\_dados](https://www.google.com/search?q=https://github.com/vqrca/dashboard_salarios_dados)

O link direto para o arquivo é: `https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv`

-----

## ⚙️ Como Executar o Projeto Localmente

Para executar este dashboard em sua máquina local, siga os passos abaixo.

### Pré-requisitos

  * Ter o [Python](https://www.python.org/downloads/) (versão 3.8 ou superior) instalado.
  * Ter o `pip` (gerenciador de pacotes do Python) instalado e atualizado.
