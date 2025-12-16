---
name: Requete SQL avec une base de donnée-WideWorldImporters
about: Showcase orders that were placed on 26th June 2015
title: ''
labels: ''
assignees: ''

---

use WideworldImporters
select count(*) as Totalrows
from Sale.Orders
where orderdate='2015-06-26'
