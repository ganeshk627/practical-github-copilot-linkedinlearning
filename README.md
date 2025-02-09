# practical-github-copilot-linkedinlearning


# 1. Working with GitHub Copilot

  1.1. What is GitHub Copilot?
  
    - Code assistant
    - Based on GPT focused on LLM
    - Popular languages available such as Python, JavaScript, etc.

  1.2. LLM
  
    - Models predict outcomes
    - Focus on language - code completion may or may not be the expected one
    - Code is language

  1.3. How LLMs work?
  
    - Tokenized data
    - Vocabulary size
    - Token cost - computational power and processing usage

  1.4. Training Phases
  
    - Predict next token/word
    - Mimics human communication
    - Reinforced learning - learning the same way humans learn

  1.5. Copilot for Individuals vs. Businesses
  
    - Business Copilot
      - Prompt privacy
      - Autocomplete, panels, chat
      - Suggestion privacy
    - User Engagement Data
      - Some data is sent
      - Evaluation, fine-tuning, abuse detection
      - Experiments and research
    - Other Features
      - Organization policies
      - License management
      - Proxy support (for the organization level but we are going to deep dive into individual level)

  1.6. Installing Copilot
  
    - GitHub --> Settings --> Profile --> Billings and Plans --> Plans and Usage --> Add-ons
      - Individual - $10/month
      - Business - $19/per user/per month
    - Install VSCode Insider build (might have additional features over regular VSCode)
      - [VSCode Insiders](https://code.visualstudio.com/insiders/)
    - Install 'GitHub Copilot Nightly'
    - Make sure 'GitHub Copilot Chat' is installed as a bundle with Copilot
    - Install 'GitHub Copilot Labs' if needed
    - To open chat press Shift+Ctrl+P

  1.7. Getting the Repo
  
    - Clone the repo (we are going to work with Python)
      - [GitHub Repo](https://github.com/LinkedInLearning/github-practical-copilot-4412871)

  1.8. Basic Autocomplete
  
  Try writing below code and see how the copilot suggests the code

    ```python
    def read_audio_list_from_files():

    ```
Also we could hover over the suggested code to see multiple suggestions, Accept complete code by pressing ```Tab``` or accept the word by pressing ```Command + Right Arrow```
> Note: Some of the suggestions might not be the expected one, so we need to be careful while accepting the suggestions

  1.9. Auto Completions Panel

**Multiple Suggestions:** GitHub Copilot can generate multiple code solutions for the same problem. Instead of just one option, you can view a list of possible solutions and choose the best one for your needs.

**Special Panel:** You can open a special panel to see multiple suggestions by using the following keyboard shortcuts:
- **Mac:** Press `Command + Shift + P`
- **Windows/Linux:** Press `Control + Shift + P`

**Improving Suggestions:** If the suggestions aren't what you want, try rewriting your comments to provide more context. The better your comments, the better the suggestions Copilot provides.

**Choosing the Best Solution:** After viewing the multiple solutions in the panel, you can pick the one that best fits your needs and accept it to replace your current code.

**Testing the Suggested Code:** Always test the code Copilot suggests to ensure it works as expected. Sometimes, the generated code may look correct but might not function properly in your specific use case.

  - Type the requirement in comments
  - Press Cmd+Shift+P
  - Select "GitHub Copilot: Open Completions Panel"
  - Now we could see some suggestions for the comments, there we could accept any of the suggestions

Or

  - Type the requirement in comments
  - Select all the comments you typed
  - Press Cmd+Enter
  - Now we could see some suggestions for the comments, there we could accept any of the suggestions

# 2. Using Copilot Chat

2.1. The Chat Panel

**Copilot Chat Panel:** This panel allows you to interact with GitHub Copilot by asking questions and using commands to assist with coding tasks.

**Slash Commands:** Typing a slash (`/`) in the chat panel brings up a list of commands, such as explaining selected code, generating unit tests, and troubleshooting code issues.

**Code Assistance:** You can select code and use the chat panel to get explanations, fix issues, or generate suggestions for improvements.

**Context Awareness:** The chat panel understands the programming environment you're working in and can provide relevant suggestions based on the context.

**Additional Features:** The panel allows you to copy code to the clipboard, insert code at the cursor, and even run code in the terminal.

  - Open chat panel from the left side of the VSCode or press Shift+Ctrl+P and select "GitHub Copilot: Open Chat Panel" or press Control+Cmd+I
  - Type '/' to see the commands
  - - explain - explain the selected code
  - - ext - 
  - - fix -
  - - help - general help about copilot
  - - tests - generate tests for the selected code
  - - vscode - questions about the VSCode
  - - clear - clear the session
  - Type 'help' to see the help commands

2.2. Generating data

  - Type the requirement in the chat panel
  - Press Enter
  - Copilot will generate the data for the requirement

2.3. Chatting with Copilot

  - Type the requirement in the chat panel
  - Press Enter
  - Copilot will generate the data for the requirement
  - Type the requirement in the chat panel
  - Press Enter
  - Copilot will generate the data for the requirement
  
2.4. Output to YAML

2.5. History and file names

**Chat History:** GitHub Copilot keeps a history of all your chats, which you can access through the history panel to review past interactions.

**File Names in YAML:** When working with YAML files, you can include specific file names to ensure proper functionality, such as audio file names for a podcast stream.

**Troubleshooting:** If Copilot doesn't provide the expected results, you can refine your prompts and ensure all necessary lines of code are selected to get accurate outputs.

**Sorting Issues:** If your YAML data is being sorted unexpectedly, you can use the `sort_keys` parameter set to `false` to prevent this.

2.6. Troubleshooting fixes

**Correcting Copilot:** Sometimes, you need to correct Copilot's output by providing more specific prompts or manually adjusting the code.

**Manual Adjustments:** It's often necessary to manually copy and replace code snippets to achieve the desired result.

**Iterative Process:** Troubleshooting with Copilot involves an iterative process of refining prompts and testing the output until it meets your requirements.

2.7. Writing comments


# Some Shortcuts
- Command + I/ Control + I --> Open the chat panel from the code
- Command + Control + I --> Open the chat panel separately
- Command + Enter/ Control + Enter --> Accept the suggestion
- Command + Shift + P/ Control + Shift + P --> Open the command palette

   

  
