* Transaction fees (absolute/relative) in Bitcoin and $
* Classify output/input scripts + their value + time until they get spent
	* Micropayment channels
	* Multi-sig
	* Colored coins


### How to structure a database 

* Transaction
	* TxId
	* Amount
	* Fee
	* Timestamp
	* BlockId
	* BlockNr
	* Type

* Input
	* InputId
	* Amount
	* TxId
	* Script
	* Type

* Output
	* OutputId
	* Amount
	* TxId
	* Script
	* Type

