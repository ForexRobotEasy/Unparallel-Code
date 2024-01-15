# Unparallel Code

This is the readme file for the code of Unparallel Code.mq5, an advanced forex software developed by the Forex Robot Easy Team. 

## Product Description

Unparallel Code is a sophisticated forex trading software designed to analyze the forex market using 97 different indicators. It implements a complex array of conditions based on these indicators to determine the optimal time to enter a trading position. The software also includes features such as stop loss and take profit management.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/unparallel-code-review-advanced-forex-software-with-97-market-indicators/). Please note that ForexRobotEasy is not the official developer of this product. We only provide a sample code that demonstrates the functionality described in the product. To find the official developer of this product, please refer to MQL5.

## Usage

To use the Unparallel Code software, follow these steps:

1. Define the global variables:
   - `StopLossFirst`: The stop loss value for the first position.
   - `StopLossRest`: The stop loss value for the rest of the positions.
   - `TakeProfit1`: The take profit value for strategy 1.
   - `TakeProfit2`: The take profit value for strategy 2.

2. Implement the necessary initialization in the `OnInit()` function.

3. Implement the necessary cleanup and data saving in the `OnDeinit()` function.

4. Implement the main trading logic in the `OnTick()` function.

5. Implement the logic to check all 97 conditions in the `CheckAllConditions()` function.

6. Implement the logic to open a new trading position in the `OpenPosition()` function.

7. Implement the logic to calculate the minimum distance between trades based on candles in the `CalculateMinDistance()` function.

8. Implement the logic to set the stop loss values for the first position and the rest in the `SetStopLoss()` function.

9. Implement the logic to set the take profit values based on the selected strategy in the `SetTakeProfit()` function.

10. Implement the logic to continue trading after the stop loss is hit in the `ContinueTrading()` function.

## Disclaimer

Please note that ForexRobotEasy is not the official developer of the Unparallel Code software. We only provide a sample code that demonstrates the functionality described in the product. To find the official developer of this product, please refer to MQL5.
