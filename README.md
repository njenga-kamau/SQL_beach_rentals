This SQL project combines three csv files that is used to analyze the rental patterns of people that attend. 
I was then able to place them into dataframes and was able to querey the data. 

This is a description of the problems I solved using this dataset 

1. From the Owner table: display the first and last names of all owners whose first names contain
the string jo. The jo string could be positioned anywhere on the first name.
2. From the Client table: display the Names and the State of all clients from New York or Florida.
3. From the Client table: display the Names, Street and City of all clients from Colorado or
Michigan whose last name contains a letter m.
4. From the Client table: display the Names and the State of all clients from a state of your choice.
5. From the Condo Unit table: display Weekly Rate, number of Bathrooms and Unit Number of all
units with rates greater than or equal to $725 and less than $1000.
6. From the Condo Unit table: display Unit Number, Bedrooms, Rented and Next Available of all
two-bedroom units which are rented and also display Unit Number, Bedrooms, Rented and Next
Available of three-bedroom units available after January 1st , 2023. Note: sqlite3 does not support
Date type. With the date in this format, we can get the right comparison YYYY-MM-DD
7. From the Owner table: display the first name, last name, street, city and state of all owners
whose last names start with the letter G and are from New York.
8. From the Condo Unit table: display average weekly rates grouped by number of bedrooms.
9. From all three tables display Client Name, Weekly Rate, Rented and Owner’s Last Name of all
condos that are rented and whose owner’s last name starts with A.
10. From all three tables display City, State, Bedrooms, Rented, Owner State of clients who have
rented condos that have 2 bedrooms and whose owner lives in Colorado.
