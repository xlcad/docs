# ^^ARC

Draws an arc.

## Category

Drawing instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Pen | Specifies the identifier of the pen used to draw the arc. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Center X | Specifies the X coordinate of the arc center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 3 | Center Y | Specifies the Y coordinate of the arc center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Radius X | Specifies the arc radius along the X axis. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | Radius Y | Specifies the arc radius along the Y axis. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 6 | Start angle | Specifies the start angle of the arc. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 7 | End angle | Specifies the end angle of the arc. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 | Param 7 |
|---|---|---|---|---|---|---|---|
| ^^ARC | MyPen | 100 | 100 | 400 | 300 | 90 | 180 |

## Notes

- See [Angles](../../definitions/angles.md) for additional information about the `Start angle` and `End angle` parameters.

## Minimum version

1.0.3019.0
