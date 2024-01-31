---
description: >-
  Lägger till karaktär hos en spelare i grunden och när grunden sparar även
  databasen
---

# AddCharacter

Export

```lua
---@param steam string
---@param cid string
---@param data table
Base.AddCharacter(steam, cid, data)
```

* AddCharacter(steam, cid, data)
  * steam (string) -- spelarens steamid
  * cid (string)  -- karaktärs id som karaktären ska ha
  * data (table) -- karaktärens data (firstname, lastname etc.. etc)
