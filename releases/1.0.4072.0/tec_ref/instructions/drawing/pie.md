# ^^PIE

Draws a pie shape.

## Category

Drawing instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Pen | Specifies the identifier of the pen used to draw the pie shape. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Brush | Specifies the identifier of the brush used to fill the pie interior. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 3 | Center X | Specifies the X coordinate of the pie center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Center Y | Specifies the Y coordinate of the pie center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | Radius X | Specifies the pie radius along the X axis. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 6 | Radius Y | Specifies the pie radius along the Y axis. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 7 | Start angle | Specifies the start angle of the pie shape. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 8 | End angle | Specifies the end angle of the pie shape. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 | Param 7 | Param 8 |
|---|---|---|---|---|---|---|---|---|
| ^^PIE | MyPen | MyBrush | 100 | 100 | 400 | 300 | 90 | 180 |

## Notes

- See [Angles](../../definitions/angles.md) for additional information about the `Start angle` and `End angle` parameters.

## Minimum version

1.0.3019.0
