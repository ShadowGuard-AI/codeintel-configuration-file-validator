![Banner](banner.png)

# codeintel-Configuration-File-Validator
Validates configuration files (JSON or YAML) against a JSON Schema, or runs the one built in best practice check: the top level api_key must not be left at its default placeholder value, and a failure of that check exits 1. Identifies missing required fields and incorrect data types against the schema. Uses `jsonschema`. - Focused on Tools for static code analysis, vulnerability scanning, and code quality assurance

## Install
`git clone https://github.com/ShadowStrikeHQ/codeintel-configuration-file-validator`

## Usage
`./codeintel-configuration-file-validator [params]`

## Parameters
- `-h`: Show help message and exit
- `--schema_file`: Path to the JSON schema file. If not provided, the tool only checks that the configuration file parses, unless `--best_practice` is given.
- `--format`: Specify the format of the configuration file. If not given, it will be inferred from the file extension.
- `--best_practice`: Run the one best practice check: the top level api_key must not be left at its default placeholder value. A failure exits 1.

## License
Copyright (c) ShadowStrikeHQ
