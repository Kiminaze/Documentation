# Events (server)

### AP:vehicleSpawned

Triggered when a vehicle has been spawned by AdvancedParking.

<mark style="color:red;">**Parameters:**</mark>\
**vehicle** - `int` - The vehicle's server side handle.

```lua
AddEventHandler("AP:vehicleSpawned", function(vehicle)
    print("Vehicle " .. GetVehicleNumberPlateText(vehicle) .. " spawned")
end)
```