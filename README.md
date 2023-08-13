Hey, welcome to 
# frznprograms
(read Frozone programs) 

I'm an aspiring Data Scientist/Algorithmic Trader from NUS. I just started on my journey exploring the vast world of Data Science and Quantitative Finance. So far, it's been pretty cool. 

You can find some of my projects here, on the code I wrote for internship last summer, some self-initiated projects I've worked on and some Algorithmic Trading. Please note that I have removed some of the details and comments from the code I wrote during my internship to maintain the confidentiality of the data that was given to me. 

The algorithms are quite basic in Finance terms, meaning they don't quite consider as many indicators and metrics as a trader would, but it's a work in progress. 

Here's a brief summary of the algorithms here: 
1. ADAM - basic long position algorithm that opens long positions and tracks a trailing stop loss, with target profit at 1.5 times the entry price
2. ANDROMEDA - built upon ADAM, this algorithm considers a 'Universe' of securities, which is created by identifying securities that perform well by dollar volume, PE ratio, etc. This Universe is adaptable and will change to rebalance the portfolio to include only the best performers.
3. MACCADACCA - a new algorithm which considers candlestick patters and the MACD indicator. It analyses the shape of the candlesticks and the general market signals to open both long and short positions.

All these algorithms are built using the LEAN Engine on QuantConnect. 

Have fun perusing! I hope my projects can offer you some inspiration, ideas or maybe even spark your interest in my chosen fields (if you're not already down the rabbit hole like I am). If you want to contact me, you can always find me here: www.linkedin.com/in/shane-bharathan


