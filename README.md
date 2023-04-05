# OpenAI PoC implemented in Next.js

![image](https://user-images.githubusercontent.com/61545957/229975828-d595518e-ddb2-483d-8bcf-d88a3ed12417.png)

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
