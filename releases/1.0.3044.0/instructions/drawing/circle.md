# ^^CIRCLE

Draws a circle.

## Category

Drawing instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Pen | Specifies the identifier of the pen used to draw the circle outline. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Brush | Specifies the identifier of the brush used to fill the circle interior. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 3 | Center X | Specifies the X coordinate of the circle center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Center Y | Specifies the Y coordinate of the circle center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | Radius | Specifies the circle radius. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 |
|---|---|---|---|---|---|
| ^^CIRCLE | MyPen | MyBrush | 100 | 150 | 60 |

## Minimum version

1.0.3019.0
