1. String Indexing
Every character in a Python string is assigned a unique index number.

Positive Indexing: Starts from 0 at the beginning of the string. Computers use 0-based indexing because they operate on binary systems.

Negative Indexing: Starts from -1 at the end of the string (reverse indexing).

2. String Slicing
Slicing allows you to extract a sub-string from a larger string.

General Format: string[start : end : step].

End Index Rule: The character at the end index is excluded from the result.

3. Using the Step Value
The "step" determines how many characters the pointer jumps.

Step 2: string[0:6:2] results in 'Pto' by skipping every second character.

Default Slicing: Leaving the indices empty (e.g., string[:]) selects the entire string from start to finish.

4. Reversing a String
A common Python trick to reverse a string is using a negative step of -1.