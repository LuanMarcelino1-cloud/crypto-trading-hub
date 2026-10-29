# Crypto Trading Hub

Hub central para operações de cripto. Duas camadas:

## Camada 1 — Execução (day-trader-skill)
Fork: https://github.com/LuanMarcelino1-cloud/day-trader-skill

Onze skills em Python para day trading:
- Alertas de preço
- Análise fundamentalista via SEC
- Gestão de portfólio
- Timing de entrada e saída
- Notícias
- Trades da Pelosi
- Gestão de risco
- Scanner de mercado
- Máquina do tempo para replay de operações

## Camada 2 — Conhecimento (graphify)
Fork: https://github.com/LuanMarcelino1-cloud/graphify

Transforma o código, docs e schemas em um grafo de conhecimento consultável. Útil pra entender como as skills se conectam e onde estão as dependências.

## Próximos passos
- [ ] Adicionar os forks como submódulos
- [ ] Configurar API keys (Binance, Coinbase, SEC EDGAR)
- [ ] Escrever o orquestrador que chama as skills em sequência
- [ ] Backtest com dados históricos

## Aviso
Nada aqui é conselho financeiro. Trading envolve risco real de perda.