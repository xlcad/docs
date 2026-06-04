# ^^PEN

Defines a reusable pen for drawing instructions.

## Category

Drawing resources

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Name | Specifies the pen identifier. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Style | Specifies the pen style. | [Integer](../../types/integer.md) | Yes | See [Pen Style](../../enumerations/pen_style.md) allowed values. |
| 3 | Thickness | Specifies the pen thickness. | [Integer](../../types/integer.md) | Yes | 1 to 256 |
| 4 | Color | Specifies the pen color. | [Integer](../../types/integer.md) | Yes | -1 to 16777215 |
| 5 | Scale factor | Specifies the scale factor applied to the pen style. | [Integer](../../types/integer.md) | Yes | 1 to 16777215 |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 |
|---|---|---|---|---|---|
| ^^PEN | MyPen | 1 | 2 | 255 | 10 |

## Notes

- This instruction is subject to the rules of the [Instructions Hierarchy](../../definitions/instr_hier.md).
- Pen thickness is expressed in pixels.
- See [Colors](../../definitions/colors.md) for additional information about the `Color` parameter.

## Minimum version

1.0.3044.0
