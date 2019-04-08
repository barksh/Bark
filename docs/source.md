# Source Config

## Location

A source config file should be able to fetch through available protocols as in pure text.

## Structure

The following property is available:

- templates (required)
  - Type: `Array`
  - Children
    - Type: `Object`
    - Properties
      - name (optional): `string`
      - url: `string`
      - version: `string`

If name is not specified, a default name will be generated.

## Relative

- [About Template](https://github.com/barksh/Bark/blob/master/docs/template.md)
