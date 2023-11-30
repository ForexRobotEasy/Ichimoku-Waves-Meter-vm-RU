# Ichimoku Waves Meter vm RU

This is a custom indicator called 'Ichimoku Waves Meter vm RU' developed by Forex Robot Easy Team. It is used for calculating waves based on high and low prices in the Forex market. The indicator is designed to provide a visual representation of the waves and their strength in the market.

## External Parameters

- WavesPeriod: This parameter determines the period for calculating the waves. The default value is set to 26.
- PriceScale: This parameter is used as a scale factor for the price waves. The default value is set to 1.0.

## Global Variables

- WavesData: This is an array that stores the calculated wave values.

## Indicator Initialization

The OnInit() function is called during the indicator initialization process. In this function, the indicator buffers are mapped and the indicator properties are set. The short name of the indicator is set as 'Ichimoku Waves Meter vm RU'. The display levels are set to 2 digits. The indicator label is set based on the WavesPeriod parameter.

## Indicator Calculation

The OnCalculate() function is called for each new tick to calculate the waves. It checks if the calculation is being done for the first time, and if so, it initializes the WavesData buffer with 0 values.

The waves are then calculated using the high and low prices for each bar. The wave value is calculated by summing the differences between high and low prices for the previous WavesPeriod bars, multiplied by the PriceScale factor.

Finally, the calculated wave values are stored in the WavesData buffer.

## Product Description

The 'Ichimoku Waves Meter vm RU' is a custom indicator developed by Forex Robot Easy Team. It is designed to provide traders with a visual representation of the waves in the Forex market and their strength.

This indicator calculates the waves based on the high and low prices of the market. The WavesPeriod parameter determines the period for calculating the waves. The PriceScale parameter is used as a scale factor for the price waves.

The indicator displays the calculated waves on the chart, allowing traders to identify the strength and direction of the waves in the market. This information can be used to make more informed trading decisions.

Please note that Forex Robot Easy is not the official developer of this product. We are providing this sample code for educational purposes only. To find the official developer of this product and for detailed reviews and trading results, please visit [Forex Robot Easy - Ichimoku Waves Meter Review](https://forexroboteasy.com/forex-robot-review/ichimoku-waves-meter-review-swift-forex-analysis-tool/).
