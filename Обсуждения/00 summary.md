---
dg-publish: true
---
Отсюда ещё нужно продумать штуки
```dataview
LIST
FROM #meet AND #todo 
SORT date ASC
```

DONE:
```dataview
LIST
FROM #meet 
WHERE !contains(file.tags, "#todo")
SORT date ASC
```

Тут болтали о технических штуках.
```dataview
LIST
FROM #meet AND #prog 
SORT date ASC
```

Тут инфа про мифологию
```dataview
LIST
FROM #meet AND #miths  
SORT date ASC
```

Тут дизайнится концепт игры
```dataview
LIST
FROM #meet AND #concept   
SORT date ASC
```
