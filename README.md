# GTD cli

Send things from command line straight to GTD inbox in Trello.

## Prerequisites
* Trello board named "GTD"
* List in that board named "Inbox"

## Install

```bash
npx -p trello-cli trello
# Get an API key and put it in ~/.trello-cli/config.json
# https://trello.com/app-key
npx -p trello-cli refresh
npm i -g .
```

## Usage

```bash
gtd <ticket name> [ticket description]
```
