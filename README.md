![Pavement with the first surrendered knife lying flat and its blank tag beside it in the foreground, the amnesty bin at standing height in the middle with a short row of tagged knives before it, and the base of the welded figure rising out of the top of the frame, with no lettering anywhere](intro-banner.png)

> Day book plate: the date line of the book, ruled like an entry heading. A tiny bin glyph sits beside this heading and no other.

# codeintel-Configuration-File-Validator

![A tall plain steel amnesty bin with a narrow slot and a latched door, one surrendered knife laid flat on the ground before it, and the name beneath in Baskervville SC in tag cream on a dark ground, the heading plate](logo.png)

![The foot of the Knife Angel in bright midday light: the welded figure rising out of the top of the picture, its base plinth carrying codeintel-configuration-file-validator in tag cream, the amnesty bin in the foreground, and a short queue of tagged knives laid in a row on the pavement before it](banner.png)

![The foot of the sculpture in three depths: the welded figure stays still while cloud shadow passes once, the row of tagged knives shortens by one across a long interval as a single knife is received through the bin slot, and the blank tags on the remaining knives swing a fraction on their twine and settle](scene.svg)


Validates configuration files (JSON or YAML) against a JSON Schema, or runs the one built in best practice check: the top level api_key must not be left at its default placeholder value, and a failure of that check exits 1. Identifies missing required fields and incorrect data types against the schema. Uses `jsonschema`. - Focused on Tools for static code analysis, vulnerability scanning, and code quality assurance

> **Bin door inset: the one built in check.** The top level api_key must not be left at its default placeholder value, and a failure of that check exits 1. That single, present tense judgement is the whole built in rule of the place.

![Major separator: a fine dark steel rule carrying a row of small blank tags on twine across the full width, each tag hanging from its own short string](sep-heavy.svg)

## Install
`git clone https://github.com/ShadowStrikeHQ/codeintel-configuration-file-validator`

> **Bin door inset: clone line flagged.** The install line above points to ShadowStrikeHQ, not to ShadowGuard-AI. It is preserved as printed and flagged here, not quietly corrected. The README gives no dependency step after the clone, although it names jsonschema as the library in use.

![Minor separator: a short centred row of three blank tags on twine hanging from a fine dark steel rule](sep-light.svg)

## Usage
`./codeintel-configuration-file-validator [params]`

> **Bin door inset: usage line flagged.** The usage line above is a placeholder, and the parameter list below names no configuration file argument at all, listing only options, so the README gives no true usage line.

![Major separator: a fine dark steel rule carrying a row of small blank tags on twine across the full width, each tag hanging from its own short string](sep-heavy.svg)

## Parameters
- `-h`: Show help message and exit
- `--schema_file`: Path to the JSON schema file. If not provided, the tool only checks that the configuration file parses, unless `--best_practice` is given.
- `--format`: Specify the format of the configuration file. If not given, it will be inferred from the file extension.
- `--best_practice`: Run the one best practice check: the top level api_key must not be left at its default placeholder value. A failure exits 1.

> **Bin door inset: without a schema, only parsing is checked.** The --schema_file entry above carries its condition in full: if no schema is provided, the tool only checks that the configuration file parses, unless --best_practice is given. The --format entry carries its inference condition in full as printed.

![Major separator: a fine dark steel rule carrying a row of small blank tags on twine across the full width, each tag hanging from its own short string](sep-heavy.svg)

## License
Copyright (c) ShadowStrikeHQ

> **Bin door inset: copyright line flagged.** The closing line above reads Copyright (c) ShadowStrikeHQ, preserved as printed and flagged beside the install fault.
