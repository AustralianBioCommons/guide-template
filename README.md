## About

Please see the [How-to Guide for the template](https://australianbiocommons.github.io/how-to-guide-template/) for more information on how to get started.  

## Quickstart: writing a guide with an AI assistant

The [`skills/`](skills/) folder contains two files for AI-assisted guide writing:

- [`skills/llm.txt`](skills/llm.txt): the BioCommons template conventions and closing checklist
- [`skills/SERVICE_CONTEXT.md`](skills/SERVICE_CONTEXT.md): a form describing the guide you are writing

1. **Fill in `skills/SERVICE_CONTEXT.md`**. Title, tool name, and target platform are the minimum required fields; write `Not yet known` for anything else.
2. **Open a new AI conversation** (Copilot, Claude, ChatGPT, Gemini).
3. **Paste `skills/llm.txt`** as message 1:
   > I'm writing an Australian BioCommons how-to guide. Use the conventions in the following file for everything you help me produce today. `<paste skills/llm.txt contents>`
4. **Paste your filled-in `skills/SERVICE_CONTEXT.md`** as message 2:
   > Here is the context for the specific guide I'm writing today. `<paste skills/SERVICE_CONTEXT.md contents>`
5. **Confirm the AI understood both files**, then start with the skeleton:
   > Generate the Quick Start checklist and workflow summary table. Do not write any prose yet.
6. **At the end of every session**, run the closing checklist:
   > Run the closing checklist from the BioCommons llm.txt against the guide we have written today and tell me what is missing or incomplete.

## Acknowledgements for the guides

This work is supported by the [Australian BioCommons](https://www.biocommons.org.au/) via funding from [Bioplatforms Australia](https://bioplatforms.com/), the Australian Research Data Commons (https://doi.org/10.47486/PL105) and the Queensland Government RICF programme. Bioplatforms Australia and the Australian Research Data Commons are funded by the National Collaborative Research Infrastructure Strategy (NCRIS).

This repository makes use of the ELIXIR toolkit theme: [![theme badge](https://img.shields.io/badge/ELIXIR%20toolkit%20theme-jekyll-blue?color=0d6efd)](https://github.com/ELIXIR-Belgium/elixir-toolkit-theme)

This template is based on the [ELIXIR Toolkit Theme example](https://github.com/ELIXIR-Belgium/elixir-toolkit-theme-example).
