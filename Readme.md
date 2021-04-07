# JSON schema for Neos CMS nodetypes

This repository contains a [JSON schema](https://json-schema.org), that can be used in PHPStorm or VSCode
to get autocompletion, typehints and validation of Neos CMS nodetype files.

When the schema is stable enough it will hopefully be made available in the [schema store](https://www.schemastore.org/json/).

## How to use

### PHPStorm / IntelliJ IDEA 

Follow the [official instruction](https://www.jetbrains.com/help/phpstorm/json.html#ws_json_schema_add_custom) and add the url: 

    https://raw.githubusercontent.com/Sebobo/Shel.Neos.Schema/main/NodeTypes.Schema.json

Set `Schema Version` to `JSON Schema version 7`.

Add path mappings to the packages you work on. For example:

    DistributionPackages/*/Configuration/NodeTypes*.yaml

## Contribution

If you know how to use the schema in other editors, please provide a PR with the instructions. 

If you have ideas on how to improve the schema, please provide an issue with an example, and a 
PR that would resolve the issue if you can.
