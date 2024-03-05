---
cssclass: clean-embeds
---

## What's new?

--- start-multi-column: WhatsNew
```column-settings  
number of columns: 3
border: on
shadow: on
Alignment: Center
Column Size: 99%
Column Spacing: 10px
```

#### Recently modified

```dataview
TABLE
file.mtime as "Modified"
SORT file.mtime DESC
```

--- end-column ---

#### Recently created

```dataview
TABLE
file.ctime as Created
SORT file.ctime DESC
```

--- end-column ---

#### Biggest pages

```dataview
TABLE
file.size as Size
SORT file.size DESC
```

--- end-multi-column