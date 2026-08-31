# CRYPTO EXCHANGE

## 1. Overview

The cryptocurrency exchange is a platform that allows users to hold digital assets and trade them against other assets.

Users can create accounts, manage their assets (BTC, ETH, USDT, EUR), place buy and sell orders, execute trades, and view their trading activity.

User A  
BTC:  0.50  
USDT: 10,000$  

User B  
BTC:  1.20  
USDT:  3,500$  

The exchange supports multiple trading pairs, such as BTC/USDT, ETH/USDT, and BTC/EUR.

A user can place an order specifying the trading pair, side, price, and quantity. The system processes the order and, when a compatible opposite order exists, executes a trade between the users.

Order - Buyer

Type:     LIMIT  
Side:     BUY  
Pair:     BTC/USDT  
Price:    100,000 USDT  
Quantity: 0.5 BTC  

Notice: If the offer user want to make doesn't exist, offer is being pushed to the waiting line until the one of the users make selling offer

Order - Seller

Type:     LIMIT  
Side:     SELL  
Pair:     BTC/USDT  
Price:    100,000 USDT  
Quantity: 0.5 BTC  

Results of the exchange 
------------------------

Buyer
- 50,000 USDT
+ 0.5 BTC

Seller
- 0.5 BTC
+ 50,000 USDT

The system is responsible for maintaining accurate user balances, processing orders correctly, and keeping a reliable record of trading activity.

## 2. Main components  

- Frontend
- API Gateaway 
- Authentication Service
- User Service 
- Wallet Service 
- Trading Service
- Matching Engine
- Order Book
- Ledger 
- Block chain integration 
- Database
- Massege Queue

## 3. One order flow

- **USER**
- **ORDER**
- **TRADING SERVICE**
- **CHECK BALANCE**
- **RESERVE FUNDS**
- **MATCHING ENGINE**
- **ORDER MATHCED**
- **TRADE EXECUTED**
- **LEDGER UPDATED**
- **BALANCES UPDATED**
- **USER RECEIVES HIS RESULTS**