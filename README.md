# WhatsAI

A ChatGPT and Midjourney-Diffusion WhatsApp Bot.

### Usage

- Text: `$gpt your query`
- Audio: `$gpt-tts your query` (Default to portuguese. Change in the code).
- Image: `$mid-diff your query` (It does not return the image to whatsapp yet, so after the execution completes, check the `cache` folder at the root directory).

### Instalation

- Only [***Python 3.9***](https://www.python.org/downloads/release/python-390/) supports **pytorch_1.12.1+cpu** for image generation.
- **Microsoft Visual C++ 14.0** or greater is required for image generation. Get it with [***Microsoft C++ Build Tools***](https://visualstudio.microsoft.com/visual-cpp-build-tools/). 
- Install all dependencies with `npm i -y` and `pip3 install -r ./requirements.txt`
- Set your [*OpenAI API Key*](https://beta.openai.com/account/api-keys) on `.env` file
- Authenticate with your WhatsApp by scanning the QR Code that will show up in the terminal.

### Building the code

- First run `npm run build`
- Then run the app with `npm start`

### Running for tests
- Run the app with `npm run dev`

> _You may have to run the app twice, since there is a sort of bug on the Baileys dependency. So follow this steps if this is the case:_

- Scan the QR Code and wait until the scan screen closes
- Stop the app on the terminal with `Ctrl + C`
- Run the app again

