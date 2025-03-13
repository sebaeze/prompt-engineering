# Prompt Engineering

The purpose of this repo is to help you to enhance your prompting skills

## What is a prompt in the context of AI ?

A prompt is the input and/or instruction given to a AI Model in order to guide Its response.

![prompt_engineering](./diagrams/prompt_engineering.png)

## Why Should I learn about prompt engineering ?

Refining your prompts will enhance your deliverables and productivity by leveraging the AI. The better you guide the AI Model's responses, the more your work will be boosted.

## What Can I do using prompt ?

- Shape the behaviour of the AI Model.
- Format the output / response from the AI Model.
- Get accurate responses.
- Minimize incorrect responses.

## Where Can I test my prompt?

- https://huggingface.co/playground
- https://aistudio.google.com/prompts/new_chat
- https://chat.mistral.ai/chat
- https://chatgpt.com/
- https://chat.deepseek.com/a/chat
- https://gemini.google.com/app

## Prompt techniques

### Steps for improving your prompt

- Define your objective clearly: Be specific about the purpose and desired output.
- Provide context: Include relevant information or background.
- Use clear and simple language: Look for the right wording, don't be ambiguous.
- Specify the format or style.
- Ask direct questions or give explicit instructions.
- Iterate and Refine: Test your prompt and modify It in order to achieve your goal.

### Zero-Shot

This technique do not provide context either examples in the query or prompt. As a result, the AI Model will entirely rely on the pre-trained data.

Recommended for:
- Simple tasks that do not require dinamic information.
- Experimentation with LLM.
- General knowledge tasks.


### One-Shot

In this technique you give to the AI Model a single example of how you want the response, this guides the AI Model on how the response should be. 

Recommended for:
- Limited training data.
- Easy tasks that require output formatting.
- Not complex enough to require several examples.

### Few-shot

You provide in the prompt a few examples of the task you want the model to execute. This technique helps the AI Model to response as expected.

Recommended for:
- Task definition.
- Tasks for a niche that the AI Model was not train on.
- When the AI Model needs to adapt quickly having no datataset to be trained.

### Chain-of-Thought (CoT)

The CoT technique involves in sending in the prompt a series of steps to follow by the AI Model, in such a way that the response is the result of following a procedure, making easier to resolve complex tasks and reducing the risk of incorrect assumptions.

Recommended for:
- Complex problem solving
- When a problem requires several steps to achieve a solution
- Reduce errores in ambiguos or unclear contexts
- Teach the model a procedure or process to deal with specific areas

### Instruction-based prompting

Using this technique you send direct and clear requests to the model, for example: resume a text in 200 words, make a list of 10 points, etc.

Recommended for:
- Performing specific tasks
- Chatbots that response to users in specific way
- Generating content from text or input

### Role-based prompting

In this technique, you assign a role or persona for the model to assume, so the model has context and boundaries in order to elaborate answers to the inquires.

Recommended for:
- Education content, for example assuming the role of teacher.
- Customer service and support.
- Professional in a specific area.

