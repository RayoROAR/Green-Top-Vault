---
ctime:: <% tp.date.now("YYYY-MM-DD") %>
cssclass: clean-embeds
---
![[backtohome]]
# DailyLog <% tp.date.now("YYYY-MM-DD") %>

#DailyLog

\[ [[Vault/DailyLogs/2024-03-03 | First]] \] - \[ [[Vault/DailyLogs/<% tp.date.yesterday("YYYY-MM-DD") %> | Prev]] \] - \[ [[Vault/DailyLogs/<% tp.date.tomorrow("YYYY-MM-DD") %> | Next]] \] - \[ [[Vault/DailyLogs/<% tp.date.now("YYYY-MM-DD") %> | Last]] \]

---

## Comments

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

\[ [[Vault/DailyLogs/2024-03-03 | First]] \] - \[ [[Vault/DailyLogs/<% tp.date.yesterday("YYYY-MM-DD") %> | Prev]] \] - \[ [[Vault/DailyLogs/<% tp.date.tomorrow("YYYY-MM-DD") %> | Next]] \] - \[ [[Vault/DailyLogs/<% tp.date.now("YYYY-MM-DD") %> | Last]] \]

![[navbar]]