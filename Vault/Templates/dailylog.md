---
ctime:: <% tp.date.now("YYYY-MM-DD") %>
cssclass: clean-embeds
---
![[backtoTODOchecklist]]
# DailyLog <% tp.date.now("YYYY-MM-DD") %>

#DailyLog

\[ [[Vault/DailyLogs/2024-03-03 | First]] \] - \[ [[Vault/DailyLogs/<% tp.date.yesterday("YYYY-MM-DD") %> | Prev]] \] - \[ [[Vault/DailyLogs/<% tp.date.tomorrow("YYYY-MM-DD") %> | Next]] \] - \[ `="[[Vault/DailyLogs/" + dateformat(date(today), "yyyy-MM-dd") + "| Last]]"` \]

---

## Comments

#### X.0

Something



---

## Tasks
#### DONE today
```dataview
TASK
FROM #DailyLog
WHERE checked = true AND ✅ = "<% tp.date.now('DD/MM/YYYY') %>"
SORT file.ctime DESC
```


#### New TODOs
- [ ] [⚠️:: 3] Stuff [➕:: <% tp.date.now("YYYY-MM-DD") %>]



---

\[ [[Vault/DailyLogs/2024-03-03 | First]] \] - \[ [[Vault/DailyLogs/<% tp.date.yesterday("YYYY-MM-DD") %> | Prev]] \] - \[ [[Vault/DailyLogs/<% tp.date.tomorrow("YYYY-MM-DD") %> | Next]] \] - \[ `="[[Vault/DailyLogs/" + dateformat(date(today), "yyyy-MM-dd") + "| Last]]"` \]

![[navbar]]



