# Supertrend-Strategy-PineScript

**Description**

A modified version of Leo Smigel's TradingView Pine Script, which defines a Supertrend trading strategy with additional filters for entry and exit signals. The code calculates the Supertrend indicator using user-defined parameters, and uses it to trigger long entry signals when the Supertrend direction changes to negative and other conditions are met. The code also includes the ADX and RSI indicators as additional filters for the long entry signals. When the Supertrend direction changes to positive, it closes the long position.

**The Supertrend Indicator**

The Supertrend indicator is a trend-following indicator that helps traders identify the current market trend and potential entry and exit points. It is calculated using the Average True Range (ATR) indicator, which measures the volatility of an asset, and a factor that determines the sensitivity of the Supertrend to changes in price. The ATR indicator is calculated using the standard deviation of the ATR indicator, which measures the volatility of an asset.

**The ADX Indicator**

The ADX indicator measures the strength of a trend, regardless of its direction. It ranges from 0 to 100, with higher values indicating a stronger trend. The ADX is calculated by taking the difference between the positive directional movement (+DM) and negative directional movement (-DM) and smoothing the result using an exponential moving average. A rising ADX indicates that the trend is gaining strength, while a falling ADX suggests that the trend is losing momentum.

**The RSI Indicator**

The RSI indicator measures the strength of an asset's price action by comparing the average gains and losses over a specific period. It ranges from 0 to 100, with values above 70 indicating that the asset is overbought and values below 30 indicating that the asset is oversold. The RSI is calculated by dividing the average gain over a specified period by the average loss over the same period and converting the result into an oscillator that ranges from 0 to 100.
