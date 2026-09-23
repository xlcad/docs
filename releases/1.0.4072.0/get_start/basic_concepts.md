# Basic concepts

Instructions are the fundamental building blocks of XL CAD.

An instruction is a declaration composed of a name followed by one or more parameters. The number of parameters depends on the specific instruction.

Another key concept of XL CAD is the way instruction parameters are defined.

Parameters can be specified either as constant values or as dynamic values.
Constant values are entered directly into worksheet cells.
Dynamic values are defined using Excel formulas or references to other cells, allowing drawings to automatically adapt to changes in the underlying spreadsheet data without modifying the instructions themselves.

Instruction elements are written in worksheet cells according to the following rules:

- All elements of an instruction must be written on the same row.
- Each element must be written in a single cell.
- Elements must be arranged from left to right in adjacent cells.

The following example shows three instructions and the use of both constant and dynamic values. The example is stored starting from cell A1, but instructions can be placed anywhere in the worksheet.

| | A | B | C | D | E | F |
| --- | --- | --- | --- | --- | --- | --- |
| **1** | [^^PEN](../tec_ref/instructions/resources/pen.md) | `MyPen` | `1` | `2` | `255` | `10` | |
| **2** | [^^BRUSH](../tec_ref/instructions/resources/brush.md) | `MyBrush` | `255` | `5` | | |
| **3** | [^^CIRCLE](../tec_ref/instructions/drawing/circle.md) | `=B1` | `=B2` | `100` | `150` | `60` |

Instructions can be entered manually, provided they comply with the required syntax. However, this approach is strongly discouraged.

Instead, it is recommended to use the features provided by the XL CAD user interface to insert instructions. In addition to ensuring that instructions are created correctly, the user interface automatically adds a technical comment to each cell containing information about the corresponding parameter.

Instructions are organized into the following categories according to their purpose.

1. [Drawing settings](../tec_ref/instructions/settings/README.md)  
   Define the drawing settings. These instructions are optional. If omitted, the application-wide settings are used.

2. [Drawing resources](../tec_ref/instructions/resources/README.md)  
   Define reusable resources such as pens, brushes, text styles, etc.

3. [Drawing instructions](../tec_ref/instructions/drawing/README.md)  
   Draw 2D primitives, images, and drawing content stored in other spreadsheet models.

4. [Array instructions](../tec_ref/instructions/arrays/README.md)  
   Replicate drawing instructions using different array layouts.

5. [Dimensioning instructions](../tec_ref/instructions/dimensioning/README.md)  
   Draw different types of dimensions.

During drawing generation, XL CAD processes instructions according to the [Instructions hierarchy](../tec_ref/definitions/instr_hier.md) and the [Instructions processing order](../tec_ref/definitions/instr_proc_ord.md).