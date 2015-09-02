
## Participants

### Data Provider

The smallest instance of a data provider is an individual sensor. But take smartphone as data provider. 

Smartphone properties

* Fluctuating Internet connectivity, limited bandwidth
* Runs on battery
* Limited storage capacity

Suitable for providing real-time sensor data


### Data Requester


## Selling the data

### Traditional payment systems

* Privacy problems
* Transaction costs

### Bitcoin

On-chain transactions to expensive

-> Payment channels

Requester locks some funds in a multisignature output that needs the requester's and the provider's signature to redeem. A transaction redeeming this output by sharing it between the requester and the provider gets updated everytime data is exchanged and is broadcasted to the Bitcoin network after the exchange is completed. Hence, for repeated buying of data form a single provider only two transactions have to be broadcasted to the Bitcoin network. Although there might have happened hundreds or thousands individual exchanges. 

Problem: Need to establish payment channels between each requester and each provider (scales with n*m). This locks a lot of bitcoins in funding transactions for payment channels

--> Hub and spoke payment channels

Idea: Every requester establishes a payment channel with a hub and the hub establishes payment channels with each provider. 

## Personal Data Markets
https://datacoup.com
http://www.handshake.uk.com/

## Data Markets

* General:
  * http://datamarket.azure.com/

* Financial:
  * http://www.xignite.com/

* Marketing:
  * http://exelate.com/
  * Oracle Data as a Service

* Places:
  * Factual

http://thenextweb.com/insider/2013/09/17/whats-the-true-value-of-your-personal-data-meet-the-people-who-want-to-help-you-sell-it/

## Privacy

* People don't know how to value their privacy 



## Related Work

* [Krontiris, I., & Dimitriou, T. (2015). A platform for privacy protection of data requesters and data providers in mobile sensing. Computer Communications.](http://www.sciencedirect.com/science/article/pii/S0140366415000560)
  ** Quadtree structure as location data indexing method
