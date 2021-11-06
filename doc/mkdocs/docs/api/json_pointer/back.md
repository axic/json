# json_pointer::back

```cpp
const std::string& back() const;
```

Return last reference token.

## Return value

Last reference token.

## Exceptions

Throws [out_of_range.405](../../home/exceptions.md#jsonexceptionout_of_range405) if JSON pointer has no parent.

## Complexity

Constant.

## Examples

??? example

    The example shows the usage of `back`.
     
    ```cpp
    --8<-- "examples/json_pointer__back.cpp"
    ```
    
    Output:
    
    ```json
    --8<-- "examples/json_pointer__back.output"
    ```

## Version history

Added in version 3.6.0.