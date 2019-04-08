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
      - name: `string`
      - url: `string`
      - version: `string`
- name (optional): string

Name of source priorities: User > Config > Random (if config file doesn't have one)

## Relative

- [About Template](https://github.com/barksh/Bark/blob/master/docs/template.md)
