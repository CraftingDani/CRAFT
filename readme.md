# CRAFT Programming language
by CraftingDani



## Keywords:
    fun
    const
    let
    if
    else
    typeof
    for
    while
    break
    return
    try
    catch
    new
    extends
    this
    super
    static
    null
    throw
    import
    export


## Syntax
### declare variable
    const <name> = <value>
    or
    let <name> = <value>
    
### define function
    fun <name>
    {
        <logic>
    }
    
    with parameters:
    fun <name>: <params>
    {
        <logic>
    }
    
### call function
    <name>! <opt. args>
    
### define class
    class <Name>(<inputs like constructor>) optional: extends <Class>
    {
        <variables>, <methods>
    }
### condi
tions
    if <condition>
    {
        <logic>
    }
    
### return statements
    return <value>
    or
    return! <value>


## Types
### primitive types
    boolean: true/false
    number: positive & negative numbers, floats, range: -(2^53 - 1) to 2^53 - 1
    char: alphabetic character
    string: list/array of characters max. length: 25^3 - 1 char(s)
### data structures
    array: array of primitive types, objects, other arrays
    object: key & value pairs, can contain primitive types, arrays, other objects  (like JSON)
### other
    function: function


## Operators
    +
    -
    *
    /
    .


## Standard Library Content
    print()
    data types & structures above
