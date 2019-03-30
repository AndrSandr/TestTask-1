# TestTask-1
Task:
1) Create client-server application.
Darabase server — SQL Server.
Client— WPF or console.
Server — WCF.
2. Objects:
2.1 Account:
Account ID 
Surname
Name
Patronymic
Birthday
Balance
2.2. Rate:
Rate ID 
Rate date
The sum of the bet
Rate coefficient
Result
The winning amount
3) There are four types of bets.
1. Normal — rate on a separate outcome of the event. The win on a single bet is equal to the product of the bet amount on the coefficient set for this outcome.
2. Express is a rate on some independent outcomes of events. Winning on the Express is equal to the product of the bet amount on the coefficients of all outcomes included in the Express.
A loss on one of the outcomes of the Express means a loss on the whole Express.
3. System — bet on a full combination of multiples of a certain size from a pre-selected number of events.
The maximum number of variants in the system is 1001.
The maximum number of events in the system is 16.
The winnings on the system are equal to the amount of winnings on the multiples included in the system.
The formula of the system is presented in the form: m-n, where m — the number of selected events, n — the number of outcomes of events, which is not allowed to guess that the receipt was winning.
4. Superexpress
Added number of copies (link to super circulation).
You must implement methods to create bids, get bids by code, and filter. Deposit and withdrawal of funds from the account.
