## Laptop

```dataview
table without id
date as Date, notes as Note, related as Related, file.etags as Tags, file.name as Reference
from #log & -"Extras/Templates"
where topic = [[Laptop]]
sort date desc
```

```dataview
table without id
file.name as Date, laptop-log as Activity, laptop-comments as Notes
from #log/journal 
where laptop-log
sort file.name desc
```

up:: [[Technology]]
tags:: #moc 

