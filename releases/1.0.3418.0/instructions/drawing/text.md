# ^^TEXT

Draws text.

## Category

Drawing instructions

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Style | Specifies the identifier of the text style used to draw the text. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | Color | Specifies the text color. | [Integer](../../types/integer.md) | Yes | 0 to 16777215 |
| 3 | X | Specifies the X coordinate of the text insertion point. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 4 | Y | Specifies the Y coordinate of the text insertion point. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 5 | Alignment | Specifies the text alignment. | [Integer](../../types/integer.md) | Yes | See [Text Alignment](../../enumerations/text_align.md) allowed values. |
| 6 | Rotation | Specifies the text rotation in degrees. | [Decimal](../../types/decimal.md) | Yes | See [Decimal](../../types/decimal.md) allowed values. |
| 7 | Text | Specifies the text to draw. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 | Param 5 | Param 6 | Param 7 |
|---|---|---|---|---|---|---|---|
| ^^TEXT | MyTextStyle | 255 | 100 | 150 | 1 | 0 | Example text |

## Notes

- See [Colors](../../definitions/colors.md) for additional information about the `Color` parameter.
- See [Angles](../../definitions/angles.md) for additional information about the `Rotation` parameter.

## Minimum version

1.0.3019.0
