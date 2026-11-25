# Brazil customs exchange rate (Siscomex) Exchange Rates API — brcustoms-exchange-rate

[![npm version](https://img.shields.io/npm/v/brcustoms-exchange-rate.svg)](https://www.npmjs.com/package/brcustoms-exchange-rate)
[![license](https://img.shields.io/npm/l/brcustoms-exchange-rate.svg)](https://github.com/AllRates-Today/brcustoms-exchange-rate/blob/main/LICENSE)
[![zero dependencies](https://img.shields.io/badge/dependencies-0-brightgreen.svg)](https://www.npmjs.com/package/brcustoms-exchange-rate)
[![TypeScript](https://img.shields.io/badge/TypeScript-types%20included-3178C6.svg)](https://www.typescriptlang.org/)
[![USD/BRL today](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fallratestoday.com%2Fapi%2Fopen%2Fcentral-bank%2Fbrcustoms%3Fsource%3DUSD%26target%3DBRL&query=%24.rate&label=USD%2FBRL%20official%2C%20Brazil%20customs%20exchange%20rate%20(Siscomex)&color=0A7E8C&cacheSeconds=3600)](https://allratestoday.com/tax-authority-rates-api/brcustoms/)
[![rate date](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fallratestoday.com%2Fapi%2Fopen%2Fcentral-bank%2Fbrcustoms%3Fsource%3DUSD%26target%3DBRL&query=%24.rate_date&label=rate%20date&color=555&cacheSeconds=3600)](https://allratestoday.com/tax-authority-rates-api/brcustoms/)

**Official Brazil customs exchange rate (Siscomex) (Brazil) daily exchange rates for Node.js and TypeScript. The published tax authority rates behind tax filings, customs valuations, audits, and compliant invoicing — not market estimates, but the numbers Brazil customs exchange rate (Siscomex) itself prints, every business day.**

## 🚀 Why this client?

- 🏛️ **Official rates** — Brazil customs exchange rate (Siscomex)'s own table, with the publisher's own `rate_date` on every response
- 📅 **History back to 2016** — point-in-time tables and daily series for any past date
- 🔀 **Official vs derived, always flagged** — computed inverse/cross pairs carry `derived: true`, never mixed with official prints
- ⚡ **Zero dependencies** — pure ESM + CJS over global `fetch`; Node 18+, Bun, Deno, and edge runtimes
- 🔷 **Type-safe** — full TypeScript definitions shipped with the package
- 🧾 **Compliance-grade metadata** — `rate_type`, publication date, and source disclaimer on every response

> **Official rate, not mid-market:** every value here is a number Brazil customs exchange rate (Siscomex) itself published, fixed once printed and carrying the tax authority's own `rate_date` — what filings and audits require. Need the live mid-market rate for pricing or display instead? Use the [mid-market API](https://allratestoday.com/docs/) or [`@allratestoday/sdk`](https://www.npmjs.com/package/@allratestoday/sdk). The two can diverge by several percent.

## 🔑 Get your API key

Get a free API key at [allratestoday.com/register](https://allratestoday.com/register) — no credit card required. Latest rates are on every plan, including free.

## 📈 Latest official table

[![Latest Brazil customs exchange rate (Siscomex) table](https://allratestoday.com/api/open/central-bank/brcustoms/table.svg)](https://allratestoday.com/tax-authority-rates-api/brcustoms/)

The image is rendered live from the keyless endpoint, so it follows the tax authority's publications on npm and on GitHub alike without a new release. The same table as text is folded below for search and copy-paste: on GitHub [a daily Action](.github/workflows/daily-table.yml) refreshes it whenever the tax authority publishes a new table; on npm it is as of the package's publish date.

<!-- daily-table:start -->
<details>
<summary>Table as text: published 2026-11-25 by Brazil customs exchange rate (Siscomex) — 156 rates, first 60 shown. Updated 2026-11-25.</summary>

| Base | Quote | Type | Rate |
| --- | --- | --- | ---: |
| AED | BRL | customs | 1.5949 |
| AFN | BRL | customs | 0.08811 |
| ALL | BRL | customs | 0.07194 |
| AMD | BRL | customs | 0.01629 |
| AOA | BRL | customs | 0.006415 |
| ARS | BRL | customs | 0.003679 |
| AUD | BRL | customs | 3.8875 |
| AWG | BRL | customs | 3.2906 |
| AZN | BRL | customs | 3.4556 |
| BBD | BRL | customs | 2.9314 |
| BDT | BRL | customs | 0.04708 |
| BHD | BRL | customs | 15.5407 |
| BIF | BRL | customs | 0.001953 |
| BMD | BRL | customs | 5.8573 |
| BND | BRL | customs | 4.5434 |
| BOB | BRL | customs | 0.4998 |
| BSD | BRL | customs | 5.8573 |
| BTN | BRL | customs | 0.06304 |
| BWP | BRL | customs | 0.4346 |
| BYN | BRL | customs | 1.956 |
| BZD | BRL | customs | 2.9284 |
| CAD | BRL | customs | 4.0929 |
| CDF | BRL | customs | 0.002541 |
| CHF | BRL | customs | 7.0122 |
| CLF | BRL | customs | 235.3463 |
| CLP | BRL | customs | 0.005691 |
| CNH | BRL | customs | 0.8788 |
| CNY | BRL | customs | 0.8789 |
| COP | BRL | customs | 0.001627 |
| COU | BRL | customs | 0.704 |
| CRC | BRL | customs | 0.01328 |
| CUP | BRL | customs | 0.2441 |
| CVE | BRL | customs | 0.05827 |
| CZK | BRL | customs | 0.2633 |
| DJF | BRL | customs | 0.03298 |
| DKK | BRL | customs | 0.8598 |
| DOP | BRL | customs | 0.09846 |
| DZD | BRL | customs | 0.04292 |
| EGP | BRL | customs | 0.1081 |
| ERN | BRL | customs | 0.3905 |
| ETB | BRL | customs | 0.03629 |
| EUR | BRL | customs | 6.426 |
| FJD | BRL | customs | 2.5819 |
| FKP | BRL | customs | 7.635 |
| GBP | BRL | customs | 7.6824 |
| GEL | BRL | customs | 2.2871 |
| GHS | BRL | customs | 0.4981 |
| GIP | BRL | customs | 7.635 |
| GMD | BRL | customs | 0.07873 |
| GNF | BRL | customs | 0.0006626 |
| GTQ | BRL | customs | 0.7669 |
| GYD | BRL | customs | 0.02819 |
| HKD | BRL | customs | 0.747 |
| HNL | BRL | customs | 0.218 |
| HTG | BRL | customs | 0.04488 |
| HUF | BRL | customs | 0.01741 |
| IDR | BRL | customs | 0.0003215 |
| ILS | BRL | customs | 1.7483 |
| INR | BRL | customs | 0.06304 |
| IQD | BRL | customs | 0.003876 |

</details>

[Full table on the Brazil customs exchange rate (Siscomex) rates page](https://allratestoday.com/tax-authority-rates-api/brcustoms/) · Source: [Official rates published by BRCUSTOMS, served by AllRatesToday](https://allratestoday.com/tax-authority-rates-api/brcustoms/). Rates are as printed by the tax authority; AllRatesToday is not affiliated with it.
<!-- daily-table:end -->

## 📦 Installation

```bash
npm install brcustoms-exchange-rate
```

```bash
yarn add brcustoms-exchange-rate
```

```bash
pnpm add brcustoms-exchange-rate
```

Requires Node 18+ (global `fetch`); also runs on Bun, Deno and edge runtimes. Also published under the org scope as [`@allratestoday/brcustoms-exchange-rate`](https://www.npmjs.com/package/@allratestoday/brcustoms-exchange-rate) — same code, same versions.

## 🏁 Quick start

```js
import { getRate } from 'brcustoms-exchange-rate';

const pair = await getRate('USD', 'BRL', { apiKey: 'art_live_...' });
console.log(pair.rate, pair.rate_date); // the official Brazil customs exchange rate (Siscomex) rate, on the tax authority's own date
```

## 📚 API reference

- [Latest pair rate](#latest-pair-rate) — one pair from the latest official table
- [Full official table](#full-official-table) — everything the tax authority printed, in one call
- [Table for a date](#table-for-a-date) — the official table for an invoice or filing date
- [Daily time series](#daily-time-series) — one pair across a date range

---

### Latest pair rate

Free plan and up. Pairs the tax authority does not print directly are resolved from its table and flagged (see *Official vs derived rates* below).

```js
const pair = await getRate('USD', 'BRL', { apiKey: 'art_live_...' });
```

**Response:**

```javascript
{
  bank: 'brcustoms',
  name: 'Brazil customs exchange rate (Siscomex)',
  rate_date: '2026-11-25',   // Brazil customs exchange rate (Siscomex)'s own publication date
  source: 'USD',
  target: 'BRL',
  rate: 5.8573,
  rate_type: 'customs',
  derived: false,
  method: 'published',
  disclaimer: 'Official rates as published by the named central bank. On weekends/holidays the most recent published rate_date is returned.'
}
```

### Full official table

Free plan and up. The complete table for the latest publication date.

```js
import { getLatestRates } from 'brcustoms-exchange-rate';

const table = await getLatestRates({ apiKey: 'art_live_...' });
console.log(table.rate_date, table.rates.length);
```

**Response:**

```javascript
{
  bank: 'brcustoms',
  name: 'Brazil customs exchange rate (Siscomex)',
  rate_date: '2026-11-25',
  rates: [
    { "base": "USD", "quote": "BRL", "type": "customs", "value": 5.8573 },
    // … the rest of the official table (157 currencies vs BRL)
  ],
  disclaimer: '…'
}
```

### Table for a date

Paid plans. The official table for any date since 2016 — weekends and holidays return the most recent published date, flagged via `published_on_requested_date`, which is exactly the in-force rate a filing needs.

```js
import { getRatesForDate } from 'brcustoms-exchange-rate';

const day = await getRatesForDate('2026-06-30', { apiKey: 'art_live_...' });
// Optionally narrow to one pair:
const one = await getRatesForDate('2026-06-30', { apiKey: 'art_live_...', source: 'USD', target: 'BRL' });
```

**Response:**

```javascript
{
  bank: 'brcustoms',
  requested_date: '2026-06-30',
  rate_date: '2026-06-30',                // the date actually published
  published_on_requested_date: true,      // false when a weekend/holiday fell back
  rates: [ /* the full table for that date */ ],
  disclaimer: '…'
}
```

### Daily time series

Paid plans. One resolved rate per publication date — ready for charting, revaluation runs, or audit workpapers.

```js
import { getHistory } from 'brcustoms-exchange-rate';

const series = await getHistory(
  { source: 'USD', target: 'BRL', from: '2026-01-01', to: '2026-11-25' },
  { apiKey: 'art_live_...' }
);
```

**Response:**

```javascript
{
  bank: 'brcustoms',
  source: 'USD',
  target: 'BRL',
  from: '2026-01-01',
  to: '2026-11-25',
  count: 152,
  rates: [
    // one entry per publication date
    { date: '2026-11-25', rate: 5.8573, rate_type: 'customs', derived: false, method: 'published' },
    // …
  ],
  disclaimer: '…'
}
```

Pass `{ symbol: 'USD' }` instead of `source`/`target` to get the raw published rows for one currency (all rate types, no pair resolution).

---

## 🗺️ Currencies covered

Brazil customs exchange rate (Siscomex) currently publishes rates covering **157 currencies** against the BRL (as of the latest table):

🇦🇪 `AED` · 🇦🇫 `AFN` · 🇦🇱 `ALL` · 🇦🇲 `AMD` · 🇦🇴 `AOA` · 🇦🇷 `ARS` · 🇦🇺 `AUD` · 🇦🇼 `AWG` · 🇦🇿 `AZN` · 🇧🇧 `BBD` · 🇧🇩 `BDT` · 🇧🇬 `BGN` · 🇧🇭 `BHD` · 🇧🇮 `BIF` · 🇧🇲 `BMD` · 🇧🇳 `BND` · 🇧🇴 `BOB` · 🇧🇸 `BSD` · 🇧🇹 `BTN` · 🇧🇼 `BWP` · 🇧🇾 `BYN` · 🇧🇿 `BZD` · 🇨🇦 `CAD` · 🇨🇩 `CDF` · 🇨🇭 `CHF` · 🇨🇱 `CLF` · 🇨🇱 `CLP` · 🇨🇳 `CNH` · 🇨🇳 `CNY` · 🇨🇴 `COP` · 🇨🇴 `COU` · 🇨🇷 `CRC` · 🇨🇺 `CUP` · 🇨🇻 `CVE` · 🇨🇿 `CZK` · 🇩🇯 `DJF` · 🇩🇰 `DKK` · 🇩🇴 `DOP` · 🇩🇿 `DZD` · 🇪🇬 `EGP` · 🇪🇷 `ERN` · 🇪🇹 `ETB` · 🇪🇺 `EUR` · 🇫🇯 `FJD` · 🇫🇰 `FKP` · 🇬🇧 `GBP` · 🇬🇪 `GEL` · 🇬🇭 `GHS` · 🇬🇮 `GIP` · 🇬🇲 `GMD` · 🇬🇳 `GNF` · 🇬🇹 `GTQ` · 🇬🇾 `GYD` · 🇭🇰 `HKD` · 🇭🇳 `HNL` · 🇭🇹 `HTG` · 🇭🇺 `HUF` · 🇮🇩 `IDR` · 🇮🇱 `ILS` · 🇮🇳 `INR` · 🇮🇶 `IQD` · 🇮🇷 `IRR` · 🇮🇸 `ISK` · 🇯🇲 `JMD` · 🇯🇴 `JOD` · 🇯🇵 `JPY` · 🇰🇪 `KES` · 🇰🇬 `KGS` · 🇰🇭 `KHR` · 🇰🇲 `KMF` · 🇰🇷 `KRW` · 🇰🇼 `KWD` · 🇰🇾 `KYD` · 🇰🇿 `KZT` · 🇱🇦 `LAK` · 🇱🇧 `LBP` · 🇱🇰 `LKR` · 🇱🇷 `LRD` · 🇱🇸 `LSL` · 🇱🇾 `LYD` · 🇲🇦 `MAD` · 🇲🇩 `MDL` · 🇲🇬 `MGA` · 🇲🇰 `MKD` · 🇲🇲 `MMK` · 🇲🇳 `MNT` · 🇲🇴 `MOP` · 🇲🇷 `MRO` · 🇲🇷 `MRU` · 🇲🇺 `MUR` · 🇲🇻 `MVR` · 🇲🇼 `MWK` · 🇲🇽 `MXN` · 🇲🇾 `MYR` · 🇲🇿 `MZN` · 🇳🇦 `NAD` · 🇳🇬 `NGN` · 🇳🇮 `NIO` · 🇳🇴 `NOK` · 🇳🇵 `NPR` · 🇳🇿 `NZD` · 🇴🇲 `OMR` · 🇵🇦 `PAB` · 🇵🇪 `PEN` · 🇵🇬 `PGK` · 🇵🇭 `PHP` · 🇵🇰 `PKR` · 🇵🇱 `PLN` · 🇵🇾 `PYG` · 🇶🇦 `QAR` · 🇷🇴 `RON` · 🇷🇸 `RSD` · 🇷🇺 `RUB` · 🇷🇼 `RWF` · 🇸🇦 `SAR` · 🇸🇧 `SBD` · 🇸🇨 `SCR` · 🇸🇩 `SDG` · `SDR` · 🇸🇪 `SEK` · 🇸🇬 `SGD` · 🇸🇭 `SHP` · 🇸🇱 `SLL` · 🇸🇴 `SOS` · 🇸🇷 `SRD` · 🇸🇸 `SSP` · 🇸🇹 `STN` · 🇸🇻 `SVC` · 🇸🇾 `SYP` · 🇸🇿 `SZL` · 🇹🇭 `THB` · 🇹🇯 `TJS` · 🇹🇲 `TMT` · 🇹🇳 `TND` · 🇹🇴 `TOP` · 🇹🇷 `TRY` · 🇹🇹 `TTD` · 🇹🇼 `TWD` · 🇹🇿 `TZS` · 🇺🇦 `UAH` · 🇺🇬 `UGX` · 🇺🇸 `USD` · 🇺🇾 `UYU` · 🇺🇿 `UZS` · 🇻🇪 `VES` · 🇻🇳 `VND` · 🇻🇺 `VUV` · 🇼🇸 `WST` · `XAF` · `XAU` · `XCD` · `XCG` · `XOF` · `XPF` · 🇾🇪 `YER` · 🇿🇦 `ZAR` · 🇿🇲 `ZMW`

## 🏛️ Source

The exchange rate Brazilian customs (Receita Federal, Siscomex) applies to convert the customs value of imports registered on a DI or DUIMP into reais. Under Article 97 of the Regulamento Aduaneiro it is the rate in force on the date of the taxable event (registration of the declaration); since 10 April 2019 Siscomex uses the Banco Central do Brasil PTAX selling rate at the close of the business day before registration (before that, the same day's). AllRatesToday applies that rule to the official PTAX sell rates, dating each rate the day it applies from, so a lookup for any registration date returns the previous business day's PTAX.

- Publisher's own page: [Regulamento Aduaneiro (Decreto 6.759/2009), Art. 97](https://www.planalto.gov.br/ccivil_03/_ato2007-2010/2009/decreto/d6759.htm) · [www.gov.br/receitafederal](https://www.gov.br/receitafederal/)
- Publication: every business day; the exact schedule, freshness status and any current delay are on the [Brazil customs exchange rate (Siscomex) rates page](https://allratestoday.com/tax-authority-rates-api/brcustoms/)
- Values are stored unmodified, with the publisher's own `rate_date` on every row — see the [methodology](https://allratestoday.com/official-rates-methodology/)

## 🧭 Reading the numbers

- `value` is always **quote currency per 1 unit of base currency** (`base: "EUR", quote: "USD", value: 1.15` means 1 EUR = 1.15 USD).
- Brazil customs exchange rate (Siscomex) quotes **BRL per 1 unit of foreign currency** (e.g. `base: "USD", quote: "BRL"` means BRL per one US dollar).
- Need the other way round? Ask `getRate(target, source)` and the API inverts or crosses for you, flagged `derived: true` — never divide a published rate yourself in a compliance workflow.
- Precious-metal codes (`XAU`, `XAG`, `XPT`, `XPD`) are quoted **per troy ounce**.
- `rate_type` tells you which of the tax authority's series a row belongs to (`customs` here); some publishers print buy/sell or several fixings for the same pair.

## 🧩 ERP & accounting systems

Loading the official Brazil customs exchange rate (Siscomex) rate into an accounting system is a supported workflow, not a hack. Step-by-step guides with the direction each system expects:

- [Dynamics 365 Business Central](https://allratestoday.com/docs/integrations/business-central/) — built-in Currency Exchange Rate Service, no code
- [Xero](https://allratestoday.com/docs/integrations/xero/) · [QuickBooks Online](https://allratestoday.com/docs/integrations/quickbooks/) · [SAP S/4HANA and ECC](https://allratestoday.com/docs/integrations/sap/) · [Odoo](https://allratestoday.com/docs/integrations/odoo/)

The same keyed endpoints return `?format=csv`, `?format=xml` and `?format=xlsx`, and accept the key as `?api_key=` on the URL for importers that cannot send headers:

```bash
curl "https://allratestoday.com/api/v1/central-bank/brcustoms/latest?format=xml&api_key=art_live_..."
```

## 🤖 AI agents

- MCP server: `npx -y @allratestoday/central-bank-mcp` (stdio) or the hosted endpoint `https://allratestoday.com/api/mcp` — tools for official rates, history, cross-bank comparison and publication calendars
- Already using the general SDK or MCP server? Since 2026-10-01 [`@allratestoday/sdk`](https://www.npmjs.com/package/@allratestoday/sdk) 1.4+ has `officialRates('brcustoms')` and [`@allratestoday/mcp-server`](https://www.npmjs.com/package/@allratestoday/mcp-server) 0.6+ has a `get_official_rates` tool — both return this source's latest table with no key, so you can add it without a second dependency
- Claude Code plugin (no key): `/plugin marketplace add AllRates-Today/claude-code-plugin` then `/plugin install allratestoday@allratestoday` — bundles both MCP servers plus an `/official-rate brcustoms ...` command
- Evaluating? Agents can self-issue a trial key with no signup: `POST https://allratestoday.com/api/agent/keys` (send `Content-Type: application/json`) returns a 100-call key valid 7 days that covers the free-plan methods (latest table, pairs); dated tables and history need a [paid plan](https://allratestoday.com/pricing/). The MCP servers expose it as `request_trial_key`
- Machine-readable site guide: [llms.txt](https://allratestoday.com/llms.txt) · [for-ai-agents](https://allratestoday.com/for-ai-agents/)

## ⚖️ Official vs derived rates

If Brazil customs exchange rate (Siscomex) does not print a pair directly, the API resolves it from the tax authority's own table and says so — official and computed values are never confused:

| `method` | `derived` | Meaning |
| --- | --- | --- |
| `published` | `false` | The tax authority printed this pair directly |
| `inverse` | `true` | Computed as 1 ÷ the published opposite direction |
| `cross` | `true` | Computed via BRL from two published rates |

## 🛡️ Error handling

Errors are thrown as `Error` with `status` (HTTP code) and `body` (the API's JSON error) attached:

```js
try {
  const pair = await getRate('USD', 'XXX', { apiKey: 'art_live_...' });
} catch (err) {
  console.log(err.message); // human-readable reason
  console.log(err.status);  // e.g. 404
}
```

| Status | Meaning |
| ------ | ------- |
| — | Missing `apiKey` (thrown before any request) |
| `400` | Malformed date or parameters |
| `401` | Invalid API key |
| `403` | Endpoint needs a [paid plan](https://allratestoday.com/pricing/) (historical dates & series) |
| `404` | Pair or date range not covered by Brazil customs exchange rate (Siscomex) |
| `429` | Monthly quota exceeded |

## 🔷 TypeScript

Full definitions ship with the package — no `@types` install:

```ts
import type { LatestRates, PairRate, DatedRates, RateEntry, HistoryQuery, RequestOptions } from 'brcustoms-exchange-rate';
```

## 📦 CommonJS

```javascript
const { getRate } = require('brcustoms-exchange-rate');

getRate('USD', 'BRL', { apiKey: 'art_live_...' }).then((pair) => console.log(pair.rate));
```

## 💡 Quota tips

- Rates change once per business day — cache the official table locally and a small monthly quota goes a long way.
- Every request counts toward your AllRatesToday quota, shared across all AllRatesToday endpoints on your key.

## 📖 Methods reference

| Method | Plan | Description |
| ------ | ---- | ----------- |
| `getRate(source, target, { apiKey })` | Free | Latest rate for one pair, resolved from the official table |
| `getLatestRates({ apiKey })` | Free | The tax authority's full latest official table |
| `getRatesForDate(date, { apiKey, source?, target? })` | Paid | The official table (or one pair) for a YYYY-MM-DD date |
| `getHistory({ symbol \| source+target, from?, to? }, { apiKey })` | Paid | Daily series since 2016 |

## 📥 Bulk data (no key)

Need the whole archive rather than an API call? The same official tables are mirrored daily as open data:

- Hugging Face: [AllRatesToday/central-bank-exchange-rates](https://huggingface.co/datasets/AllRatesToday/central-bank-exchange-rates) — one CSV per institution (`rates/brcustoms.csv`)
- Kaggle: [allratestoday/central-bank-exchange-rates](https://www.kaggle.com/datasets/allratestoday/central-bank-exchange-rates)
- Raw JSON on GitHub: `https://raw.githubusercontent.com/AllRates-Today/central-bank-exchange-rates/main/data/brcustoms/latest.json`

## 🔗 Links

- **Website:** [allratestoday.com](https://allratestoday.com)
- [Brazil customs exchange rate (Siscomex) rates page](https://allratestoday.com/tax-authority-rates-api/brcustoms/) — live table, publication cadence, FAQ
- [All tax authority sources](https://allratestoday.com/tax-authority-rates-api/) · [Full list of 120+ central banks and 50+ tax authorities](https://allratestoday.com/central-bank-rates-api/institutions/) — one API, the same response shape for every source
- [Download central bank rates](https://allratestoday.com/download-central-bank-rates/) — every bank's latest table and history as Excel, CSV or JSON
- [Bank Exchange Rate API](https://allratestoday.com/bank-exchange-rate-api/) — live buy and sell rates from 1,200+ commercial banks in 120+ countries · [npm](https://www.npmjs.com/package/bank-exchange-rates) · [GitHub](https://github.com/AllRates-Today/bank-exchange-rates)
- [Package docs on the site](https://allratestoday.com/docs/sdk/brcustoms-exchange-rate/) · [ERP integration guides](https://allratestoday.com/docs/integrations/)
- [API documentation](https://allratestoday.com/docs/#central-bank) · [Interactive reference](https://allratestoday.com/api-reference/) · [Methodology](https://allratestoday.com/official-rates-methodology/)
- [Register (Free)](https://allratestoday.com/register) · [Dashboard](https://allratestoday.com/profile) · [Pricing](https://allratestoday.com/pricing/)
- [Status](https://allratestoday.com/status)
- [Postman collection](https://allratestoday.com/postman/)
- [ChatGPT app](https://chatgpt.com/plugins/plugin_asdk_app_6ae1e76098f48191a285ac3f5ab7a83b) — ask ChatGPT for live and official central bank rates
- [OpenAPI reference on Bump.sh](https://bump.sh/allratestoday/doc/allratestoday-api) — also on [SwaggerHub](https://app.swaggerhub.com/apis-docs/allratestoday/allratestoday-exchange-rate-central-bank-rates-api/2.2.0)
- [GitHub](https://github.com/AllRates-Today/brcustoms-exchange-rate)

## 📜 License

MIT
