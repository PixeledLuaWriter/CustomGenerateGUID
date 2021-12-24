# CustomGenerateGUID
GenerateGUID is a custom made version of **Roblox's** internal one, it has every functionality of it re-created in Lua

```
    GenerateGUID: Function => wrapInCurlyBrackets: boolean => true or false or unset => returns Computed GUID
```

# How To Use

When calling the function you can do 3 things

Using `GenerateGUID()` without setting `wrapInCurlyBrackets` or setting `wrapInCurlyBrackets` to `true` returns this (Example with X's)

```lua
{XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX}
```

Using the function with the boolean set to `false` returns this (Example With X's)

```lua
XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX
```