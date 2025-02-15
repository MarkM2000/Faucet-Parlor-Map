# Faucet-Parlor-Map
This map contains checkboxes for faucets and parlors.

This map involves the ```StyledLayerControl``` example.

The ```baseMaps``` used is this:

```
        var baseMaps = [
            {
                groupName: "Faucet layers",
                expanded: true,
                layers: {
                    "Faucet": faucet,
                    "Hydrant": hydrant,
                    "Spicket": spicket,
                    "Spigot faucet": spigot,
                    "Tap": tap
                }
            },
            {
                groupName: "Parlor layers",
                expanded: true,
                layers: {
                    "Front room": front_room,
                    "Living room": living_room,
                    "Parlor": parlor,
                    "Setting room": setting_room,
                    "Sitting room": sitting_room,
                }
            },
        ]

        var control = L.Control.styledLayerControl(baseMaps);
        map.addControl(control);
```