# COBOL REDEFINES Bug
This example demonstrates a potential issue with the REDEFINES clause in COBOL when used with both numeric and alphanumeric fields.  The program appears to correctly move a value to WS-FIELD-1, but displaying WS-AREA-1 reveals unexpected results due to the way REDEFINES handles memory allocation and data types.