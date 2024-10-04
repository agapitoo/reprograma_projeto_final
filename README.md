# Análise de Dados: Nascidos Vivos no Vale Do Ribeira SP

Este projeto realiza uma análise detalhada dos dados de nascidos vivos no Vale Do Ribeira, utilizando dados públicos do **Sistema de Informações sobre Nascidos Vivos (SINASC)**. 
O foco principal é examinar os partos por município, identificar tendências e fornecer insights com base em gráficos e outras visualizações.

## 🗂️ Dados Utilizados

Os dados foram retirados diretamente do portal **DATASUS**, disponibilizado pela Secretaria Estadual de Saúde.

- **Fonte**: MS/SVSA/CGIAE - Sistema de Informações sobre Nascidos Vivos - SINASC.
- **Link para consulta**: [Acesse o site da Secretaria Estadual de Saúde](http://tabnet.datasus.gov.br/cgi/tabcgi.exe?sinasc/cnv/nvsp.def).

Os dados incluem informações detalhadas sobre nascidos vivos em diferentes municípios do Vale Do Ribeira.

## ⚙️ Ferramentas Utilizadas

- **Python**: Linguagem principal para manipulação e análise dos dados.
- **Pandas**: Para tratamento e limpeza dos dados.
- **Jupyter Notebook**: Para organização e desenvolvimento do código.
  
## 📊 Análises Realizadas

O projeto inclui várias etapas de processamento e visualização de dados. A principal análise envolve a soma total de partos por município, permitindo a visualização e comparação clara dos dados por meio de gráficos.

### Principais Tarefas

1. **Limpeza dos Dados**:
   - Substituição de valores inconsistentes (como o símbolo `'-'`) por valores numéricos (zeros).
   - Conversão de colunas relevantes para tipos numéricos e tratamento de valores nulos.

2. **Análise de Partos por Município**:
   - Agrupamento dos dados por município para calcular o total de partos em cada região.
   - Geração de gráficos de barras para visualizar os totais de partos por município.

## 📚 Estrutura do Projeto

    ├── data/               # Pasta contendo os arquivos de dados
    ├── notebooks/          # Notebooks com o código de análise
    ├── images/             # Imagens geradas (como gráficos)
    └── README.md           # Você está aqui! 😄


## 📈 Próximos Passos

Implementar novas métricas e visualizações, como a análise de partos por ano.
Comparar os dados de diferentes municípios ao longo do tempo.
Explorar outros indicadores fornecidos pelo SINASC.


## 📌 Contribuição

Contribuições são bem-vindas! Se você tiver sugestões, correções ou quiser colaborar com novas funcionalidades, sinta-se à vontade para abrir um pull request.
