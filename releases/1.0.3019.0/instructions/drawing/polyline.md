# ^^POLYLINE

Draws a polyline.

## Category

Drawing instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Pen | Specifies the identifier of the pen used to draw the polyline. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | X | Specifies the X coordinate of a polyline point. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 3 | Y | Specifies the Y coordinate of a polyline point. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | X | Specifies the X coordinate of a polyline point. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | Y | Specifies the Y coordinate of a polyline point. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 6 | Xn | Specifies the X coordinate of an additional polyline point. | [Decimal](../../types/decimal.md) | No | See [Decimal](../../types/decimal.md) allowed values. |
| 7 | Yn | Specifies the Y coordinate of an additional polyline point. | [Decimal](../../types/decimal.md) | No | See [Decimal](../../types/decimal.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 | Param 7 |
|---|---|---|---|---|---|---|---|
| ^^POLYLINE | MyPen | 100 | 150 | 300 | 150 | 500 | 350 |

## Notes

- At least two points are required to draw a polyline.
- All parameters after the fifth must define, in sequence, the `X` and `Y` coordinates of the next polyline point.

## Minimum version

1.0.3019.0
