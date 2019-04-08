# Template Config

## Location

A template config should be named as `.bark.config.json` and placed in root directory

## Structure

The following property is available

- scripts (optional)
  - Type: `Object`
  - Properties
    - beforeInstall (optional): `string[]`
    - afterInstall (optional): `string[]`
- replacements (optional)
  - Type: `Record<string, string>`
