+++
title = "Finding Historic Yugioh Data is Impossible "
author = "Philipp B."
date = 2025-08-14T23:50:13+02:00
draft = true
+++

# Attempt 1

My first attempt started with lots of Google and Perplexity searches. Both of which eventually led to a Kaggle data set that only included one current price, or one single API. Lucky enough, the API had some documentation and included price history for a given card. However, it turned out to be too good to be true and I had to realise that my first GET request did not return a JSON object including a nice time series of historic prices but instead has been highjacked by a Thai online casino.

{{< figure
  src="/Screenshot 2025-08-14.png"
  alt="A screenshot of the casino scam"
  caption="A screenshot the hijacked API endpoint / Scam alert!"
  class="ma0 w-75"
>}}