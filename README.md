# SPX500 3m OHLCV Stock index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_025_780_rows-blue)](https://getdata.finance/datasets/spx500) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/spx500)

### -> [**Download the full SPX500 dataset on getdata.finance**](https://getdata.finance/datasets/spx500)

**SPX500 3m OHLCV stock index historical data** — ultra high-quality 3m OHLCV for **S&P 500**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **S&P 500** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/spx500) · **2,025,780** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `SPX500_3m.csv` (59,222 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/spx500)** — **2,025,780** `1m` rows (~134.80 MB), **11 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W), `2008-08-19` -> `2026-07-31`.

## Download sample

**[SPX500_3m.csv](https://github.com/getdata-finance/spx500-3m-ohlcv-index-historical-data/blob/main/SPX500_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/spx500-3m-ohlcv-index-historical-data/main/SPX500_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/spx500-3m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/spx500-3m-ohlcv-index-historical-data/](https://getdata-finance.github.io/spx500-3m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/spx500](https://getdata.finance/datasets/spx500)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/spx500))** |
|---|--:|---|
| Instrument | S&P 500 · Stock index | S&P 500 · Stock index |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 59,222 | **2,025,780** |
| Size | 4.07 MB | ~134.80 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2008-08-19` -> `2026-07-31` |
| File | `SPX500_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/spx500) |
| Coverage report | — | [SPX500 coverage](https://getdata.finance/coverage/spx500) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/spx500)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

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
| 2026-02-02T05:54:00+00:00 | 6856.99 | 6858.74 | 6856.23 | 6856.37 | 852 |
| 2026-02-02T05:57:00+00:00 | 6856.37 | 6859.73 | 6854.86 | 6858 | 887 |
| 2026-02-02T06:00:00+00:00 | 6858 | 6862.49 | 6856.48 | 6858.23 | 973 |
| 2026-02-02T06:03:00+00:00 | 6858.23 | 6859.25 | 6855.23 | 6855.87 | 790 |
| 2026-02-02T06:06:00+00:00 | 6855.87 | 6856.75 | 6853.73 | 6854.23 | 815 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T20:30:00+00:00 | 7483.77 | 7484.27 | 7481.77 | 7483.03 | 339 |
| 2026-07-31T20:33:00+00:00 | 7483.03 | 7485.27 | 7482.78 | 7484.28 | 221 |
| 2026-07-31T20:36:00+00:00 | 7484.28 | 7485.28 | 7483.76 | 7485.02 | 204 |
| 2026-07-31T20:39:00+00:00 | 7485.02 | 7485.52 | 7484.26 | 7485.27 | 161 |
| 2026-07-31T20:42:00+00:00 | 7485.27 | 7485.78 | 7483.01 | 7483.37 | 285 |

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
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
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
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **SPX500** archive on **[getdata.finance](https://getdata.finance/datasets/spx500)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,025,780** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full SPX500 dataset on getdata.finance](https://getdata.finance/datasets/spx500)**

---
*GetData · SPX500 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/spx500) · 2026-08-04 UTC*
