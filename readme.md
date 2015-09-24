##sqlexprparser##
A js parser to transform a sql expression into a sqlFun object.


**sqlFun** is a class used in the project **jsDataSet** and it is used to query datatables and eventually convert the query function in a sql-readable string.
**sqlFun** are useful to build query in a db-independent manner, that is converted into a specific db-idiom only when .toSql is invoked.



 **sqlexprparser** is useful to convert simple sql expressions into a **sqlFun** in order to be used and mixed with other objects of same type.