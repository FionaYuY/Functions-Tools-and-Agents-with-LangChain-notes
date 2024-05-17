# Introduction
LangChain is a open-source library that helps developers bridge the gap between traditional software and LLMs. It allows developers to support any number of different LLMs and provides over 500 intergrations to different language models, vector stores, and tools, as well as supporting memory chains and agents.

# OpenAI Function Calling
1. OpenAI has fine-tuned the gpt-3.5-turbo-0613 and gpt-4-0613 models to:
   + Accept additional arguments through which users can pass in descriptions of functions.
   + If it is relevant, return the name of the function to use, along with a JSON object with the appropriate input parameters.

# LangChain Expression Language (LCEL)
1. LangChain composes chains of components
2. LCEL and the runnable protocol define:
   + An allowed set of input types and output types
   + Required methods: invoke, stream, batch...
   + Means of modifying parameters at runtime: bind,...
3. Composition can now use the Linux pipe syntax: Chain = prompt | llm | OutputParser

![image](https://github.com/FionaYuY/Functions-Tools-and-Agents-with-LangChain-notes/assets/151610467/6ff0e675-279e-47cc-8d65-accd8923aaf0)

4. Interface

![image](https://github.com/FionaYuY/Functions-Tools-and-Agents-with-LangChain-notes/assets/151610467/a64e9eb3-452a-42b3-90df-aaa99d81f17c)

5. Why use LCEL?

![image](https://github.com/FionaYuY/Functions-Tools-and-Agents-with-LangChain-notes/assets/151610467/2250640a-6db4-4b3f-a347-7eb4b5d2323d)
