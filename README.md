# OpenAI PoC implemented in Next.js

![GIF](https://user-images.githubusercontent.com/61545957/230609955-0af13e54-bd23-42d6-9548-ebcf54e41ae4.gif)

This repository was developed using [openai-node](https://github.com/openai/openai-node) and based on [openai-quickstart-node](https://github.com/openai/openai-quickstart-node), with several additional elements added.

- Supports styled-components and TypeScript
- Remember conversation context instead of one-time responses
- More intuitive and clean UI with easy customization options

## Getting Started

1. If you don’t have Node.js installed, [install it from here](https://nodejs.org/en/) (Node.js version >= 14.6.0 required)

2. Clone this repository

3. Navigate into the project directory

   ```bash
   $ cd openai-poc
   ```

4. Install the requirements

   ```bash
   $ npm install
   ```

5. Make a copy of the example environment variables file

   On Linux systems:

   ```bash
   $ cp .env.example .env
   ```

   On Windows:

   ```powershell
   $ copy .env.example .env
   ```

6. Add your [API key](https://platform.openai.com/account/api-keys) to the newly created `.env` file

7. Run the app

   ```bash
   $ npm run dev
   ```

8. Deploy it to the cloud with [Vercel](https://vercel.com/new?utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment))

## Customizing the Model

You can customize the following model-related variables in the `setting.ts` file.

| Variable      | Description                                                                                                                 | Option                                         | Type   |
| ------------- | --------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- | ------ |
| `PREFIX`      | Prefix to include in all conversations                                                                                      | Whatever you want (language, role, tone..)     | string |
| `MODEL`       | [Models](https://platform.openai.com/docs/models/overview)                                                                  | Available models                               | string |
| `TEMPERATURE` | [Adjust your settings](https://platform.openai.com/docs/quickstart/adjust-your-settings)                                    | Number between 0 and 1                         | number |
| `MAX_TOKENS`  | [What are tokens and how to count them?](https://help.openai.com/en/articles/4936856-what-are-tokens-and-how-to-count-them) | Maximum number of tokens allowed by each model | number |

## License

[MIT](https://github.com/joseph-106/openai-poc/blob/main/LICENSE)
