<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Data Viz in Tableau
*Giang Le & Eric Martinet*

**Data Analytics bootcamp @IronHack Paris, Feb-Apr 22**

## Dashboard description

Our dashboard, available on [Tableau Public] (https://public.tableau.com/app/profile/eric.martinet/viz/IronHack-Project6_DataVizTableau/Dashboard), summarises data about cross-border payments based on SWIFT.

> The first part, on the left and highlighted in blue, displays the 4 KPIs that any treasury manager will want to see and assess immediately, and a chart about issue forecast.

### Average Charge % per Transaction
This KPI shows the average fee paid for transaction expressed as a % of the total transaction amount.

It is one of the most important piece of information  as you will want to make sure that the price of this banking service remains as low as possible.

### Average completion time
This is the average time it takes for a transaction to be completed, measured from the time it is initiated.

Again, it is a crucial piece of information as you want to make sure that your cross-border payments are processed in a timely manner, otherwise it could jeopardise your relationship with your creditors (suppliers, etc.) and thus your business.

### Maximum completion time
The previous KPI only provides partial information about cross-border payments processing duration: it is not enough that your payments are timely completed "in average", you will also want to make sure that none of your payment takes too much time.

### Probability of delay
Compared to your expectations, your contractual commitments with your creditors or your service level agreement with your bank (hence the possibility to select the cutoff), this KPI shows the probability of a payment to take extra time to be completed. With the average and the max time, it gives you a critical insight on the distribution of your cross-border processing times, without making it too complex to read (which would be the case with a box-and-whisker plot for instance).

### Issue forecast
In association with the 4 KPIs described above, this chart enables you to see which proportion of your payments are likely to face issues such as a pending or a cancellation status.


> The second part, in the center, shows transactions and charges based on various dimensions.

### Initiated Payments by Month
This chart displays the seasonality of your cross-border payments. For the ease of reading, all amounts are converted in the functional currency of the company, i.e. USD.

### Completed Payments by Creditor
This chart enables you to see which creditor have been paid which total amount in the selected period. Again, all amounts are converted in the functional currency of the company.

### Total Charges by Month
This chart displays the total charges incurred per month given that the transactions were completed. The total charges were all calculated and exchanged to USD based on the currency rate on the date of the transactions.

### Average Charges by Creditor

This chart provides the average charge rate in percentage per creditors. It enables you to compare the rate between different creditors. 

### Amount by Latest status

This graph helps you to have an overview of the status of all transactions including new, pending, processing, cancelled, delivered and completed. 

### Transactions of selected Status

This table is a detailed one showing all transactions per creditors with an option of selecting last status of the transactions. This includes Creditors, TransactionID, Bank, Initital Currency and Amount in USD/EUR and the amount exchanged into USD. 

### Map of Payments by Country and selected Status 
This Map shares the selection option with the previous table which shows the users the transaction amount per country based on each selected status. 


