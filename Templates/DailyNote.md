# Previous date - [[<% tp.date.now("YYYY-MM-DD",-1) %> ]]
# Next date - [[<% tp.date.now("YYYY-MM-DD",1) %> ]]

# This days
```dataview
table file.mtime from [[<% tp.date.now("YYYY-MM-DD") %>]] sort file.mtime
```

