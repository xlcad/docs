# ^^REF

Defines a reference to an Excel worksheet containing reusable drawing instructions.

## Category

Drawing resources

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | Name | Specifies the reference identifier. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 2 | File | Specify the path (full or relative) of the file containing the reference Excel worksheet. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 3 | Sheet | Specifies the name of the referenced Excel worksheet. | [Text](../../types/text.md) | Yes | See [Text](../../types/text.md) allowed values. |
| 4 | Password | Specifies the password of the file containing the referenced Excel worksheet, if required. | [Text](../../types/text.md) | No | See [Text](../../types/text.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 | Param 3 | Param 4 |
|---|---|---|---|---|
| ^^REF | MyRef | C:\MyFile.xlsx | MyWorksheet | MyPassword |

## Notes

- This instruction is subject to the rules of the [Instructions Hierarchy](../../definitions/instr_hier.md).
- Relative paths for the `File` parameter are supported only for files that are not stored in directories managed by OneDrive or SharePoint.

## Minimum version

1.0.3183.0