# ^^DIMSTYLE

Defines a reusable dimension style for drawing instructions.

## Category

Drawing resources

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Name | Specifies the dimension style identifier. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Pen | Specifies the identifier of the pen used to draw the dimension. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 3 | Text style | Specifies the identifier of the text style used for the dimension text. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 4 | Ends | Specifies the shape of the dimension line ends. | [Integer](../../types/integer.md) | Yes | See [Dimension Ends](../../enumerations/dim_ends.md) allowed values. |
| 5 | Decimals | Specifies the number of decimals used to format the dimension value. | [Integer](../../types/integer.md) | Yes | 0 to 6 |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 |
|---|---|---|---|---|---|
| ^^DIMSTYLE | MyDimStyle | MyPen | MyTextStyle | 1 | 2 |

## Notes

- This instruction is subject to the rules of the [Instructions Hierarchy](../../definitions/instr_hier.md).
- See [Dimension Displayed Text](../../definitions/dim_disp_text.md) for additional information about dimension text formatting.

## Minimum version

1.0.3019.0
