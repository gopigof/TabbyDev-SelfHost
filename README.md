# Tabby Configuration for Self-Hosting

This repo contains the configuration to run [Tabby](https://tabby.tabbyml.com) on your local machines through Docker. Do note that the language models can get pretty hungry for compute resources (GPU & CPU). I recommend a 40-series NVIDIA GPU to ran a code completion model alongside a chat model.

## Models
- The config uses Deepseek-Coder V2-Lite for code completion (IDE integrated) and OpenAI GPT4o for chat completion.


## Usage
- `docker-compose up -d` in the root directory.
- Go to `http://localhost:8080` to access the Tabby UI and create an account for the first time
- Use the PAT token presented on the home page of Tabby UI, in the IDE plugins.
- Enjoy.