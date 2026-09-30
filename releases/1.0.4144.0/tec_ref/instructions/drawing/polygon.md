# ^^POLYGON

Draws a polygon.

## Category

Drawing instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Pen | Specifies the identifier of the pen used to draw the polygon outline. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Brush | Specifies the identifier of the brush used to fill the polygon interior. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 3 | Center X | Specifies the X coordinate of the polygon center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Center Y | Specifies the Y coordinate of the polygon center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | Number of sides | Specifies the number of polygon sides. | [Integer](../../types/integer.md) | Yes | Greater than or equal to 3. |
| 6 | Diameter | Specifies the polygon diameter. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 7 | Placement | Specifies whether the polygon is [i]nside or [e]xternal to the diameter. | [Text](../../types/text.md) | Yes | `i` or `e`. |
| 8 | Top side | Specifies whether the polygon should be drawn with a side facing upward. | [Boolean](../../types/boolean.md) | Yes | See [Boolean](../../types/boolean.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 | Param 7 | Param 8 |
|---|---|---|---|---|---|---|---|---|
| ^^POLYGON | MyPen | MyBrush | 100 | 150 | 6 | 300 | e | 1 |

## Minimum version

1.0.3019.0
