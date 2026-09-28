In splitForSummary(), we need to split messages into two groups based on a tokenTarget.

The most recent messages are usually the most relevant, so we want to keep those and summarize the older ones.

Your goal is to find the "split point" that separates the old from the new.
