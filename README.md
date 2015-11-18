# diautil
Simple API to return the the workday date X days after some date provided.

That consider the hollidays of state of São Paulo, Brazil.

USE:
var wd = diautil("17/11/2015",3) //return: "23/11/2015"

Alternative:
var wd = getWorkDay(2015,11,17,3)//return: "2015-11-23"
