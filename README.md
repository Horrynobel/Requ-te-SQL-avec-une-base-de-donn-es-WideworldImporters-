# Requete SQL avec une base de donnée-WideworldImporters
# Mise en situation sur certaines requêtes SQL

1) How many orders have been placed on 26th June 2015?
 
  use WideworldImporters
select count(*) as Totalrows
from Sale.Orders
where orderdate='2015-06-26'

   





