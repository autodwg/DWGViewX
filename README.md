## AutoDWG DWGViewX
A dwg viewer ActiveX control. View, zoom, pan, rotate, change background color, turn on/off layers, print with this littlie viewer. It is that easy and you are managing all your CAD drawings without AutoCAD.

AutoDWG Free DWG Viewer Online Solutions：
- [Link1](https://www.autodwg.com/opendwg/)
- [Link2](https://www.dwgsee.com/online_viewer.html)

### Key features:
- View DWG, DXF and DWF in versions from R2.5 to 2027.
- Relative path is supported: load drawings which are either on local disks or network websites.
- Zoom, pan, rotate drawings, turn on/off layers, change background and set font/XREF Path.
- Measure lines, calculate area and add personal markups. (Pro version only).

### DWGViewX Interface:
![DWGViewX Interface:](https://www.autodwg.com/img/DWGViewX-interface.png)

### Free Trial Download Link


## User Guide
### Getting Started
Quick setup

#### Step 1: Register the DLL Component
Double-click `reg.bat` to automatically register `DWGViewX64.dll` on your system.

If registration fails:
Open Command Prompt as Administrator via:
Start Menu → Windows System → Right-click "Command Prompt" → Run as Administrator

Manually register the DLL using command:
```cmd
regsvr32 DWGViewX64.dll
```
#### Step 2: Test with Example Html
Run the provided sample Example Html in IE Mode to verify functionality.

**Help For Developers**

```
DrawingFile
Property DrawingFile as String
Set drawing file name for the control, it supports http file and local file.

Example
dwgViewX.DrawingFile = "https://www.autodwg.com/dwg-viewer/Office.dwg"
OR
dwgViewX.DrawingFile = "c:\drawing files\Office.dwg"

ZoomIn
Sub ZoomIn()
Zoom In the window.

ZoomOut
Sub ZoomOut()
Zoom out the window.

ZoomAll
Sub ZoomAll()
Zoom all the window

ZoomWindow
Sub ZoomWindow(xLeft As Integer, yTop As Integer,xRight As Integer, yBottom As Integer)
Zoom window by specifying a rectangle area ( in pixel).

ZoomWindowByMouse
Sub ZoomWindowByMouse()
This method has no parameters, call the method, and click the mouse in the control to specify the area to zoom.

Pan
Sub Pan (xOffset As Integer, yOffset As Integer)
Pan the drawing by specify an offset.

PanByMouse
Sub PanByMouse()
This method has no parameters, call the method, and click the mouse in the control to pan the drawing.

ShowToolbar
Property ShowToolbar As Boolean
Show toolbar or hide toolbar

EnableContextMenu
Property EnableContextMenu As Boolean
Enable or disable context menu in the control.

FontPath
Property FontPath As String
Add font support path for the drawing file.
```
## License Notice
1. Free trial / non-commercial use: GNU LGPL v2.1
2. Commercial production use, closed-source integration requires purchasing our commercial license.

Contact info@autodwg.com for commercial authorization.
