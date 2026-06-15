# ^^RECT

Draws a rectangle.

## Category

Drawing instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Pen | Specifies the identifier of the pen used to draw the rectangle outline. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Brush | Specifies the identifier of the brush used to fill the rectangle interior. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 3 | Center X | Specifies the X coordinate of the rectangle center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Center Y | Specifies the Y coordinate of the rectangle center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | Width | Specifies the rectangle width. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 6 | Height | Specifies the rectangle height. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 |
|---|---|---|---|---|---|---|
| ^^RECT | MyPen | MyBrush | 100 | 150 | 60 | 30 |

## Minimum version

1.0.3019.0
