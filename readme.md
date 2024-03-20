# Azure OpenAI Brain Teaser

This repository shows how to create an open AI service Python application to resolve some brain teaser(Sdoku, parking place an others...)
This exemple uses OpenAI Azure service, Azure Text to speech 

This example is inspired by Microsoft documentation that you can find here

Learn how to work with the GPT-35-Turbo and GPT-4 models [GPT-4 and GPT-35-Turbo](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/chatgpt?tabs=python&pivots=programming-language-chat-completions)

Deploy a web app for chat on your data with Azure AI Studio [Azure AI Studio](https://learn.microsoft.com/en-us/azure/ai-studio/tutorials/deploy-chat-web-app)

What is Responsible AI? [Responsible AI Principles](https://learn.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai?view=azureml-api-2)



## Prerequisites
You need to create an Azure OpenAI service deployment with GPT-4 model and create an Azure Speech service first. This resources are used in the following Jupiter setup

## Install and test

```sh

$ pip install jupyterlab
$ pip install openai --upgrade
$ pip install pynq 
$ pip install azure-cognitiveservices-speech


$ set AZURE_OPENAI_KEY="**********************"
$ set AZURE_OPENAI_ENDPOINT="******************"
$ set AZURE_SPEECH_KEY="******************"

# Update PROMPT_NUMBER = 1  // update the line in the jupyter note book or add you own prompt

$ jupyter lab
```

## Output

If you choose the first prompt you will get somthing like the following picture:

![](./res/output-parking.png)


Please feel free to share any feedback.
