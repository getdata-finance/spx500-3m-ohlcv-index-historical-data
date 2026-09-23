# SPX500 3m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_000_238_rows-blue)](https://getdata.finance/datasets/spx500) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/spx500)

### -> [**Download the full SPX500 dataset on getdata.finance**](https://getdata.finance/datasets/spx500)

**SPX500 3m OHLCV index historical data** — ultra high-quality 3m OHLCV for **S&P 500**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 3m OHLCV** for **S&P 500** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/spx500) · **2,000,238** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `SPX500_3m.csv` (60,241 rows, `2026-03-23` -> `2026-09-23`, 4.32 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/spx500)** — **2,000,238** `3m` rows (full `1m`: 5,815,518), **11 timeframes**, `2009-01-02` -> `2026-09-23`.

## Download sample

**[SPX500_3m.csv](https://github.com/getdata-finance/spx500-3m-ohlcv-index-historical-data/blob/main/SPX500_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/spx500-3m-ohlcv-index-historical-data/main/SPX500_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/spx500-3m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/spx500-3m-ohlcv-index-historical-data/](https://getdata-finance.github.io/spx500-3m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/spx500](https://getdata.finance/datasets/spx500)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/spx500))** |
|---|--:|---|
| Instrument | S&P 500 · Index | S&P 500 · Index |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 60,241 | **2,000,238** |
| Size | 4.32 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/spx500) |
| Period | `2026-03-23` -> `2026-09-23` | `2009-01-02` -> `2026-09-23` |
| File | `SPX500_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/spx500) |
| Coverage report | — | [SPX500 coverage](https://getdata.finance/coverage/spx500) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/spx500)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/spx500) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`SPX500_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-23T02:30:00+00:00 | 6496.84 | 6496.85 | 6494.73 | 6495.09 | 820 |
| 2026-03-23T02:33:00+00:00 | 6495.09 | 6495.11 | 6493.09 | 6493.35 | 596 |
| 2026-03-23T02:36:00+00:00 | 6493.35 | 6494.36 | 6490.34 | 6491.11 | 674 |
| 2026-03-23T02:39:00+00:00 | 6491.11 | 6492.1 | 6488.98 | 6491.22 | 766 |
| 2026-03-23T02:42:00+00:00 | 6491.22 | 6493.11 | 6489.22 | 6489.73 | 699 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-23T01:48:00+00:00 | 7768.8 | 7769.82 | 7768.68 | 7769.45 | 262 |
| 2026-09-23T01:51:00+00:00 | 7769.45 | 7769.95 | 7769.06 | 7769.69 | 178 |
| 2026-09-23T01:54:00+00:00 | 7769.69 | 7769.94 | 7768.8 | 7769.45 | 165 |
| 2026-09-23T01:57:00+00:00 | 7769.45 | 7769.95 | 7769.19 | 7769.82 | 132 |
| 2026-09-23T02:00:00+00:00 | 7769.82 | 7769.95 | 7769.82 | 7769.95 | 3 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('SPX500_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('SPX500_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('SPX500_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **SPX500** archive on **[getdata.finance](https://getdata.finance/datasets/spx500)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,000,238** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full SPX500 dataset on getdata.finance](https://getdata.finance/datasets/spx500)**

---
*GetData · SPX500 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/spx500)*
