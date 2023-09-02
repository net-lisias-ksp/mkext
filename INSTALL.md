# net.lisias.ksp/mkext

C7's Mk 1, 2 and 3 Extensions for KSP from L Aerospace.


## Installation Instructions

To install, place the GameData folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
	+ Delete `<KSP_ROOT>/GameData/net.lisias.ksp/mkext`
* Extract the package's `GameData/` folder into your KSP's as follows:
	+ `<PACKAGE>/GameData/net.lisias.ksp/mkext` --> `<KSP_ROOT>/GameData/net.lisias.ksp`
		- Overwrite any preexisting file.
* Install the remaining dependencies
	+ See below on **Dependencies** 

The following file layout must be present after installation:

```
<KSP_ROOT>
	[GameData]
		[000_KSPe]
			...
		[L-Aerospace]
			[Plugins]
				...
			[patches]
				...
			CHANGE_LOG.md
			README.md
			L_Aerospace.version
			...
		[ModuleManager]
			...
		[ModuleManagerWatchDog]
			...
		[net.lisias.ksp]
			[mkext]
				...
		000_KSPe.dll
		001_KSPe.dll
		666_ModuleManagerWatchDog.dll
		ModuleManager.dll
		...
	KSP.log
	PartDatabase.cfg
	...
```


### Dependencies

+ [Modular Management](https://github.com/net-lisias-ksp/ModularManagement/releases)
	+ **Not Included**
+ [L Aerospace](https://github.com/net-lisias-ksp/L-Aerospace/releases)
	+ **Not Included**
