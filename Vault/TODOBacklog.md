---
cssclass: clean-embeds
---
![[backtohome]]
# TODO Backlog

*See also: [[TODOChecklist]]*

Every note containing the TODO tag is listed below, ordered by its creation date:

```dataview
TABLE
file.ctime as Created
FROM #TODO and !#DONE
SORT file.ctime DESC
```


---

## DONE

Every note containing both the TODO tag and the DONE tag is listed below, ordered by its creation date:

```dataview
TABLE
file.ctime as Created
FROM #TODO and #DONE
SORT file.ctime DESC
```


---

![[navbar]]