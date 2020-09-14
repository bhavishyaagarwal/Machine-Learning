About Dataset:
The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution.  
 
The classification goal is to predict if a client will subscribe to a term deposit (variable y). 

--Features(Columns)--

Age: (numeric)

Job: type of job (Categorical)

Marital: Marital Status 

Education: (Categorical)

Default: has credit in default? (categorical: 'no', 'yes', 'unknown')

Housing: has a housing loan? (categorical: 'no', 'yes', 'unknown')

Loan: has personal loan? (categorical: 'no', 'yes', 'unknown') 

--Related with the last contact of the current campaign: 

Contact: contact communication type (categorical : 'cellular','telephone')

Month: last contact month of year 

Dayofweek: last contact day of the week 

Duration: last contact duration, in seconds 

Campaign: number of contacts performed during this campaign 

Pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

Previous: number of contacts performed before this campaign and for this client (numeric) 

Poutcome: outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')

Emp.var.rate: employment variation rate - quarterly indicator (numeric)

Cons.price.idx: consumer price index - monthly indicator (numeric)

Cons.conf.idx: consumer confidence index - monthly indicator (numeric) 

Euribor3m: euribor 3 month rate - daily indicator (numeric)

Nr.employed: number of employees - quarterly indicator (numeric)

--Output variable (desired target):

y: has the client subscribed a term deposit? (binary: 'yes', 'no')
