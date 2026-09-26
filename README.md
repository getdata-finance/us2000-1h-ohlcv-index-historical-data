# US2000 1h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-46_814_rows-blue)](https://getdata.finance/datasets/us2000) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/us2000)

### -> [**Download the full US2000 dataset on getdata.finance**](https://getdata.finance/datasets/us2000)

**US2000 1h OHLCV index historical data** — ultra high-quality 1h OHLCV for **Russell 2000**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1h OHLCV** for **Russell 2000** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/us2000) · **46,814** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `US2000_1h.csv` (3,018 rows, `2026-03-26` -> `2026-09-25`, 260.40 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/us2000)** — **46,814** `1h` rows (full `1m`: 2,717,412), **11 timeframes**, `2018-10-26` -> `2026-09-25`.

## Download sample

**[US2000_1h.csv](https://github.com/getdata-finance/us2000-1h-ohlcv-index-historical-data/blob/main/US2000_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/us2000-1h-ohlcv-index-historical-data/main/US2000_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/us2000-1h-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/us2000-1h-ohlcv-index-historical-data/](https://getdata-finance.github.io/us2000-1h-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/us2000](https://getdata.finance/datasets/us2000)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/us2000))** |
|---|--:|---|
| Instrument | Russell 2000 · Index | Russell 2000 · Index |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 3,018 | **46,814** |
| Size | 260.40 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/us2000) |
| Period | `2026-03-26` -> `2026-09-25` | `2018-10-26` -> `2026-09-25` |
| File | `US2000_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/us2000) |
| Coverage report | — | [US2000 coverage](https://getdata.finance/coverage/us2000) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/us2000)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/us2000) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`US2000_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T03:00:00+00:00 | 2536.97 | 2550.33 | 2536.32 | 2546.22 | 6179 |
| 2026-03-26T04:00:00+00:00 | 2546.22 | 2546.52 | 2539.78 | 2540.48 | 4462 |
| 2026-03-26T05:00:00+00:00 | 2540.48 | 2542.36 | 2532.37 | 2532.88 | 7515 |
| 2026-03-26T06:00:00+00:00 | 2532.88 | 2537.48 | 2530.51 | 2536.57 | 8349 |
| 2026-03-26T07:00:00+00:00 | 2536.57 | 2537.23 | 2525.48 | 2531.41 | 8881 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T16:00:00+00:00 | 2842.68 | 2856.38 | 2841.68 | 2843.97 | 39342 |
| 2026-09-25T17:00:00+00:00 | 2843.97 | 2846.78 | 2838.21 | 2841.67 | 11610 |
| 2026-09-25T18:00:00+00:00 | 2841.67 | 2844.66 | 2839.82 | 2844.38 | 9730 |
| 2026-09-25T19:00:00+00:00 | 2844.38 | 2849.88 | 2841.31 | 2841.78 | 13129 |
| 2026-09-25T20:00:00+00:00 | 2841.78 | 2844.43 | 2841.51 | 2843.76 | 2342 |

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

df = pd.read_csv('US2000_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('US2000_1h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('US2000_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **US2000** archive on **[getdata.finance](https://getdata.finance/datasets/us2000)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **46,814** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full US2000 dataset on getdata.finance](https://getdata.finance/datasets/us2000)**

---
*GetData · US2000 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/us2000)*
