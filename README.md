# TopFlight
Profit Trailer Settings for use with TopFlight Algorithm 

# What is TopFlight?
Top flight is a small program that sits in your Profit Trailer main directory that analyises all altcoin movements within the exchange to find the best coin at the moment to purchase. A maxminum of 4 cryptocurrencies at any given time are presented to Profit Trailer to purchase. This is accomplished by putting Profit Trailer into Sell Only Mode (SOM) and then excluding SOM for these coins/tokens.

# How does TopFlight Work?
TopFlight independantly anaylises the movement of all cryptocurrencies within the exchange and simply looks for the following criteria:
- High volitility movement within a coin or token
- Upward trending of that specific coin or token

When these conditions are met, they are presented to Profit Trailer to purchase (by adding a line at the bottom of PAIRS.Properties to turn sell only off (= false) for that specific coin). Profit Trailer then buys and sells the coin according to it's configured settings.

# Why does Profit Trailer need to be in Sell Only Mode (SOM)
The single purpose of the TopFlight algorithm is to present Profit Trailer with a maximun of 3 coins or tokens (at that point in time, from all coins or tokens traded on the exchange) to choose to purchase from.  

# Questions?
Specific questions can be sent to: ptsettings.club@gmail.com
