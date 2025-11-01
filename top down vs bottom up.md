| Top Down Parser        | Bottom Up Parser     |
|------------------------|----------------------|
|1. Parses string from symbol to input string. | 1.Parses or reduces from input string to non-terminal. |
|2. Expands productions. | 2. Reduces i/p to non-terminals. |
|3. Follows LMD. | 3. Follows RMD in reverse. |
|4. Top down parsers cannot handle left recursion. | 4. Bottom up parsers can handle left recursion. |
|5. Eg: Recursive desent parser | 5. Eg: Shift Reduce parsers. |
|6. This parser works with simple words. |6. This parser works with more general grammars. |

