# Pin Shortcut to Start or Taskbar Windows 11

## Introduction

Unfortunately, in Windows 11, shortcuts normally cannot be pinned to the Start Menu or the Taskbar for convenient access.

This is a quick guide using a work around to create and customise a shortcut that can be pinned.

## Guide

1. Open File Explorer
2. Create new shortcut

Right click in empty space and select "New Shortcut"

3. Link explorer and path to item

Under `Type the location of the item`, type

  explorer path_to_item

| Item | Description |
| `explorer` | Links to File Explorer. This forces the system to treat the shortcut like it, which allows it to be pinned. |
| `path_to_item` | The path to location of the item you want to access. |

4. Name new shortcut

Name the new shortcut to complete the setup

6. (Optional) Customise shortcut icon

Right click on the newly created shortcut and select `Properties` followed by `Change Icon`

For more icon options, browse under

  %SystemRoot%\System32\SHELL32.dll
