# FRB Support and Resistance

This code is a custom indicator for MetaTrader 4 that calculates and visualizes support and resistance zones based on critical points. It allows users to select the desired timeframe and customize the line colors and thickness for support and resistance zones.

## How it Works

### Initialization Function
The `OnInit()` function is called when the indicator is initialized. In this function, the support and resistance zones are calculated based on critical points (not shown in the code). Then, the `DrawSupportResistanceZones()` function is called to visualize these zones.

### Iteration Function
The `OnCalculate()` function is called for each new tick or bar. In this function, calculations are performed to determine the support and resistance zones (not shown in the code). The function returns the total number of calculated rates.

### Draw Support and Resistance Zones
The `DrawSupportResistanceZones()` function is responsible for drawing the support and resistance lines on the chart. It creates objects of type 'trendline' using the `ObjectCreate()` function and sets their properties such as color and thickness using the `ObjectSet()` function.

## Product Description

FRB Support and Resistance is a custom indicator for MetaTrader 4 that helps traders identify key support and resistance zones in the market. These zones can be crucial in determining potential levels of buying or selling pressure, making them valuable areas to consider for entry or exit points.

This indicator allows users to select their desired timeframe, customize the line colors and thickness for support and resistance zones, and visualize these zones directly on the chart.

To use FRB Support and Resistance, simply add it to your MetaTrader 4 platform and apply it to the desired chart. The indicator will automatically calculate and display the support and resistance zones based on critical points.

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer and access detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/frb-support-resistance-unbiased-review-on-forex-software/).
