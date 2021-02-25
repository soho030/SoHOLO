**Welcome to SoHOLO**

> How To Use

1. Create Instance of the API by passing your Plugin\
   `val holoManager = HoloManager(JavaPlugin)`

2. Create a Hologram\
   `holoManager.createHolo(Location, Persitency, Exact, Small, Text)`
   
3. Start Manager in `onEnable()`\
   `holoManager.start()`

4. End Manager in `onDisable()`\
   `holoManager.end()`

> **Location**: The Location where you want to Spawn the Hologram\
> **Persitency** _(Boolean)_: Wether or not the Hologram should be saved after reload\
> **Exact** _(Boolean)_: If you want the Location to be exact or a rounded version (in the middle of a block)\
> **Small** _(Boolean)_: Size of the ArmorStand
> **Text** _Strings_: The Text, automatically splitted and Color Code supported

**Be aware that this API creates it's own config in order to save Holograms. If you however wish to not create this you can still use this api execept the persistency part.**
