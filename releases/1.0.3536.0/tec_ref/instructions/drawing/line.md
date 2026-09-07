# ^^LINE

Draws a line.

## Category

Drawing instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Pen | Specifies the identifier of the pen used to draw the line. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | X1 | Specifies the X coordinate of the line start point. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 3 | Y1 | Specifies the Y coordinate of the line start point. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | X2 | Specifies the X coordinate of the line end point. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | Y2 | Specifies the Y coordinate of the line end point. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 |
|---|---|---|---|---|---|
| ^^LINE | MyPen | 100 | 150 | 300 | 150 |

## Minimum version

1.0.3019.0
