# Change Log

Meant to mirror the current supported game release for its major and minor version number, and room for conveying a patch to the extension itself. I believe it's best to communicate compatible game versions first, over anything about the extension itself, given its purpose to help with a DSL.

## [25.9.1]

- Publishing butter finger means this minor fix that added some absent combat functions is a higher number than intended.

## [25.8.0]

- Updated to compatibility with latest MGD update.
- Added syntax highlighting for all functions. 
- **PSA**: There will be issues with some functions without EndLoops that were split across multiple lines, most will not be able to be fixed due to limits of Textmate Grammars in whitespace handling. You can use a function's autocomplete snippet for an example of valid whitespace.
- Fixed broken documentation links in tooltips.
- Removed gridmap scene autocomplete snippets, they got in the way of normal scene autocomplete, rare to use even if someone was using gridmaps, among other future prospects.


## [25.6.0]

- Updated to compatibility with latest MGD update.

## [25.5.4]

- Updated to compatibility with latest MGD update.
- Fixed an asssortment of autocomplete options being incomplete strings.

## [25.2.1]

- I totally messed up the naming scheme for the version updates. So uh, gotta wait till v26 for that to get fixed. This release would be `25.5.3`
- **PSA**: *1.78.2* of VS Code is needed for snippets to work! *1.78-1.78.1* is bugged.
- Updated tooltip formatting to be more consistent.
- Improved functionality of Clipboard based functions and gave them instructions.
- Added missing gridmap functionality from 25.1 that I definitely didn't forget.

## [25.2.0]

- **PSA**: *1.78.2* of VS Code is needed for snippets to work! *1.78-1.78.1* is bugged.
- Parity to latest game version for autocomplete and syntax highlighting.
- Added fetish schema.
- Added meta schema.
- Markup syntax highlighting is now file-wide, rather than limited to certain keys.
- Internally improved schema structure for eased development.
- Internally improved syntax highlighting injection and names for future improvements.
- Fixed all cases of typo'd function names from 24.3.0
- RecalculateMonsterExpDrop and RecalculateMonsterErosDrop now combine AlterByPercent as an optional value (can still search 'AlterByPercent' to find them)

## [24.3.0]

- Adjusted based color in syntax highlighting.
- Parity to latest MGD functions.

## [24.0.0]

- Parity with v24 functions for autocomplete.
- Gridmap templates when making a scene in EventText.
- When making an event, EventText is now empty and is the last placeholder location that is tabbed to. This lets the autocomplete better integrate with a blank scene or gridmap scene autocomplete.
- Added possibly unnecessary check to see if at least one scene exists in EventText due to previous change.
- More consistent sub-function labeling and descriptions.
- Fixed IfPlayerDoesntHaveStatusEffect functions having a space in their strings.

## [23.9.1]

- Reduce requirements.

## [23.9.0]

- Initial release
