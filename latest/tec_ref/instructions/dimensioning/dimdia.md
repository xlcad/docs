# ^^DIMDIA

Draws a diameter dimension.

## Category

Dimensioning instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Style | Specifies the identifier of the dimension style used to draw the dimension. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Center X | Specifies the X coordinate of the measured object center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 3 | Center Y | Specifies the Y coordinate of the measured object center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Diameter | Specifies the measured object diameter. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | Dimension line X | Specifies the X coordinate of the dimension line position. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 6 | Dimension line Y | Specifies the Y coordinate of the dimension line position. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 7 | Text | Specifies the text displayed by the dimension. | [Text](../../types/text.md) | No | See [Text](../../types/text.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 | Param 7 |
|---|---|---|---|---|---|---|---|
| ^^DIMDIA | MyDimStyle | 100 | 100 | 65 | 300 | 300 | <> mm |

## Notes

- See [Dimension displayed text](../../definitions/dim_disp_text.md) for additional information about the `Text` parameter.

## Minimum version

1.0.3019.0
