# Langchain_Intro
Understanding of langchain
LangChain, a framework for building applications using language models. 😊

LangChain is an open-source framework designed to easily build applications using language models like GPT, LLaMA, Mistral, etc. One of the most powerful features of LangChain is its support for advanced prompt engineering. Prompt engineering refers to the design and optimization of prompts to get the most accurate and relevant responses from a language model1.

A prompt is the input provided to a language model to elicit a desired response. A good prompt typically contains instructions, example inputs, questions, and contexts that guide the model’s behavior. LangChain offers a set of tools for creating and working with prompt templates, which are structured guides to formulating queries for language models2.

A chain is a sequence of actions that can be performed on a prompt or an output. A chain can include actions such as formatting, parsing, validating, or transforming the data. LangChain provides a class called LLMChain that allows you to create chains of actions using language models3.

An agent is an entity that can execute a chain of actions and produce an output. An agent can be a single language model or a combination of multiple models and tools. LangChain provides a class called AgentExecutor that allows you to create and run agents using chains and prompt templates

## Langchain consist three import concpet to complete the task
1) Prompt remplate
2) Chains
3) Agent

# Prompt Template:
A prompt template is a way of creating prompts for language models using placeholders and input values. A prompt is the input that guides the model’s response. A prompt template can have different sections, such as instructions, context, examples, and output indicator. A prompt template can be formatted with different input values to create different prompts for different tasks or scenarios.

Why Use Prompt Templates? Prompt templates are useful when multiple inputs are needed, making code cleaner and more manageable.

![image](https://github.com/anithorat/Langchain_Intro/assets/101381417/fda21802-b5da-4847-aee0-1d18ad8ad817)


for example:
![image](https://github.com/anithorat/Langchain_Intro/assets/101381417/21b4351c-b1a4-4d9e-a761-ad65187c6ee0)

# ******Introduction to Prompt Templates in LangChain******

https://www.comet.com/site/blog/introduction-to-prompt-templates-in-langchain/


## Prompts
  Language models (LLMs) require prompts to function.




A prompt is a set of instructions or inputs to guide the model’s response. The output from a prompt can be answers, sentence completions, or conversation responses. 

A well-constructed prompt template has the following sections:
1) **Instructions**: Define the model’s response/behaviour.
2) **Context**: Provides additional information, sometimes with examples.
3) **User Input**: The actual question or input from the user.
4) **Output Indicator**: Marks the beginning of the model’s response.

## Prompt templates in LangChain
LangChain provides PromptTemplate to help create parametrized prompts for language models.

A PromptTemplate allows creating a template string with placeholders, like {adjective} or {content} that can be formatted with input values to create the final prompt string.

Some key features:

* Validation of input variables against the template
* Flexible input values — can pass dictionaries, data classes, etc
* Support for different templating engines like Python’s `str.format` or Jinja2
* Easy to extend and create custom templates

![image](https://github.com/anithorat/Langchain_Intro/assets/101381417/c25e3958-8736-4c06-9282-ab95814b9aea)

![image](https://github.com/anithorat/Langchain_Intro/assets/101381417/e658d67b-db60-4407-a1e4-aa6b0d071452)

# **Example**

![image](https://github.com/anithorat/Langchain_Intro/assets/101381417/8655547a-efd6-457e-b6cc-4d4585d98de6)


# **Chain**

Chains are sequences of actions that can be performed on a prompt or an output.

Prompt: - A prompt is a set of instructions or inputs to guide the model’s response. The output from a prompt can be answers, sentence completions, or conversation responses. 

Chains are one of the core features of LangChain, a framework for building applications using language models. Chains are sequences of actions that can be performed on a prompt or an output. A prompt is the input that guides the model’s response. An output is the result of the model’s generation.


![image](https://github.com/anithorat/Langchain_Intro/assets/101381417/6a5c7942-fe38-473d-ada4-df7fc05084c1)

#### There are different types of chains in LangChain, depending on the complexity and functionality of the tasks. Some of the common types are:


