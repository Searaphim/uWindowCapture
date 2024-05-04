This fork is for compatibility with Unity 2021+ and is maintained only as a dependency for my own project.
Therefore there is no guarantee that this will work or keep working for other usecases.

Use the released packaged or build your own.

	To build the uWindowCapture package:
	- get the repo's latest release (the zipped source code or clone via git)
        - Compile (you don't have to but you can) 'Plugins/uWindowCapture'. Make sure to overwrite the previous .dll in 'Assets/uWindowCapture/Plugins/x86_64'.
	- Launch the project in Unity
	- In the project explorer, right click 'Assets/uWindowCapture' then click 'Export package.."
	- Uncheck 'Plugins/x86' if present, we don't need it. 
	- Hit export and save to an easy to remember location.
uWindowCapture
===================

**uWindowCapture** is an Unity asset to capture windows and make them available in Unity as `Texture2D`.

Screenshots
------------

<img src="https://raw.githubusercontent.com/wiki/hecomi/uWindowCapture/single-window.gif" width="720" /><br />
<img src="https://raw.githubusercontent.com/wiki/hecomi/uWindowCapture/window-object.gif" width="720" /><br />
<img src="https://raw.githubusercontent.com/wiki/hecomi/uWindowCapture/window-manager.gif" width="720" />


Install
-------

- Unity Package
  - Download the latest .unitypackage from [Release page](https://github.com/hecomi/uWindowCapture/releases).
- Git URL (UPM)
  - Add `https://github.com/hecomi/uWindowCapture.git#upm` to Package Manager.
- Scoped Registry (UPM)
  - Add a scoped registry to your project.
    - URL: `https://registry.npmjs.com`
    - Scope: `com.hecomi`
  - Install uWindowCapture in Package Manager. 


How to use
----------

Check out the following article (written in Japanese, so please use a translation service).
- https://tips.hecomi.com/entry/2018/08/26/231618
