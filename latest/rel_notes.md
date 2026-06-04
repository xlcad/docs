# Release Notes

## News

1. Added access to the online documentation through `Application > Documentation`.
2. Added new settings to control the formatting of cells automatically populated with instructions through ribbon commands.

## Improvements

1. In previous versions, the `Scale` parameter of the `^^DRAWREF` instruction accepted only values greater than 0. In the current version, non-zero values are accepted.
2. In previous versions, the `File` parameter of the `^^REF` instruction accepted only full file paths. In the current version, both full and relative file paths are accepted.

## Issues Fixed

1. In previous versions, the `Thickness` parameter of the `^^PEN` instruction accepted values in the range 1 to 16777215. In the current version, values in the range 1 to 256 are accepted.