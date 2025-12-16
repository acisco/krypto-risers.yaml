project: Krypto-Risers Hunter
version: 0.2
last_updated: 2025-12-16
goal: Finne kryptoer som klatrer raskest i rank/pris tidlig – spotte neste 1000x tidlig med små innsatser (f.eks. 10 USD)
data_source: CoinGecko + CoinMarketCap (24h/7d/14d fokus, siden 30d-rank-endring er begrenset)

current_top_risers:
  - name: Hemi
    symbol: HEMI
    market_cap_rank: ~504
    24h_change: +97.5%
    7d_change: +109.5%
    14d_change: +174%
    comment: Topp gainer akkurat nå – lav cap, høy volumøkning. Sterk kandidat for videre klatring!

  - name: PumpBTC
    symbol: PUMP
    recent_change: Høy 24h (topp gainer)
    comment: Pump-relatert, ofte ekstremt volatil – kan gi raske multipler hvis momentum holder.

  - name: Pippin
    symbol: PIPPIN
    24h_change: +32.6%
    trending: Topp søkt på CoinGecko
    comment: Leder dagens gainers + trending hard. Ofte tegn på kommende pump – verdt å følge!

  - name: Magma Finance
    trending: Topp 3 søk
    24h_change: +27.5%
    comment: Sterk momentum + høy søkeinteresse. Finans-narrativ funker bra i bull.

  - name: Luxxcoin
    symbol: LUX
    rank: ~828
    24h_change: +103%
    comment: Ekstrem 24h-pump fra lav rank – klassisk low-cap riser. Høy risiko, høy reward.

  - name: Wojak
    symbol: WOJAK
    rank: ~929
    24h_change: +36.8%
    comment: Meme-coin med sterk oppgang – kan fortsette hvis community pusher.

tasks_next:
  - [ ] Lag scraper.py (automatisk henting fra CoinGecko API – jeg dikterer koden neste)
  - [ ] Sett opp GitHub Actions for daglig auto-update av denne fila
  - [ ] Legg til filter for å unngå stablecoins/scams
  - [ ] Telegram-bot for varsler når en coin går +100% på 7 dager

checklist:
  - [x] Repo opprettet
  - [x] Første yaml-fil committet
  - [x] Første manuelle data-run
  - [ ] Automatisk scraper
  - [ ] Test-investering i en riser?
