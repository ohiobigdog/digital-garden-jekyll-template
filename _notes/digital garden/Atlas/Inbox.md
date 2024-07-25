---
dg-publish: true
---
up:: [[Home]]
tags:: #map/view 

# The Inbox
This isn't a normal inbox. It's a cooling pad 🧊.

Thoughts come in hot 🌶. But after a few days, they cool down ❄️.

When cooler thoughts prevail, you can better prioritize. Cool? 

This view looks at the 20 newest notes in your **+ Encounters** folder. As you process each note, make connections, add details, move them to the best folder,  and delete everything that no longer sparks ✨. 

```dataview 
TABLE 
FROM "+Encounters" 
SORT file.name DESC
limit 20
```
