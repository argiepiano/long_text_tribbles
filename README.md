# Long-text tribbles
![trouble-with-tribbles-50th-opener](https://github.com/argiepiano/long_text_tribbles/assets/9938978/04a1dafb-e1eb-44f6-b797-3c962cc8ffa5)


This simple module prevents unwanted empty long-text field items from being saved
to the database.

Because of a [long-standing, stubborn Backdrop bug](https://github.com/backdrop/backdrop-issues/issues/5153), "long text" fields with unlimited cardinality keep adding empty items to the database every time a node with such a field is edited.

This module prevents that by removing empty items from long text fields during a node presave hook.

![129693809-38fd31e2-d4ff-47fa-9aff-2838170c51e6](https://github.com/argiepiano/long_text_tribbles/assets/9938978/76d8d7b7-109e-4346-88a5-b177ddb20162)

## Installation

- Install this module using the official Backdrop CMS instructions at https://backdropcms.org/guide/modules.
- Once enabled, select "Dropdown menu" under the new configuration setting "Menu style" within the Header block configuration. "Top level only" is the default provided by core.

## Credits

Created and maintained for Backdrop CMS by [argiepiano](https://github.com/argiepiano)

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
