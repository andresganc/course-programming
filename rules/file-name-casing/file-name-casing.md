
# Rule: file-name-casing

## Enforces a consistent file naming convention

-   Rationale
    Helps maintain a consistent style across a file hierarchy

    

    camel-case: File names must be camel-cased: fileName.ts.
    pascal-case: File names must be Pascal-cased: FileName.ts.
    kebab-case: File names must be kebab-cased: file-name.ts.
    snake-case: File names must be snake-cased: file_name.ts.


    
    ignore: File names are ignored (useful for the object configuration).
    Or an object, where the key represents a regular expression that matches the file name, and the value is the file name rule from the previous list.

    Config
    One of the following arguments must be provided: