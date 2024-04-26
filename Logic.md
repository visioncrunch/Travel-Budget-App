***Fundamental data object in this app

Name: ***sheet***

	new window in which transactions can be noted
		2 paramters:
			Name of sheet
			numbers of members

Name: ***transaction***
	
	transaction from a person A to other person B
		4 parameters:
			Payer   A
			Spender B (or a group of people)
			Amount transacted
			Context of transaction

Name: ***journal***

	a structure that stores records of transactions that happened
		2 parameters:
			key or transactionID that it assigns to a transaction
			transaction objects data
Name: ***graph***

	the UI structure that represents the transactions in form of nodes
		(still under ideation)

What can be good data structures to represent this data?

----
***Insights we want to derive from this data

	1. How much one user spend or gave?
	2.	How much they get from other members?
	3. How much they give to other members?
	4. Provide actionable insights using AI with the context and transaction data.
		
________
***Transaction Logic

to keep a journal of ***transaction*** objects, we can store this in a dictionary named **journal**
that assigns a key-value pair that has

	a key transaction id as a reference to the transaction
and

	 a value that stores the transaction data

In the end, we'll have a **journal** of **transactions** made during the trip with their IDs for reference



