# AI Trading Bot — Dashboard

Live dashboard van mijn AI-tradingbot-project (BTC/EUR, Kraken-data):
actuele koers, technische indicatoren (RSI, EMA-trend, volatiliteit),
backtestresultaten en de roadmap naar live trading.

**Bekijk de site:** straks live op Vercel — zie hieronder.

## Lokaal openen
Gewoon `index.html` openen in je browser. De live-koers werkt direct
(Kraken public API, geen key nodig).

## Live zetten via Vercel (gratis)
1. Ga naar https://vercel.com/signup → **Continue with GitHub**
2. **Add New → Project** → importeer deze repository
3. Klik **Deploy** — klaar, je krijgt een live URL

## Backtest (sept 2026, eerste versie)
| Strategie | Rendement | Max. daling | Trades | Winnaars |
|---|---|---|---|---|
| AI-bot | −2,7% | −21,8% | 37 | 22 |
| Buy & hold | +16,6% | −26,5% | — | — |

Eerste eerlijke resultaat: de bot verslaat vasthouden nog niet — het
model overfit nog. Dit is het startpunt om te itereren.

*Leerproject. Niets hier is financieel advies.*
