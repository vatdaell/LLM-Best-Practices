# 1 - Zero Shot Prompting
Zero shot prompting is a technique where you provide an LLM with a prompt without any context and get a response back. You do not need to provide any examples or contextual information, this is great for simple tasks or when you do not have the data available to feed into the LLM.

Prompt:
```
Rate the sentence sentiment as positive or negative text, only reply with positive or negative: I cannot believe that the actors agreed to do this "film". Sentiment:
```

Response:
```
Negative
```

As seen in the prompt, we did not provide any additional details to the prompt and the LLM since we are leveraging the LLM's training to provide us an answer.

If zero shot prompting does not give you the result, you should try to use one-shot or few shot prompting as discussed in the [next section](2%20-%20One%20and%20Few%20Shot%20Prompting.md). 