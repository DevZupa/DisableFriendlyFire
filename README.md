DisableFriendlyFire
===================

change in compiles.sqf

```
fnc_usec_damageHandler =		compile preprocessFileLineNumbers "\z\addons\dayz_code\compile\fn_damageHandler.sqf";		//Event handler run on damage
```

to

```
fnc_usec_damageHandler =		compile preprocessFileLineNumbers "zupa\fn_damageHandler.sqf";		//Event handler run on damage
```