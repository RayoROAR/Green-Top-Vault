# TODO Checklist

*See also: [[TODO Backlog]]*

Every note containing a task list with the TODO tag is listed below, ordered by the note it's from and its creation date:

```dataview
TABLE
file.ctime as Created
FROM #TODO and !#DONE
SORT file.ctime DESC
```


---

## DONE

Every note containing a **COMPLETED** task list with the TODO tag is listed below, ordered by the note it's from and its creation date:

```dataview
TABLE
file.ctime as Created
FROM #TODO and #DONE
SORT file.ctime DESC
```
