Minimalistic Interface for Local Language Models (LLMs) (Powered by Ollama)
=========================================================

Introduction
------------



A simple interface for Ollama models, allowing you to chat with your models, save conversations and toggle between different ones easily.

Features
--------

* Chat with Local Language Models (LLMs): Interact with your LLMs in real-time through our user-friendly interface.
* Model Toggling: Switch between different LLMs easily (even mid conversation), allowing you to experiment and explore different models for various tasks.
* Memory-based Context Storage: Keep track of context in memory, ensuring smooth interactions even when switching between models.
* Conversation History: Save conversations in a local database, allowing you revisit them at a later date.
* Prompt Templating: Create parameter driven prompt templates to improve reuse.

Technical Details
----------------

* Built using React, Next.js, and Tailwind CSS for a clean and modern design.
* Utilizes LangchainJs and Ollama for seamless integration with Local Language Models (LLMs).
* Stores context in memory for efficient model switching.


To-do
---------------

- Add edit message icon for user messages
- Summarise conversations
- Incorporate visualisations
- Convert to desktop app so that it can be more powerful
- Command menu should allow for saving new prompt templates directly from there
- Command menu should let you edit + delete existing prompts




Installation Guide
---------------
Node js version 18 or above required 
<br/>
<br/>
NPM version 9 or above required
<br/>

``` 
node -v

npm -v

```

 1. Clone the repository
 2. Install all dependency ```npm install ```
 3. Run in locally ``` npm run dev ```

 