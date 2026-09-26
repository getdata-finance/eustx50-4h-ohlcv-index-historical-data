# EUSTX50 4h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-15_783_rows-blue)](https://getdata.finance/datasets/eustx50) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/eustx50)

### -> [**Download the full EUSTX50 dataset on getdata.finance**](https://getdata.finance/datasets/eustx50)

**EUSTX50 4h OHLCV index historical data** — ultra high-quality 4h OHLCV for **EURO STOXX 50**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 4h OHLCV** for **EURO STOXX 50** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`4h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/eustx50) · **15,783** `4h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `4h` sample updated in sync

> **Sample on GitHub** · `EUSTX50_4h.csv` (518 rows, `2026-03-26` -> `2026-09-25`, 48.50 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/eustx50)** — **15,783** `4h` rows (full `1m`: 2,770,438), **11 timeframes**, `2012-08-27` -> `2026-09-25`.

## Download sample

**[EUSTX50_4h.csv](https://github.com/getdata-finance/eustx50-4h-ohlcv-index-historical-data/blob/main/EUSTX50_4h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/eustx50-4h-ohlcv-index-historical-data/main/EUSTX50_4h.csv)) · [GitHub Releases](https://github.com/getdata-finance/eustx50-4h-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/eustx50-4h-ohlcv-index-historical-data/](https://getdata-finance.github.io/eustx50-4h-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/eustx50](https://getdata.finance/datasets/eustx50)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/eustx50))** |
|---|--:|---|
| Instrument | EURO STOXX 50 · Index | EURO STOXX 50 · Index |
| Timeframes | `4h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 4h rows | 518 | **15,783** |
| Size | 48.50 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/eustx50) |
| Period | `2026-03-26` -> `2026-09-25` | `2012-08-27` -> `2026-09-25` |
| File | `EUSTX50_4h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/eustx50) |
| Coverage report | — | [EUSTX50 coverage](https://getdata.finance/coverage/eustx50) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`4h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/eustx50)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `4h` sample · [getdata.finance](https://getdata.finance/datasets/eustx50) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `4h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EUSTX50_4h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T04:00:00+00:00 | 5658.09 | 5660.09 | 5635.61 | 5645.59 | 1342.17572 |
| 2026-03-26T08:00:00+00:00 | 5645.59 | 5664.1 | 5610.09 | 5612.59 | 13332 |
| 2026-03-26T12:00:00+00:00 | 5612.59 | 5665.61 | 5607.61 | 5634.59 | 17687 |
| 2026-03-26T16:00:00+00:00 | 5634.59 | 5641.61 | 5579.1 | 5581.11 | 6824.4602 |
| 2026-03-26T20:00:00+00:00 | 5581.11 | 5692.1 | 5580.59 | 5609.15 | 1456 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-24T16:00:00+00:00 | 6288.38 | 6336.39 | 6283.37 | 6312.44 | 11690 |
| 2026-09-25T04:00:00+00:00 | 6312.44 | 6340.12 | 6312.44 | 6319.61 | 3578 |
| 2026-09-25T08:00:00+00:00 | 6319.61 | 6346.12 | 6313.6 | 6324.11 | 5859 |
| 2026-09-25T12:00:00+00:00 | 6324.11 | 6334.12 | 6296.11 | 6329.12 | 8056 |
| 2026-09-25T16:00:00+00:00 | 6329.12 | 6353.62 | 6327.12 | 6351.65 | 5831 |

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

df = pd.read_csv('EUSTX50_4h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EUSTX50_4h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('EUSTX50_4h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='4h')
print(pf.stats())
```

## Download full data

The complete **EUSTX50** archive on **[getdata.finance](https://getdata.finance/datasets/eustx50)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **15,783** rows at `4h`, plus all other timeframes in the same ZIP.

**[-> Get the full EUSTX50 dataset on getdata.finance](https://getdata.finance/datasets/eustx50)**

---
*GetData · EUSTX50 4h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/eustx50)*
