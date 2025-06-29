Unfortunately, Gemini doesn't have its own files with common settings. Therefore, every time you start a project, you need to write the rules again in the chat window. Even if you work with one project for a long time, Gemini may forget to use some rules. This is a convenient way to solve the problem - formalize rules and create your own settings file.

# Agent rules
This repository contains a `rules.toml` file designed to configure your AI assistant (e.g., Gemini in Android Studio, ChatGPT, Claude, or other LLMs). By defining a set of rules in this TOML file, you can guide the assistant’s behavior, ensuring more consistent responses and adherence to specific project guidelines or personal preferences.

## Why `rules.toml`?
* **Universality:** Suitable for easy reading by an AI Agent and simple understanding by a human.
* **Adaptability:** Easily configurable to meet the needs of a specific project.
* **Shareability:** Easy to share with the team.


## How to Use
1. Create a `rules.toml` file in the root folder of your project
2. Use the recommended rules and add your own
3. Ask the agent to read the file and follow these rules
