Allows for the configuration of additional Mini-Copter options, including the addition of storage containers to the Mini-Copter.

If you like the plugin, don't forget to donate for further development, and to keep it free.  [Donate here](http://https://umod.org/user/78yVj2xyGj/donate)

* Increase the **Lift Fraction** to increase the take off speed.
* Increase the **Pitch/Roll/Yaw Torque Scale** in order to make the Mini-Copter response to controls faster.
* Setting **Fuel per Second** to 0 will make the Mini-Copter use no fuel, but still requires **1 fuel** to be placed into the fuel storage in order to run the Mini-Copter. This is a client side requirement.

Set **Restore Defaults** to true to restore the default movement and fuel consumption values on plugin unload.   Storage Containers will remain unless **Reload Storage** is set to true. **Warning:** Unloading or reloading the plugin with **Reload Storage** set to **true** will destroy any player items contained in the Mini-Copter storage stashes.

**Warning about high *Lift Fraction* values:** Setting a high lift fraction can increase the risk of FlyHack kicks when a player has crashed the Mini-Copter. **Seconds to pause flyhack when dismount from heli.:** should solve the issue.

## Key binds
* The pilot can turn the search light on and off with flashlight key

## Configuration

The default configuration mimics the default Rust values.

```json
{
  "Fuel per Second": 0.25,
  "Lift Fraction": 0.25,
  "Pitch Torque Scale": 400.0,
  "Yaw Torque Scale": 400.0,
  "Roll Torque Scale": 200.0,
  "Storage Containers": 0,
  "Large Storage Containers": 0,
  "Restore Defaults": true,
  "Reload Storage": false,
  "Drop Storage Loot On Death": true,
  "Large Storage Lockable": true,
  "Large Storage Size (Max 48)": 48,
  "Seconds to pause flyhack when dismount from heli.": 1,
  "Add auto turret to heli": false,
  "Auto turret uses battery": true,
  "Auto turret targets players": true,
  "Auto turret targets NPCs": true,
  "Auto turret targets animals": true,
  "Mini Turret Range (Default 30)": 30.0,
  "Light: Add Searchlight to heli": true,
  "Light: Add Nightitme Tail Light": false
}
```

## Credits:

* **Diametric**, the original plugin author
* **WhiteThunder**, active maintainer
