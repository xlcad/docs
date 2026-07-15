# ^^TEXTSTYLE

Defines a reusable text style for drawing instructions.

## Category

Drawing resources

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Name | Specifies the text style identifier. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Font | Specifies the font name to use. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 3 | Height | Specifies the text height in points. | [Integer](../../types/integer.md) | Yes | See [Integer](../../types/integer.md) allowed values. |
| 4 | Bold | Specifies whether the text style is bold. | [Boolean](../../types/boolean.md) | Yes | See [Boolean](../../types/boolean.md) allowed values. |
| 5 | Italic | Specifies whether the text style is italic. | [Boolean](../../types/boolean.md) | Yes | See [Boolean](../../types/boolean.md) allowed values. |
| 6 | Underline | Specifies whether the text style is underlined. | [Boolean](../../types/boolean.md) | Yes | See [Boolean](../../types/boolean.md) allowed values. |
| 7 | Strikeout | Specifies whether the text style is struck through. | [Boolean](../../types/boolean.md) | Yes | See [Boolean](../../types/boolean.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 | Param 7 |
|---|---|---|---|---|---|---|---|
| ^^TEXTSTYLE | MyTextStyle | Arial | 12 | 1 | 0 | 0 | 0 |

## Notes

- This instruction is subject to the rules of the [Instructions Hierarchy](../../definitions/instr_hier.md).
- The `Font` parameter may be obtained using the XL CAD feature `Parameters > Available fonts`.

## Minimum version

1.0.3019.0
