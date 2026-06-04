# ^^DRAWREF

Draws the contents defined in a referenced Excel worksheet.

## Category

Drawing instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Reference | Specifies the identifier of the reference to draw. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | X | Specifies the X coordinate of the point where the reference origin is positioned. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 3 | Y | Specifies the Y coordinate of the point where the reference origin is positioned. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Scale | Specifies the scale factor applied to the reference. | [Decimal](../../types/decimal.md) | Yes | Greater than 0. |
| 5 | Rotation | Specifies the reference rotation in degrees. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 6 | Cell | Specifies the address of the cell in the referenced Excel worksheet whose value should be modified. | [Text](../../types/text.md) | No | Microsoft Excel cell address |
| 7 | Value | Specifies the new value to apply to the cell in the referenced Excel worksheet. | [Any](../../types/any.md) | No | See [Any](../../types/any.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 | Param 7 |
|---|---|---|---|---|---|---|---|
| ^^DRAWREF | MyRef | 100 | 150 | 2.5 | 90 | B12 | New value |

## Notes

- See [Angles](../../definitions/angles.md) for additional information about the `Rotation` parameter.
- All parameters after the fifth must define, in sequence, the `Cell` and `Value` pairs of the referenced Excel worksheet to be modified.

## Minimum version

1.0.3019.0
