# notion-sdk-typescript-starter

This is a template repository for getting started with the [Notion SDK](https://github.com/makenotion/notion-sdk-js)
and [TypeScript](https://www.typescriptlang.org/).

## Features

- TypeScript for type checking.
- Prettier for code formatting.
- A minimal GitHub Actions workflow that typechecks your code.
- Dotenv for configuring your Notion API token.
- Our lovely Notion SDK!

## What to do after duplicating

1. Make sure you've [created a Notion integration](https://developers.notion.com/docs/getting-started) and have a secret Notion token.
2. Add your Notion token to a `.env` file at the root of this repository: `echo "NOTION_TOKEN=[your token here]" > .env`.
3. `npm install`.
4. Edit the `page_id` in `index.ts` from FIXME to be any page currently shared with your integration.
5. `npm start` to run the script.
