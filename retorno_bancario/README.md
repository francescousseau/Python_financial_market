# Projeto de Análise de Retorno de Ações bancárias em relação ao indice IBOVESPA

Este projeto de Data Science tem como objetivo analisar a rentabilidade das ações bancárias em relação ao índice IBOVESPA. A análise de retorno das ações bancárias é de grande importância no mercado financeiro, permitindo aos investidores avaliar o desempenho dessas ações em comparação com o índice de referência.

# Visão Geral

A análise será realizada utilizando técnicas de processamento de dados e visualização, buscando identificar padrões e tendências nos retornos das ações bancárias em relação ao IBOVESPA ao longo do tempo. Serão considerados diversos indicadores, como retorno total, retorno anualizado, volatilidade e índices de desempenho, para fornecer uma visão abrangente da rentabilidade das ações bancárias em comparação com o mercado em geral.

Ao analisar o retorno das ações bancárias em relação ao IBOVESPA, espera-se obter insights valiosos que possam auxiliar investidores e tomadores de decisão a identificar oportunidades de investimento e entender o desempenho do setor bancário em relação ao mercado mais amplo.

O projeto utiliza bibliotecas de processamento de dados, como pandas e yfinance, além das bibliotecas de visualização, como matplotlib.pyplot e matplotlib.ticker, para realizar a análise e a visualização dos dados. Os dados utilizados são provenientes de um arquivo em formato Excel disponível na pasta do projeto.

# Instalação

1. Clone o repositório e entre na pasta do projeto: `cd Python_financial_market/retorno_bancario`.
2. Crie e ative um ambiente virtual.
3. Instale as dependências: `pip install -r ../requirements.txt`.

# Uso

1. Abra o notebook `bancos_retorno.ipynb` com Jupyter (`jupyter lab`).
2. Execute as células em ordem. O notebook lê a planilha `lucro_bancos.xlsx` desta mesma pasta (caminho relativo) e baixa os preços de ações e do índice IBOVESPA com `yfinance`.

Bibliotecas usadas: `pandas`, `yfinance`, `matplotlib.pyplot` e `matplotlib.ticker`.

> **Observação:** o `yfinance` consulta uma fonte pública que pode mudar. Os resultados dependem da versão da biblioteca e da data da execução.

# Contribuição

Contribuições de outros colaboradores são bem-vindas para aprimorar e expandir a análise de retorno das ações bancárias em relação ao IBOVESPA. Para contribuir, basta abrir uma issue descrevendo a proposta de contribuição, fazer um fork do repositório, criar um branch para a feature ou correção, implementar as alterações necessárias e abrir uma solicitação de pull (pull request) com uma descrição detalhada das mudanças feitas.


Se você deseja contribuir com este projeto de Data Science no mercado financeiro, siga as diretrizes a seguir:

Abra uma issue descrevendo a sua proposta de contribuição.

Faça um fork do repositório e crie um branch para a sua feature ou correção.

Faça as alterações necessárias e teste-as.

Abra uma solicitação de pull (pull request) com uma descrição detalhada das mudanças feitas.


# Licença

Este projeto está sob licença Open Source, permitindo o compartilhamento, modificação e uso livre dos resultados e do código fonte.


