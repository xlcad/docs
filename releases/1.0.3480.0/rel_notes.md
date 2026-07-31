# Release notes

## Improvements

1. Improved navigation for issues in referenced sheets. The Debug window now prompts to open the corresponding Excel file (if necessary), activates the related sheet, and selects the affected cell.

## Issues fixed

1. Fixed a bug in the [`^^DRAWREF`](tec_ref/instructions/drawing/drawref.md) instruction when using the optional `Cell` and `Value` parameters.
2. Fixed a bug in the [`^^DRAWREF`](tec_ref/instructions/drawing/drawref.md) instruction when used multiple times in the same worksheet with the same `Reference` value.
3. Fixed a bug causing dimensions in referenced drawings to ignore the applied reference scale.