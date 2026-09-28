It should be `role: "user"` because we're asking the AI model to do something (create a summary).

Your new prompt object will look something like this:

```javascript
const summaryPrompt = {
  role: "user",
  content: "..." // What goes here?
};