# Introduction
LangChain is a open-source library that helps developers bridge the gap between traditional software and LLMs. It allows developers to support any number of different LLMs and provides over 500 intergrations to different language models, vector stores, and tools, as well as supporting memory chains and agents.

# OpenAI Function Calling
1. OpenAI has fine-tuned the gpt-3.5-turbo-0613 and gpt-4-0613 models to:
   + Accept additional arguments through which users can pass in descriptions of functions.
   + If it is relevant, return the name of the function to use, along with a JSON object with the appropriate input parameters.
