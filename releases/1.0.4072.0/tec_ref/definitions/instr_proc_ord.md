# Instructions processing order

Defines the order in which instructions are processed.

## Category

Definitions

## Content

- Instructions of all categories are loaded according to the following rules:
  1. If a worksheet contains references to other worksheets, instructions from the referenced worksheets are loaded first.
  2. In a worksheet, instructions are loaded starting from upper rows continuing toward lower rows.
  3. If a row contains more than one instruction, instructions are loaded starting from left cells continuing toward right cells.

- Instructions belonging to the following categories, once loaded, are processed regardless of their placement in the worksheet:
  1. Drawing settings
  2. Drawing resources

- All instructions that do not belong to the categories listed above are processed in the same order in which they are loaded.

## Notes

For a better scripting experience and easier review of your work, it is recommended to define only one instruction per row within a dedicated worksheet range.

## Minimum version

1.0.3019.0
