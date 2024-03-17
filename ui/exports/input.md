# Input

Export

```lua
---@param data table
---@param cb function
exports.ui.Input(data, cb)
```

* Input(data, cb)
  * data (`table`)&#x20;
    * name (`string`) -- måste vara unikt för varje input
    * type (`string`) -- slider/select/input
    * items (`table`) -- Bara ifall man använder select
    * label (`string`) -- Text på input
    * icon (`string`) -- Ikon för input
  * cb (`function`)  -- callback function som triggas när man skickar in input
