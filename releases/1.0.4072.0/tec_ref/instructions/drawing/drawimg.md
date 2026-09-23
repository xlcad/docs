# ^^DRAWIMG

Draws a previously defined image.

## Category

Drawing instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Image | Specifies the identifier of the image to draw. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | X | Specifies the X coordinate of the image center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 3 | Y | Specifies the Y coordinate of the image center. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Scale | Specifies the scale factor applied to the image. | [Decimal](../../types/decimal.md) | Yes | Not equal to 0. |
| 5 | Rotation | Specifies the image rotation in degrees. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 |
|---|---|---|---|---|---|
| ^^DRAWIMG | MyImg | 100 | 150 | 0.75 | 0 |

## Notes

- See [Angles](../../definitions/angles.md) for additional information about the `Rotation` parameter.

## Minimum version

1.0.3309.0
