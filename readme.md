# CRAFT Programming language
by CraftingDani



## Keywords:
    fun
    const
    let
    if
    else


## Syntax
### declare variable
    const <name> = <value>
    or
    let <name> = <value>
### define function
    fun <name>(<params>)
    {
        <logic>
        optional: return <>
    }
### call function
    <name>(<args>)
### define class
    class <Name>(<inputs like constructor>) optional: extends <Class>
    {
        <variables>, <methods>
    }
### conditions
    if(<condition>)
    {
        <logic executed if condition == true>
    }


## Types
### primitive types
    boolean: true/false
    number: positive & negative numbers, floats, range: -(2^53 - 1) to 2^53 - 1
    char: alphabetic character
    string: list/array of characters
    
### data structures
    array: array of types above
    object: key & value pairs, can contain primitive types, arrays, other objects  (like JSON)
