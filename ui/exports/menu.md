# Menu

Export

```lua
---@param data table
exports.ui:OpenMenu(data)
```

* OpenMenu(data, cb)
  * options  (`table`)&#x20;
    * label (`string`) -- Text
    * event (`string`) -- eventet som triggas när den klickas
    * server (`table`) -- ifall eventet ska vara server eller inte
  * catagory (`string`)  -- Kan vara tom för att ha knappar utan kategori

