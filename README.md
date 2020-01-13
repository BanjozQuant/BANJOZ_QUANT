# Main

This project is for automated unsupervised algorithm trading.

There are a few key elements 

1 - BROKER ===  The broker i use is interactive brokers. This is important as it's the API that i use. Having said that, the IB API stuff is confined to it's own module, so it could be easily overloaded.

2 - GUI === The GUI framework i have chosen is WXWidgets. It should port to various OS's, MAC, Linux. I use windows so it would be good if others could help out here.

In terms of modules ... 

1 - Historian == This Saves public Market data, including dividends etc.

2 - Accountant == This will save PRIVATE data, trades, transactions

3 - IBGController == controls requests and data to and from IB. Can also place trades.

==========================================================================

BEYOND ===

Looking forward, i am going to dabble in AI. Hence the framework up front to allow unsupervised learning. Any suggestions would be welcome.

