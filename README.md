# ChatGPT Export Organizer

A single-file, local tool: turn the `conversations.json` file exported from ChatGPT into a searchable, viewable list, and export any conversation as Markdown.

## Not affiliated with OpenAI

This is an unofficial community tool. It is not made by, endorsed by, or affiliated with OpenAI. It does not log in, does not go online, does not upload anything, and needs no API key. It cannot pull conversations directly from your ChatGPT account; you select the export file yourself.

## What it does

- Reads `conversations.json` locally (from ChatGPT Settings > Data export)
- Searches by title and content
- Shows a conversation cleanly, in time order
- Exports any conversation as a Markdown file, or copies Markdown
- Includes one fake sample conversation via "Load sample"

## What it does not do

- It does not connect to your ChatGPT account
- It is not guaranteed to support every future change to the ChatGPT export format; if parsing fails, first check that the file really is `conversations.json`
- The sample conversation is fake, for demo purposes only

## Privacy

The file is processed only in your browser with JavaScript and is never sent to any server. Do not paste passwords, keys, or other sensitive information into the tool.

## How to use

1. Open `index.html` in a browser
2. Select your exported `conversations.json`
3. Search, open a conversation, export or copy Markdown

## License

MIT, see `LICENSE`.


## Versions / 版本

- English: `index.html`
- 中文版：`index-zh.html`
