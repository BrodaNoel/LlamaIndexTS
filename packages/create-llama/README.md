# Create LlamaIndex App

The easiest way to get started with [LlamaIndex](https://www.llamaindex.ai/) is by using `create-llama`. This CLI tool enables you to quickly start building a new LlamaIndex application, with everything set up for you.

## Features

- NextJS, ExpressJS, or FastAPI (python) stateless backend generation 💻
- Streaming or non-streaming backend ⚡
- Optional `shadcn` frontend generation 🎨

## Get Started

You can run `create-llama` in interactive or non-interactive mode.

### Interactive

You can create a new project interactively by running:

```bash
npx create-llama@latest
# or
npm create llama@latest
# or
yarn create llama
# or
pnpm create llama@latest
```

You will be asked for the name of your project, along with other configuration options.

Here is an example:

```bash
>> npm create llama@latest
Need to install the following packages:
  create-llama@latest
Ok to proceed? (y) y
✔ What is your project named? … my-app
✔ Which template would you like to use? › Chat with streaming
✔ Which framework would you like to use? › NextJS
✔ Which UI would you like to use? › Just HTML
✔ Which chat engine would you like to use? › ContextChatEngine
✔ Please provide your OpenAI API key (leave blank to skip): …
✔ Would you like to use ESLint? … No / Yes
Creating a new LlamaIndex app in /home/my-app.
```

### Non-interactive

You can also pass command line arguments to set up a new project
non-interactively. See `create-llama --help`:

```bash
create-llama <project-directory> [options]

Options:
  -V, --version                      output the version number

  --use-npm

    Explicitly tell the CLI to bootstrap the app using npm

  --use-pnpm

    Explicitly tell the CLI to bootstrap the app using pnpm

  --use-yarn

    Explicitly tell the CLI to bootstrap the app using Yarn

```

## LlamaIndex Documentation

- [TS/JS docs](https://ts.llamaindex.ai/)
- [Python docs](https://docs.llamaindex.ai/en/stable/)
## Running the Application

After creating your new LlamaIndex application, you need to install all the necessary dependencies and build the application before you can start it. Follow these steps:

1. Install the dependencies:

```bash
npm install
```

2. Create a production build of the application:

```bash
npm run build
```

3. Start the application:

```bash
npm run start
```

Please note that `npm run start` is meant to start a production server and requires a build to be created first.

Inspired by and adapted from [create-next-app](https://github.com/vercel/next.js/tree/canary/packages/create-next-app)
