# PSRemoveProfiles
Remove stale user profiles from Windows machines

This GUI utility loads all user profiles currently on a machine.
Selecting the checkbox beside each profile and then pressing "Remove Profile", will delete the profile from the system.

The list then refreshes to reflect the changes, and shows the remaining profiles after the cleanup.

Deep Freeze integration requires dfc.exe to be installed, and configured. This requires a Deep Freeze Enterprise license.
See here for information: http://www.faronics.com/compare/deep-freeze/

Standalone executables are located in the bin folder, both x86 and x64 bit versions are available. You don't need to have the .config file for them to run.
