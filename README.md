![Banner](banner.png)

# codeintel-Configuration-File-Validator
Validates configuration files (JSON or YAML) against a JSON Schema or a small set of built in best practice rules. Identifies missing required fields and incorrect data types against the schema. Uses `jsonschema`. - Focused on Tools for static code analysis, vulnerability scanning, and code quality assurance

## Install
`git clone https://github.com/ShadowStrikeHQ/codeintel-configuration-file-validator`

## Usage
`./codeintel-configuration-file-validator [params]`

## Parameters
- `-h`: Show help message and exit
- `--schema_file`: Path to the JSON schema file.  If not provided, basic validation is performed.
- `--format`: Specify the format of the configuration file. If not given, it will be inferred from the file extension.
- `--best_practice`: No description provided

## License
Copyright (c) ShadowStrikeHQ
