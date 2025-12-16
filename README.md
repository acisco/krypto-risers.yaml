project: Krypto-Risers Hunter
version: 0.1
last_updated: 2025-12-16
goal: Finne kryptoer som klatrer raskest i rank/pris tidlig – kjøp 10 USD i toppkandidater for potensiell 1000x
strategy:
  - Hent data fra CoinGecko/CoinMarketCap
  - Sorter etter høyest % oppgang siste 7-30 dager
  - Filtrer ut stablecoins og kjente scams
  - Fokus på coins som starter utenfor topp 1000 og klatrer inn

current_top_risers:
  - name: Hemi
    symbol: HEMI
    market_cap_rank: ~504
    24h_change: +97.5%
    7d_change: +109.5%
    14d_change: +174%
    comment: Sterk riser akkurat nå – lav cap, høy volumøkning. Verdi å følge!

  - name: PumpBTC
    symbol: PUMP
    market_cap_rank: Mid-range
    24h_change: Høy (topp gainer)
    comment: Pump-relatert, ofte volatilt men rask klatring.

  - name: MYX Finance
    symbol: MYX
    recent_gain: +10,773% (Q3 2025)
    comment: Absurd oppgang tidligere i året – viser potensialet i perps-trading coins.

  - name: Zora
    symbol: ZORA
    recent_gain: +573% (Q3)
    comment: Creator platform, sterk narrativ.

  - name: pippin
    trending: Topp søkt nå
    24h_change: +30.5%
    comment: Trending hard – ofte tegn på kommende pump.

  - name: Magma Finance
    trending: Topp 3
    24h_change: +27.5%
    comment: Finans-relatert, god momentum.

tasks_next:
  - Lag scraper.py (Python-script som henter data automatisk fra CoinGecko API)
  - Sett opp daglig run (f.eks. via GitHub Actions)
  - Legg til Telegram-bot for varsler når en coin klatrer +500% på 30 dager

checklist:
  - [x] Repo laget
  - [x] Første yaml-fil committet
  - [ ] Første automatiske scan
  - [ ] Investerings-test (10 USD i en riser?)# krypto-risers.yaml
