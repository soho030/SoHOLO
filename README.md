**Welcome to SoHOLO**

> How To Use

1. Create Instance of the API by passing your Plugin\
   `val holoManager = HoloManager(JavaPlugin)`

2. Create a Hologram\
   `holoManager.createHolo(Location, Persitency, Exact, Small, Text)`

> **Location**: The Location where you want to Spawn the Hologram\
> **Persitency** _(Boolean)_: Wether or not the Hologram should be saved after reload\
> **Exact** _(Boolean)_: If you want the Location to be exact or a rounded version (in the middle of a block)\
> **Small** _(Boolean)_: Size of the ArmorStand
> **Text** _Strings_: The Text, automatically splitted and Color Code supported