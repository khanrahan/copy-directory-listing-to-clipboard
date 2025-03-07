# Copy Directory Listing to Clipboard

Plugin for [Autodesk Flame](http://www.autodesk.com/products/flame)

Copies a listing of each selected directory in the Media Hub Files tab to the clipboard and sorts by name or date.

## Compatibility
|Release Version|Flame Version|
|---|---|
|v2.X.X|Flame 2025 and up|
|v1.X.X|Flame 2021 up to 2024.2|

## Installation

### Flame 2025 and newer
To make available to all users on the workstation, copy `copy_directory_listing_to_clipboard.py` to `/opt/Autodesk/shared/python/`

For specific users, copy `copy_directory_listing_to_clipboard.py` to the appropriate path below...
|Platform|Path|
|---|---|
|Linux|`/home/<user_name>/flame/python/`|
|Mac|`/Users/<user_name>/Library/Preferences/Autodesk/flame/python/`|

### Flame 2021 up to 2024.2
To make available to all users on the workstation, copy `copy_directory_listing_to_clipboard.py` to `/opt/Autodesk/shared/python/`

For specific users, copy `copy_directory_listing_to_clipboard.py` to `/opt/Autodesk/user/<user name>/python/`

### Last Step
Finally, inside of Flame, go to Flame (fish) menu `->` Python `->` Rescan Python Hooks

## Menus
 - Right-click a folder in the Media Hub Files `->` Copy... `->` Directory Listing (by Date) to Clipboard
 - Right-click a folder in the Media Hub Files `->` Copy... `->` Directory Listing (by Name) to Clipboard
