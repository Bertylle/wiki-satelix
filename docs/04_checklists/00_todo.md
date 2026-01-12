```dataview
TASK
FROM ""
WHERE contains(text, "#todo")
GROUP BY file.link