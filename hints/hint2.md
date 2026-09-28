Your 'messages' array (BEFORE):

[ M1, M2, M3, M4, M5, M6, M7 ]
(Oldest)           (Newest)

Your 'tokenTarget' = 1000 tokens
(Let's pretend M5, M6, and M7 together are 950 tokens)

Your function's output (AFTER):

messagesToSummarize: [ M1, M2, M3, M4 ]
remainingMessages:   [ M5, M6, M7 ]
(Their total tokens <= 1000)

The key question is: **How do you find the index** (in this example, right after M4) to make this split?