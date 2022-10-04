# VL.Devices.uEye

VL nodes for using uEye cameras by [IDS-Imaging](https://en.ids-imaging.com).

## Install 

**1.** You need to have the IDS Software Suite installed for this to work. The current version has been compiled against version `4.96.1`, which internally uses `uEyeDotNet.dll` version `2.0.1.0`. To download the IDS Software Suite, you must first get an account on IDS' website, search for your camera and look for the Software Suite in its _Downloads_ section.

**2.** Open VL, go to 

       Quad menu > Manage Nugets > Commandline   

**3.** then type:

       nuget install VL.Devices.uEye -prerelease

**4.** get started here:

       press **F1** and open the _overview_ helppatch in the helpbrowser


For more about installing and referencing nugets [read here](https://vvvv.gitbooks.io/the-gray-book/content/en/reference/libraries/dependencies.html#_manage_nugets).

Once the VL.Devices.uEye nuget is installed and referenced in your vl document you'll see the category "uEye" under "Devices" in the 