# Pronokthal EA ReadMe File

This ReadMe file provides a brief overview of the Pronokthal EA code. The Pronokthal EA is an expert advisor developed by the Forex Robot Easy team. Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/pronokthal-ea-review-optimal-forex-software-for-all-currencies/).

## Code Description

The Pronokthal EA is an automated trading system designed to trade on the MetaTrader 5 platform. The code is written in MQL5 language and can be used to trade multiple currency pairs. The EA follows a simple trading strategy based on predefined inputs and market conditions.

### Global Variables

The code begins by declaring global variables that can be adjusted by the user. These variables include:

- `FundSize`: The recommended fund size for trading.
- `Timeframe`: The default timeframe for trading.
- `OrderType`: The default order type (BUY or SELL).
- `Leverage`: The default leverage for trading.
- `Slippage`: The default slippage in points.
- `StopLoss`: The default stop loss in points.
- `TakeProfit`: The default take profit in points.

### Expert Advisor Initialization

The `OnInit()` function is called during the initialization of the expert advisor. It sets the optimization criterion, disables stop levels, and sets the slippage for order execution.

### Expert Advisor Start

The `OnTick()` function is called on every tick of the selected currency pairs. It checks if there is enough funds to trade and then loops through all the currency pairs. For each currency pair, it checks if the symbol is allowed for trading, if the market is open, and sets the leverage for the symbol. If there is an open position, it closes it. If not, it calculates the lot size based on the fund size and opens a new position using the predefined order type, lot size, stop loss, and take profit levels.

### Check if Symbol is Allowed for Trading

The `IsAllowedSymbol()` function checks if the symbol is allowed for trading. It uses a custom symbol blacklist to exclude specific symbols from trading. The blacklist can be modified by adding or removing symbols as needed.

### Expert Advisor Deinitialization

The `OnDeinit()` function is called during the deinitialization of the expert advisor. It cleans up any resources used by the expert advisor.

## Product Description

The Pronokthal EA is an optimal forex software developed by the Forex Robot Easy team. It is designed to automate trading on the MetaTrader 5 platform, allowing traders to trade multiple currency pairs with ease. The EA follows a simple yet effective trading strategy based on predefined inputs and market conditions.

Key Features:

- Automated trading system
- Compatible with MetaTrader 5 platform
- Supports multiple currency pairs
- Adjustable parameters for customization
- Recommended fund size for optimal performance

Please note that ForexRobotEasy is not the official developer of this product. We are only providing a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/pronokthal-ea-review-optimal-forex-software-for-all-currencies/).
