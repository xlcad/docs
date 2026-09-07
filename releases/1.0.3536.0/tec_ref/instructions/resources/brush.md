# ^^BRUSH

Defines a reusable brush for drawing instructions.

## Category

Drawing resources

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Name | Specifies the brush identifier. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Color | Specifies the brush color. | [Integer](../../types/integer.md) | Yes | -1 to 16777215 |
| 3 | Style | Specifies the Brush style. | [Integer](../../types/integer.md) | Yes | See [Brush style](../../enumerations/brush_style.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 |
|---|---|---|---|
| ^^BRUSH | MyBrush | 255 | 5 |

## Notes

- This instruction is subject to the rules of the [Instructions Hierarchy](../../definitions/instr_hier.md).
- See [Colors](../../definitions/colors.md) for additional information about the `Color` parameter.

## Minimum version

1.0.3019.0
