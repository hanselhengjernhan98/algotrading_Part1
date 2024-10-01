Hey! 

Check out my contratian trading strategy - which tests if the market has indeed overracted for the worst and best performing stocks. I have personally made money from executing such trades in the past, whenever say Elon Musk says something controversial (which causes the TSLA share prices to tank), or when Apple launches a new product! 

Therefore, I figured I should first code a trading bot, which shorts the 3 worst performing stocks in the Dow Jones Index, and longs the 3 best performing ones. 

<img width="749" alt="image" src="https://github.com/user-attachments/assets/6e7dcb99-00a2-4ca7-b09d-060cc30be6fa">

'position_t' represents the target trades, or the needed portfolio of the 3 worst and 3 best performing stocks for the day. 'position_a' on the other hand represents the previous day's portfolio. Therefore, if there is an overlap, where the previous day's portfolio includes part of the target trades for the day, we will not need to trade as we already have the desired position. The 'trades' column therefore automatically instructs us which position to take, if any.



<img width="879" alt="image" src="https://github.com/user-attachments/assets/2b019548-ecd5-4dd5-832c-c5492e07c2f2">


As can be seen, it will notify you of the price in which the stock was purchased/shorted, when successful. 

Please view the file for the full code. I intend to do a part 2 real soon, where I backtest this model!
