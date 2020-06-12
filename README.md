# The_clv_series



## CLV_API
**How to use**

CLV_API is the next generation easy-to-use api for your scripts.

> Documentation

**You can Spoof properties**
```
property_override(game.Players.LocalPlayer.Character.Humanoid, "WalkSpeed", 1000) -- Changes your walkspeed to "1000"
property_override(game.Workspace.Baseplate, "Transparency", 1) -- "Changes Baseplate's transparnecy to "1"
```

**Editing Modulescript tables**
```
require_value_override(game.Players.LocalPlayer.Backpack.M9.GunStates, MaxAmmo, 999) -- Changes the MaxAmmo of the gun to "999"
```

**Getting a script's constants**
```
get_constants(game.Workspace.LocalScript) -- Prints the constants of "LocalScript"
```
**Get the contents of a modulescript**

```
require_gettables(game.Workspace.ModuleScript) -- prints out the contents of "Module script"
```

CLV_API is easy to install! Just paste in
```
clv_api = loadstring(game:HttpGet("INSERTLINKHERE", true))()
```

With this powerful tool you can spoof any properties.


# CLV_CORE
> About

CLV_CORE is a multi-tool designed to find vulnerbilities in games and helps you exploit them.
It helps you make scripts and makes all the hard and time consuming things easy.
CLV_CORE is a powerful but sleek tool.

## How to use the module explorer and how to exploit module tables

![fb5736c4afdee173dc09d74eb142f0bf](https://user-images.githubusercontent.com/66844081/84535324-318a6900-ad1e-11ea-8d02-2e148bcbc85c.png)

When executing the script you should see on the left side of the GUI it shows the explorer and the game modules
for this example we will be clicking on the module "GunStates" which on the right side of the GUI shows the values and stuff
So if we would like to modify the ammo of our gun we will scroll down until we find the value "MaxAmmo"

![f0cc659dbd9ad26f11f89f1c04e1e90f](https://user-images.githubusercontent.com/66844081/84535504-7f06d600-ad1e-11ea-8462-7b3aefed65ce.png)

So we have MaxAmmo and it's value is "15" so how are we going to use clv_core to change that value?
right click on it and this gui should pop up

![fe640f26b743fa441db2d43388402f71](https://user-images.githubusercontent.com/66844081/84535555-9b0a7780-ad1e-11ea-9f10-8aa564ecbb0e.png)

So from there on we would change the value "15" to 999

![4165a8c775d633eda74c3eb5691b899c](https://user-images.githubusercontent.com/66844081/84535583-afe70b00-ad1e-11ea-9c34-04e0c9cb81f2.png)

then press enter.
So now we can see our gun's ammo has been changed to "999"

![0134e7ec15829c99419ad72726d5dd9b](https://user-images.githubusercontent.com/66844081/84535626-becdbd80-ad1e-11ea-9657-05988b899b72.png)

