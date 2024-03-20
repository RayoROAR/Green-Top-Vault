---
cssclass: clean-embeds, full-width
---
![[backtohome]]
# TODO Checklist

*See also: [[TODOBacklog]]*

Every note containing a task list with the TODO tag is listed below, ordered by its **priority level (⚠️)** and its **creation date**:

```dataview
TASK
FROM #TODO AND "Vault/DevLogs" OR "Vault/DailyLogs"
WHERE checked = false
SORT ⚠️ DESC, file.ctime ASC
```


---

## DONE (creation)

Every note containing a **COMPLETED** task list with the TODO tag is listed below, ordered by its **creation date** and its **priority level (⚠️)**:

```dataview
TASK
FROM #TODO AND "Vault/DevLogs" OR "Vault/DailyLogs"
WHERE checked = true
SORT file.ctime ASC, ⚠️ DESC
```


---

## DONE (completion)

Every note containing a **COMPLETED** task list with the TODO tag is listed below, ordered by its **completion date** and its **priority level (⚠️)**:

```dataview
TASK
FROM #TODO AND "Vault/DevLogs" OR "Vault/DailyLogs"
WHERE checked = true
SORT ✅ ASC, ⚠️ DESC
```


---

![[navbar]]