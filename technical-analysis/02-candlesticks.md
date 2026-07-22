# Japanese Candlesticks

## Definition

**Japanese candlesticks** are charting tools used to display price movement over a specific period.

Each candlestick represents four key prices: **Open, High, Low, and Close (OHLC).**

## Structure

```text
      [ Bullish ]             [ Bearish ]
    (Price Went UP)        (Price Went DOWN)

         High                    High
          │                       │
      ┌───┴───┐               ┌───┴───┐
      │ Close │               │ Open  │
      │       │               │       │
      │ Body  │               │ Body  │
      │       │               │       │
      │ Open  │               │ Close │
      └───┬───┘               └───┬───┘
          │                       │
         Low                     Low
```

* **Body:** The block showing the distance between the **Open** and **Close** prices.
* **Wicks (Shadows):** The lines showing the **High** and **Low** prices reached during the period.

## Types

### Bullish Candlestick

* **Formula:** Close > Open
* **Meaning:** Price moved up; buyers were in control.

### Bearish Candlestick

* **Formula:** Close < Open
* **Meaning:** Price moved down; sellers were in control.

## Key Points

* Each candlestick represents a specific timeframe (e.g., 5m, 1H, 4H, 1D).
* A longer body indicates stronger market momentum.
* Longer wicks indicate price rejection at those levels.

## Summary

Japanese candlesticks display **OHLC** data to help traders understand price movement and market sentiment during a specific timeframe.
