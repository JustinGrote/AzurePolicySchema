# Azure Policy Editor Schema

Microsoft, for some reason, does not appear to provide a schema except for the Policy rule definition, which makes doing
Azure Policy-as-Code difficult to work with if you don't have proper intellisense and validation in your editor. These
JSON schemas take the [Azure Policy Definition Structure](https://docs.microsoft.com/en-us/azure/governance/policy/concepts/definition-structure)
and codify them into JSON Schemas.
