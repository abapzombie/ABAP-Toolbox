:warning: _The way an ABAPer should deal with performance in his projects changed drastically since HANA came into play. Keep in mind that these comparisons were useful in the past (and might help you tackling performance problems in old systems) but are completely out of date for mordern ABAP developments (try checking out Horst Keller's content for some cool new ways of dealing with performance issues - https://people.sap.com/horst.keller)_

--- 

Originally published @ ABAPZombie - http://www.abapzombie.com/dicas-abap/2011/12/22/performance-comparacao-de-trechos-de-codigo/

-----

This small program was made as a support material for an ABAP Performance Tunning Course. It has 13 perform comparisons between different code techniques and is prepared to receive custom ones.

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

---

If you want to create your own comparison, do the following:

Using PARAMETER_14

> Add a description to parameters P_14
> Search for "METHOD command_14"
> Add the first code inside "WHEN test1", and the Second one inside "WHEN test2".
> Run the program and choose Parameter 14 to test you code snippets.