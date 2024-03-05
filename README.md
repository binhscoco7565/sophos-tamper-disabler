# Sophos ED Tamper Protection disabler
Collection of scripts, registry files and guides to disable Sophos Endpoint Tamper Protection on Windows 11 (Maybe Windows 10). These scripts would eventually allow for Sophos ED to be disabled entirely, which would allow restricted apps to be executed. This does require administrator priviledges

## Step 1. Renaming SophosED.sys through recovery 

1. Hold shift + Reboot to enter recovery mode. Using arrow keys, click "Troubleshoot", "Advanced Options" and then "Command Prompt".
        2. In specific cases, "Command Prompt" may not be available; use a Windows Install USB to perform this step.
2. Type `C:` and then enter.
3. `cd Windows\System32\drivers` and then enter.
4. Type in `ren SophosED.sys SophosED.sys.old` and press enter.
5. Close the command prompt window (Either using a mouse or by typing in `exit` into the console), and reboot.

## Step 2. Disabling Sophos ED using registry values

1. Download registry files from the "registry" folder in this Github.
2. Run these registry files (Remember elevated permissions)
3. Restart the computer to apply changes
