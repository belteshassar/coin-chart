# coin-chart

Chart the coins of the world using d3.js

## Adding coins

Adding a new coin is relatively straightforward for common currencies; just follow these steps:

1. Check that the currency is included in the 32 currencies that the [ECB posts reference rates](https://www.ecb.europa.eu/stats/policy_and_exchange_rates/euro_reference_exchange_rates/html/index.en.html) for.
2. Add a row for the coin in the file `coin_data.csv`.
3. Add a png image of the coin with a transparent background to the `gfx/` directory.
