# vim-ai

This plugin adds Artificial Intelligence (AI) capabilities to your Vim and Neovim.
You can generate code, edit text, or have an interactive conversation with GPT models, all powered by OpenAI's API.

To get an idea what is possible to do with AI commands see the [prompts](https://github.com/madox2/vim-ai/wiki/AI-prompts#prompts) on the [Community Wiki](https://github.com/madox2/vim-ai/wiki)

## Features

- Generate text or code, answer questions with AI
- Edit selected text in-place with AI
- Interactive conversation with ChatGPT
- Supports custom roles and more

## Installation

Using built-in Vim packages `:help packages`

```sh
# vim
mkdir -p ~/.vim/pack/plugins/start
git clone https://github.com/mdelazek/vim-ai.git ~/.vim/pack/plugins/start/vim-ai

```

## Configuration

To tailor the default settings, you need to update certain variables in your `.vimrc` file. Here are some examples of what you could add or modify:

```vim
let g:default_ai_model = "MODEL_NAME"
let g:ai_api_url = "API_URL"
let g:api_token = "API_KEY"
```


[MIT License](https://github.com/madox2/vim-ai/blob/main/LICENSE)
