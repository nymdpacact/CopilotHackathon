# GitHub Copilot Hackathon

Demo project for running labs to evaluate Copilot viability

- [Goal](#goal)
- [Pre-requisites](#pre-requisites)
- [Work with Github Codespaces](#work-with-github-codespaces)
- [Instructions](#labs-instructions)
- [Quick Links](#quick-links)

## Goal

The goal of a GitHub Copilot Hackathon is to learn how to use it, using a set of [exercises (labs)](#labs-instructions) that consist of building a web server using Nodejs with different functionalities, a .NET Web API or a Java Rest API (Spring Boot).

We have also set two exercises for data engineers and data scientists based on python.

For those who are already familiar with GitHub Copilot, we have also defined a series of [challenges](#challenges-instructions) to test your skills. In this case, you will find an introduction and short guidance to help you solve the challenge, but you will have to do most of the work on your own (with the help of Copilot, of course).

GitHub Copilot is an AI-powered code assistant that helps developers write better code faster. It uses machine learning models trained on billions of lines of code to suggest whole lines or entire functions based on the context of what you’re working on. By using Copilot, you can learn how to write better code and improve your productivity.

Remember:

- As you type GitHub Copilot will make suggestions, you can accept them by pressing Tab.
- If nothing shows up after Copilot write some lines, press enter and wait a couple of seconds.
- Press **Ctrl + Enter**, to see more suggestions.
- Use Copilot chat to support your learning and development.
- Press **Ctrl + i** to start Copilot chat inline within your code. 

### Proctors
- Sam (dotnet, springboot)
- Ben (Node, Typescript)
- Manny (springboot, dataengineering, datascience)
- Kevin (C++, Node)

## Pre-requisites

**GitHub Copilot access**

If you still do not have an active Copilot license, a 30 day trial can be requested here: https://github.com/github-copilot/signup.

### Work with GitHub Codespaces

Codespaces is a pre-configured development environmnet hosted in Azure with VS Code in the browser as the editor. All the languages, dependencies, frameworks and tools needed for this workshop should come pre-installed and readty to go.

To start programming just start a new codespace and you are ready to go, don't need to install anything.

### IDE Extensions

Install the Copilot Extension for you IDE (these extensions should already be installed as part of your Codespace so no action needed, but helpful when using Copilot locally)

- [Visual Studio Code Copilot Extension](https://docs.github.com/en/copilot/using-github-copilot/getting-code-suggestions-in-your-ide-with-github-copilot?tool=vscode)
- [Visual Studio 2022 Copilot Extension](https://learn.microsoft.com/en-us/visualstudio/ide/visual-studio-github-copilot-extension?view=vs-2022)
- [Visual Studio 2022 Copilot Chat Extension](https://learn.microsoft.com/en-us/visualstudio/ide/visual-studio-github-copilot-chat?view=vs-2022)
- [JetBrains Copilot Extension](https://docs.github.com/en/copilot/using-github-copilot/getting-code-suggestions-in-your-ide-with-github-copilot?tool=jetbrains)

## Labs instructions

- [Node Server](./exercisefiles/node/README.md)
- [Node Server Typescript](./exercisefiles/node_typescript/README.md)
- [.NET Web API](./exercisefiles/dotnet/README.md)
- [Java Spring Boot](./exercisefiles/springboot/README.md)
- [Python Data Engineer](./exercisefiles/dataengineer/README.md)
- [Python Data Scientist](./exercisefiles/datascientist/README.md)
- [C++](./exercisefiles/c++/README.md)

## Challenges instructions

- [Develop a shop cart](./challenges/eshop/eshop.md) 
- [Develop a memory game](./challenges/memorygame/memorygame.md)
- [Develop a chat based on websockets](./challenges/chatwebsockets/chatwebsockets.md)
- [Behavior Driven Development (BDD) challenge](./challenges/bdd/README.md)
- [Analysis cryptocurrency market](./challenges/cryptoanalisis/crypto.md)
- [Expense Tracker](./challenges/expensetracker/README.md)

### Tips

- use multi-line comments for additional details for Code Complete
- be explicit with your requests ([see here for some prompt engineering tips](https://docs.github.com/en/enterprise-cloud@latest/copilot/using-github-copilot/copilot-chat/prompt-engineering-for-copilot-chat))
- keep relevant files open in tabs
- copy and paste terminal output when chatting
- use slash commands like @workspace and @terminal to include additional context (type /help to get a list)
- nudge Chat by referring to previous prompts and responses
- use the Fix with Copilot feature for syntax errors
- try a different model if you’re not getting the right response
- use Code Review to review a method
- add files/context to your chat prompt


## Quick Links

1. [Lots of Getting Started Resources](https://github.com/rob-derosa/github/issues/1)

2. [Copilot Keyboard Shortcut cheat sheet](https://github.com/fiserv-copilot-workshop/CopilotHackathon/tree/main/Resources)

3. [Prompt Engineering tips](https://docs.github.com/en/enterprise-cloud@latest/copilot/using-github-copilot/copilot-chat/prompt-engineering-for-copilot-chat)

4. [Multi-model Use Cases](https://docs.github.com/en/copilot/using-github-copilot/ai-models/changing-the-ai-model-for-copilot-chat)

1. [About GitHub Copilot](https://docs.github.com/en/copilot/about-github-copilot)

2. [Getting started with GitHub Copilot](https://docs.github.com/en/copilot/using-github-copilot/getting-started-with-github-copilot)

3. [About code referencing in GitHub Copilot](https://docs.github.com/en/copilot/using-github-copilot/finding-public-code-that-matches-github-copilot-suggestions)

4. [Using GitHub Copilot Chat in your IDE](https://docs.github.com/en/copilot/github-copilot-chat/using-github-copilot-chat-in-your-ide)

5. [Enabling GitHub Copilot in the CLI](https://docs.github.com/en/copilot/github-copilot-in-the-cli/enabling-github-copilot-in-the-cli)

6. [GitHub Copilot MS Learn Modules](https://learn.microsoft.com/en-us/training/browse/?terms=github%20copilot)

7. [GitHub Copilot Certifications](https://resources.github.com/learn/certifications/)

### Multi-Model Breakdown

**Anthropic’s Claude 3.5 Sonnet** is designed to handle an extensive range of coding tasks, from initial design to maintenance, optimisations, and beyond. Its prowess is evident in managing complex and multi-step coding challenges, making it a robust option for dynamic software development requirements.

**Gemini 2.0 Flash**, a Google AI model, is particularly useful for coding applications like generating code snippets, suggesting code fixes, explaining complex code concepts, and even assisting with debugging, thanks to its advanced reasoning capabilities and ability to understand complex prompts, making it a powerful tool for developers to enhance their coding efficiency and productivity; it can also integrate with existing coding environments to provide real-time assistance. 

**OpenAI’s latest models, o1-preview and o1-mini**, surpass the capabilities of the current GPT 4o. These models boast enhanced reasoning abilities, providing a deeper understanding of code constraints and edge cases to produce efficient, high-quality results.

