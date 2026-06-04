# ^^DIMAL

Draws an aligned dimension.

## Category

Dimensioning instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Style | Specifies the identifier of the dimension style used to draw the dimension. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | First point X | Specifies the X coordinate of the first point measured by the dimension. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 3 | First point Y | Specifies the Y coordinate of the first point measured by the dimension. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Second point X | Specifies the X coordinate of the second point measured by the dimension. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | Second point Y | Specifies the Y coordinate of the second point measured by the dimension. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 6 | Dimension line X | Specifies the X coordinate of the dimension line position. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 7 | Dimension line Y | Specifies the Y coordinate of the dimension line position. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 8 | Text | Specifies the text displayed by the dimension. | [Text](../../types/text.md) | No | See [Text](../../types/text.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 | Param 7 | Param 8 |
|---|---|---|---|---|---|---|---|---|
| ^^DIMAL | MyDimStyle | 100 | 100 | 500 | 100 | 300 | 150 | <> mm |

## Notes

- See [Dimension Displayed Text](../../definitions/dim_disp_text.md) for additional information about the `Text` parameter.

## Minimum version

1.0.3019.0
