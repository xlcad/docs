# ^^IMG

Defines a reference to a file containing a reusable image.

## Category

Drawing resources

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Name | Specifies the image identifier. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | File | Specifies the path (full or relative) of the file containing the image. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 |
|---|---|---|
| ^^IMG | MyImg | C:\MyImg.bmp |

## Notes

- This instruction is subject to the rules of the [Instructions Hierarchy](../../definitions/instr_hier.md).
- See [File Paths](../../definitions/file_paths.md) for additional information about the `File` parameter.
- See [Image Formats](../../definitions/image_formats.md) for additional information about the supported image formats.

## Minimum version

1.0.3309.0