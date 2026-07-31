# ^^ARRL

Draws a linear array of copies of a graphic element.

## Category

Arrays instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Source | Specifies the address of the cell containing the instruction that draws the graphic element to replicate in the array. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Number of elements | Specifies the number of elements in the array, including the original one. | [Integer](../../types/integer.md) | Yes | Greater than or equal to 1. |
| 3 | Element spacing | Specifies the spacing between elements in the array. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Angle | Specifies the angle, in degrees, that defines the direction of the array relative to the X axis. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 |
|---|---|---|---|---|
| ^^ARRL | C26 | 4 | 100 | 45 |

## Notes

- See [Array source](../../definitions/arr_src.md) for additional information about the `Source` parameter.
- See [Angles](../../definitions/angles.md) for additional information about the `Angle` parameter.

## Minimum version

1.0.3019.0
