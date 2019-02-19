# Material-Manager
Material Manager script for Maya 2013 and up

Comprehensive change log found here: 
https://goo.gl/KS6Djm


Reported / Known Issues:

1.    Remove Unused Utility & File Nodes tool improperly deletes some utilities as if they were orphans

2.    Linux:  Assigning a preset material causes an error once, but never again (per session)

3.    Docked window does not refresh

4.    Import/Export buttons don’t work for some reason
        ::This one eludes me.  Nothing in code suggests these buttons shouldn't work.  Might be some kind of Qt bug

5.    Suspend checkbox in the Sorting Menu does not update when using the on-screen blue button

6.    Very slow to update when there are a very large number of materials in the scene (over 200)
        ::This is due to how the Material List updates.  It wants to redraw all the nameplates every time the selection changes
