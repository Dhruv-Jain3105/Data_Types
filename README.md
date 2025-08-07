# Experiment 2 - Data_Types
## Aim: To study and implement C++ Program Structure (Data Types)

## Software used : VS Code

## Theory :
There are many types of data types in C++ like Integer(int), Float(float), String(string), Boolean(bool), Character(char), etc. These are stored in memory space in there respective bits space. These data types storage can be changed by using various storage classes like automatic(auto), register(register), static(static), external(extern) and mutable(mutable).
Automatic :
Keyword: auto
Storage: RAM (stack)
Scope: Local to the block/function where it is defined.
Lifetime: Till the block/function executes; destroyed when the function ends.
Default Initial Value: Garbage
Task: Used for temporary storage inside functions.
Register :
Keyword: register
Storage: CPU register (if available, else stored in RAM but optimized).
Scope: Local to the block/function.
Lifetime: Till the block/function executes.
Default Initial Value: Garbage
Task: Used for fast access variables, e.g., counters in loops.
Note: You cannot take its address using &.
Static :
Keyword: static
Storage: RAM (static storage area)
Scope:
Local static → Visible only in that block.
Global static → Visible only in that file.
Lifetime: Till program ends (value persists between function calls).
Default Initial Value: Zero (0) for numeric, NULL for pointers.
Task: Used to retain value between function calls or restrict global variable access to a single file.
External :
Keyword: exten
Storage: RAM (global area)
Scope: Global (accessible across files).
Default Initial Value: Zero (0) for numeric, NULL for pointers.
Task: Used to declare global variables/functions that can be shared across multiple files.
Mutable :
Keyword: mutable
Storage: Same as normal member variables.
Scope: Class scope.
Lifetime: Till object exists.
Task: Allows modification of class member variables even if the object is declared as const.

## Conclusion :
I learnt about various data types and how to store them using various storage classes.
