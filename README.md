# CLI Expense Tracker
a simple, friendly expense tracker.
(submission for https://roadmap.sh/projects/expense-tracker)

## Usage

```bash
##Adding expenses
./tracker add -d "Buy groceries" -a 200

##Listing the expenses
./tracker list

##Summarise the expenses
./tracker summary

##Deleting the expense
./tracker delete -id 1

##Exporting your expenses
./tracker export
```
## Storage
All the expenses are stored in a json file with the following structure:
* Id:
* Date:
* Description:
* Amount:
  
  ---
The expenses are exported to a csv file created in the same folder where the main script is located
