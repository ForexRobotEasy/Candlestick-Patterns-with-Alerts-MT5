# Candlestick Patterns with Alerts MT5

This code is a custom indicator for MetaTrader 5 (MT5) that detects and alerts the user to various candlestick patterns. It can be used to identify potential bullish and bearish formations in the market.

## Input Parameters

The indicator allows the user to define the colors for bullish and bearish formations. The default colors are green for bullish formations and red for bearish formations. These colors can be customized to suit the user's preferences.

## How it Works

The indicator uses a series of functions to check for different candlestick patterns in the market. These patterns include bullish breakout formations, bearish breakout formations, hammers, pins, bullish engulfing formations, and bearish engulfing formations.

For each candlestick pattern detected, the indicator displays an arrow object on the chart. A bullish formation is indicated by a green arrow at the low of the candle, while a bearish formation is indicated by a red arrow at the high of the candle.

## Function Descriptions

- `OnInit()`: This function is called during the indicator initialization process. It creates arrow objects for bullish and bearish formations and sets their properties, such as color and arrow code.

- `OnCalculate()`: This function is called for each new tick in the market. It checks for different candlestick patterns and calls the corresponding display functions to show the formations on the chart.

- `IsBullBreakout()`, `IsBearBreakout()`, `IsHammer()`, `IsPin()`, `IsBullishEngulfing()`, `IsBearishEngulfing()`: These functions are used to check for specific candlestick patterns. The user can add their own code to these functions to customize the pattern detection logic.

- `DisplayBullishFormation()`, `DisplayBearishFormation()`: These functions are called when a bullish or bearish formation is detected. They create arrow objects on the chart at the appropriate price level.

## Product Description

This code is a sample implementation of a custom indicator for MetaTrader 5 that detects and alerts the user to various candlestick patterns. It can be used to identify potential bullish and bearish formations in the market.

Please note that Forex Robot Easy is not the official developer of this product. We only provide a sample code that demonstrates how the indicator can work. To find the official developer of this product, please refer to the MQL5 website.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy's review of Candlestick Patterns MT5](https://forexroboteasy.com/forex-robot-review/candlestick-patterns-mt5-unbiased-review-of-forex-alert-software/).

For more information and assistance with using this indicator, please visit [Forex Robot Easy](https://forexroboteasy.com).
