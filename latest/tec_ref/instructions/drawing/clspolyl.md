# ^^CLSPOLYL

Draws a closed polyline.

## Category

Drawing instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Pen | Specifies the identifier of the pen used to draw the closed polyline. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Brush | Specifies the identifier of the brush used to fill the interior of the closed polyline. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 3 | X | Specifies the X coordinate of a point of the closed polyline. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Y | Specifies the Y coordinate of a point of the closed polyline. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | X | Specifies the X coordinate of a point of the closed polyline. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 6 | Y | Specifies the Y coordinate of a point of the closed polyline. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 7 | X | Specifies the X coordinate of a point of the closed polyline. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 8 | Y | Specifies the Y coordinate of a point of the closed polyline. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 9 | Xn | Specifies the X coordinate of an additional point of the closed polyline. | [Decimal](../../types/decimal.md) | No | See [Decimal](../../types/decimal.md) allowed values. |
| 10 | Yn | Specifies the Y coordinate of an additional point of the closed polyline. | [Decimal](../../types/decimal.md) | No | See [Decimal](../../types/decimal.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 | Param 7 | Param 8 |
|---|---|---|---|---|---|---|---|---|
| ^^CLSPOLYL | MyPen | MyBrush | 100 | 150 | 300 | 150 | 500 | 350 |

## Notes

- At least three points are required to draw a closed polyline.
- If the first and last points are different, the polyline is automatically closed.
- All parameters after the eighth must define, in sequence, the `X` and `Y` coordinates of each additional point of the closed polyline.

## Minimum version

1.0.4072.0