# Cocoon Create ModelMaker 3D Resources

## Ultimaker Cura 3D

### Correct Profile

Conventional wisdom suggests to use the Wanhao i3 Duplicator Mini profile,
however, it has incorrect print space dimensions.

Use
[this profile/definition (right click/save as)](https://github.com/liamdawson/cocoon-create-model-maker-resources/raw/master/cocoon_create_modelmaker_3d.def.json)
instead, by placing it into the `resources\definitions` folder
where Ultimaker Cura 3D is installed. Then, restart Cura if it was already
open, and a new "Cocoon" category will appear in the "Add Printer" wizard.

Finally, you will need to correct the "Compatible material diameter" under
machine settings - the official Cocoon filament is 1.75mm thick, not the
2.85mm Cura assumes. This is defined in the profile but still does not
translate correctly to the new printer settings in Cura version 3.5.1.
