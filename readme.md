# Suris Character Generator


![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![NoobLel](https://img.shields.io/badge/Knowledge%20required-Noob-red.svg)

This project aims on letting you dynamically generate RPG-Style characters using local AI (Ollama recommended), based on just however much input you want to give it (it's a single text-input)

## Features

- Dark and modern design
- Feature-rich live display
- Copy to clipboard in plain-markdown
- Completely local
- Doesn't require much input, but supports it, so it's very flexible

## Usage & Examples

Put either just a random name (e.g. Lars), or a full description, containing what you deem neccesary, here is an example:

```
Lars, a young adult, the founder of the anarchistic region "Anarchistia".
He's very very strong, one of the strongest people alive
```

## Installation

1. Make sure you've installed Ollama. If you don't, install it from https://ollama.com
2. Make sure you have the LLaMA3 model pulled w/Ollama.
- Open a command line (cmd in windows) and enter `ollama pull llama3`
3. Clone this repo, or download it as a ZIP and extract it somewhere
4. Make sure `serve` is installed via NPM
- If NPM is not installed, download it first from https://nodejs.org
- Do `npm install --global serve` in your command line.
5. In the directory where you have this repo extracted, open a command line
- On Windows, this can be done by clicking on the Adress-Bar in the file-explorer. Type in `cmd` into the adress-bar and press enter.
6. Serve the website with executing `serve`
7. You're done, just go to the adress that's shown in serve (typically http://localhost:3000/)

## Feedback

If you have any feedback, please reach out to me at contact@thrilltech.top