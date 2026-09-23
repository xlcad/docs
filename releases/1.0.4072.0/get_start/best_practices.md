#  Best practices

This page describes a set of recommended best practices to help you achieve a better experience when using XL CAD.

- **Scripting**  
   For a better scripting experience and easier review of your work, it is recommended to define only one instruction per row within a dedicated cell range.
   It is also recommended to follow this order when writing instructions:
    1. [Drawing settings](../tec_ref/instructions/settings/README.md)
    2. [Drawing resources](../tec_ref/instructions/resources/README.md)
    3. [Drawing instructions](../tec_ref/instructions/drawing/README.md)
    4. [Array instructions](../tec_ref/instructions/arrays/README.md)
    5. [Dimensioning instructions](../tec_ref/instructions/dimensioning/README.md)

- **Working folders**  
  To enjoy maximum drawing generation performance and to take advantage of the flexibility of relative [File paths](../tec_ref/definitions/file_paths.md), it is recommended to work on worksheets stored in folders not managed by OneDrive or SharePoint.

- **Formula dependencies**  
  XL CAD fully supports Excel formulas and cell references. Keep in mind that spreadsheet models containing long chains of sequential formula dependencies may increase drawing generation time compared to equivalent models with shorter dependency chains.