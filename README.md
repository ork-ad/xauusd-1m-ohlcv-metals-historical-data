# XAUUSD 1m OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-4_177_899_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)]() [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full XAUUSD dataset on ork.ad**](https://ork.ad/)

**XAUUSD 1m OHLCV Precious metals historical data** — ultra high-quality one-minute OHLCV for **Gold / US Dollar**. Near-continuous precious-metals liquidity across global sessions. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1-minute OHLCV** for **Gold / US Dollar** (Precious metals)
- **Near-continuous precious-metals liquidity across global sessions**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m` only) · **13 timeframes** on [ork.ad](https://ork.ad/) · **4,177,899** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `XAUUSD_1m.csv` (113,570 rows, `2026-03-03` → `2026-06-26`). **Full archive on [ork.ad](https://ork.ad/)** — **4,177,899** `1m` rows (~220.47 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2014-05-18` → `2026-06-26`.

## Download sample

**[XAUUSD_1m.csv](https://github.com/ork-ad/xauusd-1m-ohlcv-metals-historical-data/blob/main/XAUUSD_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/xauusd-1m-ohlcv-metals-historical-data/main/XAUUSD_1m.csv)) · [GitHub Releases](https://github.com/ork-ad/xauusd-1m-ohlcv-metals-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/xauusd-1m-ohlcv-metals-historical-data/](https://ork-ad.github.io/xauusd-1m-ohlcv-metals-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Gold / US Dollar · Precious metals | Gold / US Dollar · Precious metals |
| Timeframes | `1m` only (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1m rows | 113,570 | **4,177,899** |
| Size | 6.13 MB | ~220.47 MB |
| Period | `2026-03-03` → `2026-06-26` | `2014-05-18` → `2026-06-26` |
| File | `XAUUSD_1m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **1-minute (`1m`) evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub 1m samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAUUSD_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-03 04:57:00 | 5364.37 | 5365.6 | 5361.71 | 5364.72 | 474 |
| 2026-03-03 04:58:00 | 5364.72 | 5366.06 | 5363.41 | 5363.78 | 531 |
| 2026-03-03 04:59:00 | 5363.78 | 5365.06 | 5360.46 | 5360.52 | 759 |
| 2026-03-03 05:00:00 | 5360.52 | 5362.58 | 5355.91 | 5358.54 | 1415 |
| 2026-03-03 05:01:00 | 5358.54 | 5361.71 | 5356.15 | 5361.59 | 842 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-26 20:40:00 | 4069.12 | 4069.68 | 4068.69 | 4069.67 | 190.00 |
| 2026-06-26 20:41:00 | 4069.67 | 4070.71 | 4069.47 | 4070.10 | 251.00 |
| 2026-06-26 20:42:00 | 4070.10 | 4070.10 | 4069.62 | 4069.83 | 101.00 |
| 2026-06-26 20:43:00 | 4069.83 | 4070.06 | 4069.29 | 4069.98 | 158.00 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('XAUUSD_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XAUUSD_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('XAUUSD_1m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **XAUUSD** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **4,177,899** rows at `1m`, plus all higher timeframes in the same ZIP.

**[→ Get the full XAUUSD dataset on ork.ad](https://ork.ad/)**

---
*GetData · XAUUSD 1m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-02 UTC*