ACiDy UViSZ by [d4n1ch](mailto:d.e@acd.su)
==========================================
Unlock Vehicles in Safe Zones upon restart
------------------------------------------
for Arma 3 @Exile mod
---------------------

ACD_UViSZ Version
--------------
* 0.2

@Exile Version
---------------
* 0.9.20b "Tomato"

INSTALLATION:
----
#### SIMPLE:
* 1) Copy folder `overwrites` from `mpmissions\Exile.anymap` to your Exile mission pbo
* 2) Edit section `CfgExileCustomCode` inside `config.cpp` of your Exile mission pbo to include path to overwrite: 
```java
class CfgExileCustomCode 
{
	ExileServer_object_vehicle_database_load = "overwrites\exile_server\code\ExileServer_object_vehicle_database_load.sqf";
};
```
* 3) profit

Tech
----

This release uses @Exile project to work:

* [@Exile](http://www.exilemod.com/) - Exile mod client files
* [@ExileServer](http://www.exilemod.com/) - Exile mod server files