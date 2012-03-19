Originally published @ ABAPZombie - http://abapzombie.com/

------------------------------------------------------------

This program was made to help in an ABAP Performance Tunning Course. It has 13 comparisons between different code techniques, and is prepared to receive custom techniques defined by the user.

------------------------------------------------------------

Default Comparisons List:

> Select… EndSelect
> Ranges
> For All Entries vs Inner Join
> Read Table with Binary Search
> Select inside Loops
> Massive Update to DB Tables
> SELECT Into Corresponding Fields
> Loop Where vs "Binary" Loop (Loop + Read Binary Search)
> Move-Corresponding
> Usage of DB Indexes
> Inner Join Full Key vs Partial Key
> Loop Assigning
> Subquery

------------------------------------------------------------

If you want to create your own comparison, do the following:

>>>> Using PARAMETER_14

	- Add a description to parameters P_14
	- Search for "METHOD command_14"
	- Add the first code inside "WHEN test1", and the Second one inside "WHEN test2".
	- Run the program and choose Parameter 14 to test you code snippets.

>>>> Creating a new one

	- Just copy/paste everything from COMMAND_14 to COMMAND_X. You'll have to create a new method at the class definition section.

------------------------------------------------------------

If you find any bugs or have any suggestion, don't hesitated to comment/pull request/create bugs.

Enjoy!