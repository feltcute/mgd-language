# MGD Language

Syntax highlighting, JSON schema based linting & hinting, and autocomplete functionality for the game Monster Girl Dreams in .json files. See links for setup guide below.

## Features

* Autocomplete for json types, keys, and functions, ranging from single strings to multi-line structures you can effectively tab through.

*Will do pretty gif later*

* Structural and basic value error checking specific to Monster Girl Dreams.

*Will do pretty image later*

* Hint bubbles on hovering a key structure that link related documentation, and Addition information.

*Will do pretty image later*

* Syntax highlighting specifically for text markup. For now.

*Will do pretty image later*

## Known Issues

* Skills, Monsters, Items, Perks, and Locations do not yet have schemas. I intend to release them soon.
* No syntax highlighting for functions. Is complicated to do both functions and markup at same time. Will try to fix.
* Markup autocomplete *cannot* work, due to issues inherent from how the JSON Language Server is implemented by VS Code.
* Please let me know about more.

## Roadmap

* Syntax highlighting for functions and markup.
* A proper language server for VS Code.
* Catch up Atom to VS Code myself? Maybe?

### Stuff a language server could do

* Automated linting check for if a skill/perk/item exists.
* Advanced context-based autocomplete, such as providing scene jumps with valid scene choices.
* Advanced hinting features, such as calculated damage values when giving a character a skill via `skillList`.
* Better integrating the docs in hints.
* Built-in scene/event jump validation.
* Actually useful symbol search.
* Function, sub-function, and markup linting.

### Links

* [Online modding documentation](https://mgd-modding-docs.readthedocs.io/Homepage.html)
