# Swing Sniper

## About
Swing Sniper is a custom indicator developed by Forex Robot Easy Team. This indicator enhances forex trading by providing adjustable indicators for determining trend direction and swing points. It can be used in MetaTrader 4 platform.

For detailed reviews and trading results of this product, visit [Forex Robot Easy - Swing Sniper Review](https://forexroboteasy.com/forex-robot-review/swing-sniper-review-enhance-forex-trading-with-adjustable-indicators/).

Please note that Forex Robot Easy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, use MQL5.

## Global Variables
- `lookBackPeriod`: Default look back period for moving average (default: 10)
- `multiplier`: Default multiplier for swing in point (default: 1.5)
- `channelShift`: Default channel shift value (default: 20)

## Custom Indicator Initialization Function
- `OnInit()`: This function is called when the indicator is initialized. It sets the chart properties, creates indicator buffers, sets indicator colors, and sets chart colors.

## Custom Indicator Iteration Function
- `OnCalculate()`: This function is called for each bar to calculate the moving average, determine the trend direction, calculate the swing in point, adjust the channel shift value, and modify adjustable indicators during testing or optimization. It also sets visual cues for downtrend and uptrend.

## Usage
1. Install the Swing Sniper custom indicator in MetaTrader 4 platform.
2. Apply the Swing Sniper indicator to the desired chart.
3. Adjust the global variables (`lookBackPeriod`, `multiplier`, `channelShift`) as per your trading preferences.
4. Monitor the chart for visual cues and use the adjustable indicators to make trading decisions.

Please note that the effectiveness of this indicator may vary depending on market conditions and individual trading strategies. It is recommended to thoroughly backtest and optimize the adjustable indicators before using them in live trading.

For more information and support, visit [Forex Robot Easy](https://forexroboteasy.com/).
