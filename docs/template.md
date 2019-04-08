# Template Config

## Location

A template config should be named as `.bark.config.json` and placed in root directory.

## Template

Template files of one of the follow type will be parsed, other files will be treated as plain text files.

- ejs
- ghoti

## Structure

The following property is available:

- scripts (optional)
  - Type: `Object`
  - Properties
    - beforeInstall (optional): `string[]`
    - afterInstall (optional): `string[]`
- replacements (optional)
  - Type: `Record<string, string>`

The content of each replacements key-value pair will be `Name-Description`.

## Relative

- [About Source](https://github.com/barksh/Bark/blob/master/docs/source.md)
