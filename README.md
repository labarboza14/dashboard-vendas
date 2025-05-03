# 📊 Dashboard Interativo de Vendas com Streamlit + Google Sheets

Este projeto é um dashboard interativo construído com **Streamlit**, que consome dados diretamente de uma planilha no **Google Sheets**. Foi criado para fins de **prática, estudo e demonstração** de soluções simples e eficazes para visualização de dados de vendas.

> ⚠️ Os dados utilizados são **fictícios** e foram criados exclusivamente para fins educacionais.

## ✅ Funcionalidades

- Carregamento automático de dados de uma planilha no Google Sheets.
- Visualização tabular dos dados atualizados.
- Filtro por intervalo de **datas** com seleção interativa.
- Cálculo de:
  - 📆 Faturamento total do período selecionado
  - 💰 Faturamento acumulado de todo o período disponível
  - 📦 Quantidade total de itens vendidos
  - 🛒 Quantidade de produtos únicos
  - 🧑‍💼 Quantidade de vendedores distintos
- Gráficos interativos com **Plotly**:
  - 📊 Total por canal de venda (gráfico de pizza)
  - 💳 Faturamento por forma de pagamento (gráfico de barras)
  - 🧑‍💼 Ranking de vendedores (gráfico de barras)

## 🚀 Como Executar

Você pode rodar este projeto diretamente no Google Colab com suporte a Streamlit e ngrok.

1. **Abra o notebook no Colab**: [🔗 Link para o notebook](https://colab.research.google.com/drive/1cU9aYzzlFGtd7GzvIaZ_yOG5zf8xPfRg)
2. **Execute as células passo a passo**
3. **O link do ngrok será gerado automaticamente**
4. Acesse o dashboard via link público fornecido no final

## 📁 Estrutura do Projeto

```

📦 dashboard-vendas
├── app.py                # Código principal do dashboard
├── README.md             # Este arquivo
├── dash\_vendas.ipynb     # Notebook no Colab com o mesmo conteúdo


```

## 🧰 Tecnologias Utilizadas

- Python
- Streamlit
- Pandas
- Plotly
- Google Sheets API (via `gspread`)
- Ngrok (exposição do app via link público)
- Google Colab

## 🙋🏽‍♀️ Para que serve esse projeto?

Este projeto é ideal para:

- Pessoas em transição de carreira para tecnologia
- Estudantes de análise de dados
- Demonstrações de dashboards simples com dados reais (mesmo que fictícios)
- Prática de integração com Google Sheets


