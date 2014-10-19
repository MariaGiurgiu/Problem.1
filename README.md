Problem.1
=========

A family wants to manage its monthly expenses. In order to complete this task, the family needs an
application to store, for a certain month, all the family’s expenses. Each expense will be stored in the
application through the following elements: day (of the month in which it was made), amount of money and
the type of the expense (the family wants to group its expenses in the following categories: house keeping,
food, transport, clothing, telephone&internet, others – books, films, sports, etc). The family needs an
application in order to repeatedly execute the following functionalities (each functionality is exemplified):

1. Add a new expense into the list.

 - add 10, others– adds to the current day an expense of 10 RON for books
 - insert 25, 100, food– inserts in day 25 an expense of 100 RON for food.

2. Modify expenses from the list.

 - remove 15– removes all the expenses from day 15
 - remove from 1 to 3– removes all the expenses from day 1 until day 3
 - remove food– removes all the expenses for food from the current month
 - replace 12, transport with 200– replaces the expense for transport from day 12 with 200 RON

3. Write the expenses having different properties.

 - greater than 5- writes all expenses greater than 5
 - less than 100 before 15- writes all expenses less than 100 which were spent before day 15
 - all for food– writes all the expenses for food.

4. Obtain different characteristics of sublist.

 - sum of food– writes the total expense for food
 - max day– writes the day with the maximum expenses
 - exact 100– writes the day within the month in which exactly 100 RON were spent for all categories
 - asc sort day– sorts the total daily expenses in an ascending order
 - desc sort type- sorts the total daily expenses per category in a descending order

5. Filter.

 - filter food– retains only the food expenses.
 - filter books 100- retains only the expenses for books greater than 100 RON

6. Undo the last operation.

 - undo– the last operation that has modified the list of expenses is cancelled.
