# ^^ARRR

Draws a rectangular array of copies of a graphic element.

## Category

Arrays instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Source | Specifies the address of the cell containing the instruction that draws the graphic element to replicate in the array. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Number of elements X | Specifies the number of elements in the array, including the original one, along the X axis. | [Integer](../../types/integer.md) | Yes | Greater than or equal to 1. |
| 3 | X spacing | Specifies the spacing between array elements along the X axis. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Number of elements Y | Specifies the number of elements in the array, including the original one, along the Y axis. | [Integer](../../types/integer.md) | Yes | Greater than or equal to 1. |
| 5 | Y spacing | Specifies the spacing between array elements along the Y axis. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 6 | Perimeter elements only | Specifies whether to draw only the perimeter elements of the array. | [Boolean](../../types/boolean.md) | Yes | See [Boolean](../../types/boolean.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 |
|---|---|---|---|---|---|---|
| ^^ARRR | C26 | 4 | 100 | 6 | 50 | 1 |

## Notes

- See [Array source](../../definitions/arr_src.md) for additional information about the `Source` parameter.

## Minimum version

1.0.3019.0
