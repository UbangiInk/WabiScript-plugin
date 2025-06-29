First attempt at creative AI work... Wish me luck!
I intend to build on the image review but add the following nuances:
- Creative personas to write captions for photography in a Lightroom Classic catalog workflow.
- Generate hiaku-like poetic, zen koan-like prose for images
- Provide a robust UI for interface


---------------------- original dev read me -------------------------------

This is a plugin for Lightroom Classic that generates alt text for photos using ChatGPT-4o and saves it to the caption field in the photo's metadata.

To use it:

1. Clone this repo
2. Get an OpenAI API key at https://platform.openai.com/api-keys (make sure it has access to the `gpt-4.1` model)
3. Open Lightroom Classic, go to File > Plug-in Manager > Add, and select the `lightroomalttextplugin.lrplugin` folder in this repo
4. Paste the OpenAI API key in the settings section, and click "done"
5. Select an image, go to Library > Plug-in Extras > Generate Alt Text with ChatGPT
6. Wait a few seconds, a message will let you know when the alt text has been generated
7. Inspect the alt text in the photo's metadata, and edit as needed
