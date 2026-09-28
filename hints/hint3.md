There are two excellent ways to find this point. Both are correct!

Strategy 1: Add from the End

Loop backwards from the end of the `messages` array. 

Keep a running total of tokens, adding each message's count. 

The moment you're about to go over the `tokenTarget`, you've found your split point.

[ M1 | M2 | M3 | M4 | M5 | M6 | M7 ]
<--  <--  <-- (Adding tokens)

-----------

Strategy 2: Subtract from the Start

Get the total token count of all messages (using `getTotalTokenCount`). 

Loop forwards from the start of the array. 

Keep subtracting each message's token count from your total.

When your total is finally under the `tokenTarget`, you've found your split point.

[ M1 | M2 | M3 | M4 | M5 | M6 | M7 ]
-->  -->  --> (Subtracting tokens from total)