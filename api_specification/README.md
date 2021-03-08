### The endpoint
```js
shortcode = "DIGITMATCH_R_10_18.18_1613451832_5T_7_0"
currency  = "USD"

// endpoint:
`GET /v1/DIGITS/${currency}/${shortcode}`
```

- The api starts with `/v1/<contract-category>/`, each category will have its own interface.
- The only required parameters for `DIGITS` are `shortcode` + `currency`.
- We have explicitly decided not to support **back pricing** in this endpoint.
- A future endpoint will have an extra `date_pricing` parameter, to support back pricing.
