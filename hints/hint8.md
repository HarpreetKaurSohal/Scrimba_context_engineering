You have your `messages` array and your new `summaryPrompt` object. You need to combine them into one array to send to the AI.

You *could* use `messages.push(summaryPrompt)`, but this **difies the original array which can sometimes cause bugs.

A safer, cleaner way is to create a brand new array. 

The spread operator (`...`) is perfect for this.