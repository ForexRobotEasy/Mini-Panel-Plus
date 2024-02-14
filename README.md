# Mini Panel Plus ReadMe File

This ReadMe file provides information about the Mini Panel Plus code, developed by Forex Robot Easy Team. For detailed reviews and trading results of this product, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/mini-panel-plus-review-enhanced-forex-software-for-strategic-trading/).

## Description

The Mini Panel Plus is a trading panel that allows users to execute trades and manage positions in the MetaTrader 5 platform. The panel provides various features such as opening orders, setting stop loss and take profit levels, trailing stop, and breakeven functionality.

### Panel Parameters

1. `Lot`: Number of contracts to be traded.
2. `Gain`: Stop gain position. Set to 0 to exclude.
3. `Loss`: Stop loss position. Set to 0 to exclude.
4. `TS`: Trailing stop position.

### Functions

The Mini Panel Plus provides the following functions:

1. `OpenOrder(double price)`: Opens an order at the specified price.
2. `CloseOrder()`: Closes an open order.
3. `SetStopLoss(double price)`: Sets the stop loss level at the specified price.
4. `SetStopGain(double price)`: Sets the stop gain level at the specified price.
5. `SetTrailingStop(double price)`: Sets the trailing stop level at the specified price.
6. `SetBreakeven()`: Sets the breakeven level.

### Usage

1. Initialize the panel by calling the `OnInit()` function.
2. Handle tick events using the `OnTick()` function.
3. Customize the trading conditions and actions within the `OnTick()` function.
4. Clean up and deinitialize the panel using the `OnDeinit()` function.

### Note

Forex Robot Easy is not the official developer of this product. This ReadMe file only provides the sample code that can work as described in the Mini Panel Plus. To find the official developer of this product, please refer to the MQL5 platform.

For more information and detailed reviews of this product, please visit the [Forex Robot Easy website](https://forexroboteasy.com/forex-robot-review/mini-panel-plus-review-enhanced-forex-software-for-strategic-trading/).
