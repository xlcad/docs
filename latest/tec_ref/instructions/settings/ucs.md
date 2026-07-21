# ^^UCS

Defines the user coordinate system (UCS).

## Category

Drawing settings

## Parameters

| Ordinal | Name | Description | Type | Required | Allowed values |
|---|---|---|---|---|---|
| 1 | X axis | Defines the `X` axis direction. | [Integer](../../types/integer.md) | Yes | See [X axis](../../enumerations/axis_x.md) allowed values. |
| 2 | Y axis | Defines the `Y` axis direction. | [Integer](../../types/integer.md) | Yes | See [Y axis](../../enumerations/axis_y.md) allowed values. |

## Example

| Instruction | Param 1 | Param 2 |
|---|---|---|
| ^^UCS | 1 | -1 |

## Notes

- This instruction is subject to the rules of the [Drawing Settings Instructions](../../definitions/drw_stg_instr.md).
- See [Angles](../../definitions/angles.md) for additional information about angle orientation and rotation direction.

## Minimum version

1.0.3019.0
