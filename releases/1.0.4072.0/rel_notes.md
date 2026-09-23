# Release notes

## News

1. Added the new [`^^CLSPOLYL`](tec_ref/instructions/drawing/clspolyl.md) instruction for drawing closed polylines.
2. Added new values to the [`Brush style`](tec_ref/enumerations/brush_style.md) enumeration.

## Issues Fixed

1. Fixed an issue that affected [array](tec_ref/instructions/arrays/README.md) rendering in referenced worksheets.

## Improvements

1. Added validation to prevent the same value for the `Name` parameter from being used for [`^^IMG`](tec_ref/instructions/resources/img.md) and [`^^REF`](tec_ref/instructions/resources/ref.md) instructions within the same worksheet or across referenced worksheets.