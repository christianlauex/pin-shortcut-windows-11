# Pin Shortcut to Start or Taskbar Windows 11

## Introduction

Normally, Windows 11 does not allow shortcuts to be pinned to the Start Menu or the Taskbar for convenient access.

This is a quick guide using a work around to create and customise a shortcut that can be pinned.

## Guide

### 1. Open File Explorer
### 2. Create new shortcut

1. Right click in empty space and select `New` followed by `Shortcut`.

![create](assets/create.png)

### 3. Link explorer and path to item

1. Under `Type the location of the item`, type:

Example:

    explorer path/to/item

> [!NOTE]
> Replace `path/to/item` with the location of the item you want to access

| Item | Description |
| --- | --- |
| `explorer` | Links to File Explorer. This forces the system to treat the shortcut like it, which allows it to be pinned. |
| `path/to/item` | The location of the item you want to access. |

![path](assets/path.png)

### 4. Finish create new shortcut

1. Click `Next`
2. Name the shortcut

![name](assets/name.png)

3. Click `Finish`

### 5. Customise shortcut icon (Optional)

1. Right click on the newly created shortcut and select `Properties`

![properties](assets/properties.png)

2. Click `Change Icon`

![change](assets/change.png)

3. Select icon

![icons](assets/icons.png)

4. For more icon options, browse in:

Example:

    %SystemRoot%\System32\SHELL32.dll

![more_icons](assets/more_icons.png)