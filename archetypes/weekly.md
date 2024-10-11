---
type: weekly
layout: weekly

date: "{{ .Date }}"
issuenumber: {{ len (readDir "content/weekly") }}
title: "Issue {{ len (readDir "content/weekly") }}: {{ dateFormat "January 02" .Date }} - {{ dateFormat "02, 2006" ((.Date | time.AsTime).AddDate 0 0 7) }}"
---

### Table of Contents:

- [Recent News](#news)
- [Upcoming Events](#events)
- [CCS Proposals](#proposals)
- [Price & Blockchain Stats](#stats)
- [Volunteer Opportunities](#volunteer)
- [Support](#support)

### Recent News {#news}

{{% newsbyte %}}
Haveno DEX [v1.0.8](https://github.com/haveno-dex/haveno/releases/tag/1.0.8) adding scripts to run Haveno on Tails OS; miscellaneous translations; general enhancements and a few bug fixes. Haveno Reto [v1.0.8](https://github.com/retoaccess1/haveno-reto/releases/tag/v1.0.8).
{{% /newsbyte %}}

### Upcoming Events {#events}

{{% event "July 1, 2024 (Monday) - 18:00 UTC" %}}
Seraphis Wallet Workgroup Meeting - [#no-wallet-left-behind](irc://irc.libera.chat/#no-wallet-left-behind) IRC channel; Matrix [room](https://matrix.to/#/#no-wallet-left-behind:monero.social).
{{% /event %}}

### CCS Proposal Ideas {#proposals}

Below you can find some CCS proposal ideas open for discussion.

{{% ccs_item link="jeffro256-full-time-2024Q3" author="jeffro256" %}}
full-time development 2024Q3
{{% /ccs_item %}}

### CCS Proposals Need Funding

{{% ccs_item link="jeffro256-full-time-2024Q3" author="jeffro256" goal=146 raised=30.04 %}}
full-time development 2024Q3
{{% /ccs_item %}}

### Price & Blockchain Stats {#stats}

###### Blockchain Stats

{{< bc_stats
	height="0"
	hashrate="0 GH/s"
	txs_per_block="0"
	avg_txs_per_day="0"
	block_reward="0.6"

	date="January 1, 2024"
>}}

###### XMR Blocks Distribution in last 1000 blocks

![Hashrate Pool Distribution Pie Chart](./hash.png)

###### Price & Performance

{{< price_performance
	market_cap="3,209,863,981"
	street_price="190.07"

	table_date="06/13/24"
	price_usd="173.67,+5.4,+29.9,+24.7"
	price_eur="160.61,+6.8,+30.9,+25.4"
	price_btc="0.00258,+12.4,+19.8,-51.9"

	date="June 6, 2024"
>}}

###### XMR Price Graph

![XMR Price Graph](./price.png)

Sources: [miningpoolstats.stream](https://miningpoolstats.stream/monero); [bitinfocharts.com](https://bitinfocharts.com/monero/); [coingecko.com](https://www.coingecko.com/en/coins/monero); [localmonero.co blocks](https://localmonero.co/blocks); [haveno.markets](https://haveno.markets/).

{{< volunteer >}}
{{% volunteer_item title="Test Monero Core Software" link="https://github.com/monero-project/monero" %}}
Anyone with moderate technical ability is encouraged to try to build and run Monero nightlies. Do not trust it with your Monero, but feel free to open an Issue on GitHub as problems arise. Instructions to build on your OS of choice can be found [here](https://github.com/monero-project/monero#compiling-monero-from-source). 
{{% /volunteer_item %}}
{{< /volunteer >}}

{{< support />}}
