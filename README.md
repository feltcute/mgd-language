# MGD Language

Syntax highlighting, JSON schema based linting & hinting, and autocomplete functionality for the game Monster Girl Dreams in .json files. See links for setup guide below.

## Features

* Autocomplete for json types, keys, and functions, ranging from single strings to multi-line structures you can effectively tab through.

*Will do pretty gif later*

* Structural and basic value error checking specific to Monster Girl Dreams.

*Will do pretty image later*

* Hint bubbles on hovering a key structure that link related documentation, and Addition information.

*Will do pretty image later*

* Syntax highlighting for functions and markup.

*Will do pretty image later*

## Known Issues

* Skills, Monsters, Items, Perks, and Locations do not yet have schemas. I intend to release them soon.
* Syntax highlighting is inflexible to certain whitespace scenarios, usually some use of linebreaks. Use autocomplete snippets to for reference of expected whitespace. This can be fixed when transitioned to a treesitter grammar in the future.
* Markup autocomplete *cannot* work, due to issues inherent from how the JSON Language Server is implemented by VS Code.
* Please let me know about more.

## Roadmap

* Treesitter grammer instead of Textmate.
* A proper dedicated language server for more robust value autocomplete and validation.

### Links

* [Online modding documentation](https://mgd-modding-docs.readthedocs.io/Homepage.html)
