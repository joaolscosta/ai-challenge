### Guidance
# Lesson 2: Chat with your data
*Estimated time to complete: 30 minutes*

## What is Fabio's dog's name?
What was the model's answer? Probably it wasn't "Nikita" which would have been the correct answer.

Do you know why? Because the model has no knowledge about Fabio or his dog. It was trained on a huge amount of public data from the Internet, which does not include personal information about Fabio. So how do we provide the model with such knowledge?

## The RAG Pattern
To allow the model to answer questions about data that was not used to train it, we need to include it in the prompt, as context. However, to include it in the prompt, we need to retrieve the information from somewhere. The Retrieval Augmented Generation (RAG) pattern is used to solve this.

## To Do
- [ ] 

Done? [Next Lesson](/guidance/guidance-lesson3.md)<br>
Want to go back? [Previous Lesson](/guidance/guidance-lesson1.md)