# Main

This project is for automated unsupervised algorithm trading. It is written primarily in C/c++.

Here are a few pre requisites

1 - BROKER ===  The broker i use is interactive brokers. This is important as it's the API that i use. Having said that, the IB API stuff is confined to it's own module, so it could be easily overloaded to support other vendors API's.

2 - GUI === The GUI framework i have chosen is WXWidgets. It should port to various OS's, MAC, Linux with minimal fuss. I use windows so it would be good if others could help out here.

3 - BOOST === Boost has recently been eliminated from the project.

In terms of modules ... 

1 - Historian == This Saves public Market data, including dividends etc.

2 - Accountant == This will save PRIVATE data, trades, transactions

3 - IBGController == controls requests and data to and from IB. Can also place trades.

==========================================================================

BEYOND ===

Looking forward, i am going to dabble in AI. Hence the framework up front to allow unsupervised learning. Any suggestions would be welcome.

