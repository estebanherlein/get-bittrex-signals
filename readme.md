# Get trade signals

### Usage: 
gettradesignals.py [OPTIONS] INTERVAL BASE MINVOLUME

  Command line interface for a small routine that requests information from the bittrex API and uses
  Ichimoku kinko hyo to generate trend signals for each market that are dumped to a JSON
  file

### Arguments:
  :param interval: The candlestick interval [“oneMin”, “fiveMin”,
  “thirtyMin”, “hour”, “day”]

  :param base: The base currency of the market pair [BTC, ETH, USD or USDT]

  :param minvolume: Minimum 24h volume in base currency units

### Options:
  --help  Show this message and exit.
