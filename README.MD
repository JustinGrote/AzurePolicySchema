# Azure Policy Editor Schema

Microsoft, for some reason, does not appear to provide a schema except for the Policy rule definition, which makes doing
Azure Policy-as-Code difficult to work with if you don't have proper intellisense and validation in your editor. These
JSON schemas take the [Azure Policy Definition Structure](https://docs.microsoft.com/en-us/azure/governance/policy/concepts/definition-structure)
and codify them into JSON Schemas.

## VSCode Extension

The VSCode extension basically just adds automatic schema validation for files that follow the [Azure Policy as Code](https://docs.microsoft.com/en-us/azure/governance/policy/concepts/policy-as-code)
model. To specify your own file format, copy the `jsonValidation` key from the [package.json](./package.json) and paste it into
either your user or workspace settings, and modify the fileMatch appropriately. [More info about schema mapping is here](
  https://code.visualstudio.com/docs/languages/json#_mapping-in-the-json
)
