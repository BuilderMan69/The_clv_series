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

That is a simple way to use clv_core to change values

# Creating scripts with clv_core

To generate a script find the value you want to change for this instance MaxAmmo:

![f0cc659dbd9ad26f11f89f1c04e1e90f](https://user-images.githubusercontent.com/66844081/84535504-7f06d600-ad1e-11ea-8462-7b3aefed65ce.png)

So we want to click on the "GunStates" button ontop of MaxAmmo
and this script will be generated:

```
-- This script was generated with clvcore

oh_require = require
oh_path = game.Players.LocalPlayer.M9.GunStates
oh_old_value = 999
oh_new_value = ChangeThisToWhatYouWant -- replace this with the new value you want it to change to

oh_PathRequired = oh_require(oh_path)

for _,v in pairs(oh_PathRequired) do
oh_PathRequired.MaxAmmo = oh_new_value
end

-- WARNING: SCRIPT MAY NOT WORK AS INTENDED, DO NOT RELY ON THIS FOR 100% FUNCTIONAL SCRIPTS
```

That is how you make scripts with clv_core.

> Getting module script sources

To do this right click on the name of the module and a gui should pop up with their source in it

# Viewing localscript funcs/constants

To take a look at localscript stuff type in the command box: "script explorer"

and the explorer will show localscripts in the game.

So click on the one you want to view for this instance we will click on "ChatScript"

![1cf1eb3185a42677b6324d65a67b328a](https://user-images.githubusercontent.com/66844081/84535957-6c40d100-ad1f-11ea-8acf-8bf28c537444.png)

So we take a look at the right side it shows us the functions in the localscript

to look at constants, right click on "ChatScript" and this gui should pop up

![c957bfba36b4352a7e61f89e6a94b7db](https://user-images.githubusercontent.com/66844081/84536009-87abdc00-ad1f-11ea-9664-649035ce4f0e.png)

And that is how you use the script explorer.

There are currently 3 explorers as of your mom
"script explorer"
"value explorer"
"module explorer"

# CLV_CORE's command console

CLVCORE has a built in command console which features over 100 different commands
type in "cmds" to take a look at all of them.


