# File Paths

Defines how file paths must be specified.

## Category

Definitions

## Content

Instruction parameters that require a file path must be specified according to the following rules:
- The only supported path types are local paths (e.g. `C:\MyFolder\MyFile.xlsx`) or UNC paths (e.g. `\\MyShared\MyFolder\MyFile.xlsx`).
- File paths may be specified using either a full path or a relative path.

## Notes

Relative paths are supported only for Parent and Referenced files that are not stored in directories managed by OneDrive or SharePoint.

## Minimum version

1.0.3183.0