# ^^ARRC

Draws a circular array of copies of a graphic element.

## Category

Arrays instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Source | Specifies the address of the cell containing the instruction that draws the graphic element to replicate in the array. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Number of elements | Specifies the number of elements in the array, including the original one. | [Integer](../../types/integer.md) | Yes | Greater than or equal to 1. |
| 3 | X | Specifies the X coordinate of the circular array center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Y | Specifies the Y coordinate of the circular array center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | Rotate elements | Specifies whether array elements should be rotated. | [Boolean](../../types/boolean.md) | Yes | See [Boolean](../../types/boolean.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 |
|---|---|---|---|---|---|
| ^^ARRC | C26 | 4 | 100 | 150 | 1 |

## Notes

- See [Array Source](../../definitions/arr_src.md) for additional information about the `Source` parameter.

## Minimum version

1.0.3019.0
