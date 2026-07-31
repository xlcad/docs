# ^^DIMANG

Draws an angular dimension.

## Category

Dimensioning instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Style | Specifies the identifier of the dimension style used to draw the dimension. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Intersection X | Specifies the X coordinate of the intersection point of the two lines defining the angle. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 3 | Intersection Y | Specifies the Y coordinate of the intersection point of the two lines defining the angle. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | First point X | Specifies the X coordinate of the point on the first line opposite the intersection. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | First point Y | Specifies the Y coordinate of the point on the first line opposite the intersection. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 6 | Second point X | Specifies the X coordinate of the point on the second line opposite the intersection. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 7 | Second point Y | Specifies the Y coordinate of the point on the second line opposite the intersection. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 8 | Dimension line X | Specifies the X coordinate of the dimension line position. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 9 | Dimension line Y | Specifies the Y coordinate of the dimension line position. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 10 | Text | Specifies the text displayed by the dimension. | [Text](../../types/text.md) | No | See [Text](../../types/text.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 | Param 7 | Param 8 | Param 9 | Param 10 |
|---|---|---|---|---|---|---|---|---|---|---|
| ^^DIMANG | MyDimStyle | 100 | 100 | 300 | 100 | 300 | 300 | 250 | 250 |  |

## Notes

- See [Dimension displayed text](../../definitions/dim_disp_text.md) for additional information about the `Text` parameter.

## Minimum version

1.0.3019.0
