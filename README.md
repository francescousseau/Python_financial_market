# Python Financial Market

Estudos em Python com dados públicos do mercado financeiro, obtidos com `yfinance`.

| Projeto | O que faz |
|---|---|
| [`action_tracker`](action_tracker/) | Rastreia o desempenho de um portfólio de ações ao longo do tempo, com gráficos de preço ajustado e de preços normalizados (`yfinance` e `matplotlib`). |
| [`retorno_bancario`](retorno_bancario/) | Analisa o retorno das ações de bancos brasileiros (Itaú, Banco do Brasil, Santander e Bradesco) em relação ao índice IBOVESPA, usando também a planilha `lucro_bancos.xlsx`. |

## Como executar

```bash
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

Abra o notebook do projeto desejado e execute as células em ordem.

## Observações

- Os dados vêm de uma fonte pública acessada pelo `yfinance`. Os resultados mudam com a data de execução e com a versão da biblioteca. Versões recentes do `yfinance` ajustam os preços por padrão e podem não devolver a coluna `Adj Close` usada em `action_tracker`; se ocorrer um erro de coluna, use `auto_adjust=False` na chamada de `download`.
- Este repositório tem finalidade educacional. **Não constitui recomendação de investimento.**
- Não há arquivo de licença neste repositório. A licença do código deve ser definida pelo autor.

## Autor

Francesco Cousseau
