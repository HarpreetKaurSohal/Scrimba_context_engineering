For generateSummary(), we need to ask the AI to create a summary of messagesToSummarize.

We need to add a message requesting the summary.

AI SDK Message object docs: https://scrimba.com/ai-sdk-message-docs
AI SDK Generating Text docs: https://scrimba.com/ai-sdk-generating-text

What role should that message have - "user", "assistant", or "system"?

* `"system"` is for high-level instructions.
* `"assistant"` is for the AI's *own* responses.
* `"user"` is for *requests* made to the AI.