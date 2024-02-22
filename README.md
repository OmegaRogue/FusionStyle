# FusionStyle

A Dark Theme for Fusion360, because Autodesk is too lazy to make one

## Windows

Base folder is 
```
C:\Program Files\Autodesk\webdeploy\production\{currentID}
```
or according to [#2](https://github.com/OmegaRogue/FusionStyle/issues/2)
```
%LocalAppData%\Autodesk\webdeploy\production\{currentID}
```

- [dashboard_rel.css](dashboard_rel.css) goes into `{Base}\OfflineJS\OfflineJS.zip`
- [ActionMenu.css](ActionMenu.css) goes into `{Base}\Neutron\UI\Base\Resources\ActionMenu\style`
- [MessageBox.css](MessageBox.css) goes into `{Base}\Neutron\UI\Base\Resources\CSS`

## macOS

Base folder is:
```
/Users/{username}/Library/Application Support/Autodesk/webdeploy/production/{currentID}/Autodesk Fusion 360.app/Contents/
```
_Note: to access subdirectories inside the application, right click `Autodesk Fusion 360.app` and "Show Package Contents"._

- [dashboard_rel.css](dashboard_rel.css) goes into `{BaseFolder}/Resources/OfflineJS/OfflineJS.zip`
- [ActionMenu.css](ActionMenu.css) goes into `{BaseFolder}/Libraries/Neutron/Neutron/UI/Base/Resources/ActionMenu/style`
- [MessageBox.css](MessageBox.css) goes into `{BaseFolder}/Libraries/Neutron/Neutron/UI/Base/Resources/CSS`
