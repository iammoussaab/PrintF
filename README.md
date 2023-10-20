#PrintF
# C printf Function Implementation

This project involves implementing a custom `printf` function in C, with various features and conversion specifiers.

| Task  | Description                                                                  | Mandatory/Advanced |
|------ |------------------------------------------------------------------------------ |-------------------- |
| 0     | Implement basic printf function for `%c`, `%s`, and `%%`.                     | Mandatory           | 
| 1     | Handle numeric conversion specifiers: `%d` and `%i`.                          | Mandatory           | 
| 2     | Implement custom conversion specifier `%b` (binary).                         | Advanced            | 
| 3     | Handle numeric conversion specifiers: `%u`, `%o`, `%x`, and `%X`.            | Advanced            | 
| 4     | Use a local buffer to minimize `write` calls (buffer size: 1024 chars).       | Advanced            | 
| 5     | Implement custom conversion specifier `%S` (string with non-printable chars). | Advanced            | 
| 6     | Handle the `%p` conversion specifier.                                        | Advanced            | 
| 7     | Handle flag characters: `+`, space, and `#` for non-custom specifiers.       | Advanced            | 
| 8     | Handle length modifiers `l` and `h` for numeric specifiers.                  | Advanced            | 
| 9     | Handle field width for non-custom specifiers.                               | Advanced            | 
| 10    | Handle precision for non-custom specifiers.                                  | Advanced            | 
| 11    | Handle the "0" flag character for non-custom specifiers.                    | Advanced            |
| 12    | Handle the "-" flag character for non-custom specifiers.                    | Advanced            |
| 13    | Implement custom conversion specifier `%r` (reversed string).               | Advanced            |
| 14    | Implement custom conversion specifier `%R` (rot13'ed string).               | Advanced            |
| 15    | Ensure all options and functionalities work well together.                  | Advanced            |

For details on each task and associated code, please refer to the corresponding GitHub repository linked in the table.

## Usage

To use the custom printf function, include the appropriate header and call `_printf` with the desired format and arguments. The function returns the number of characters printed.

