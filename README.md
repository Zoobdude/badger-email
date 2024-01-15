# Badger Email

This is a work in progress.

## What is it?

The plan is to be able to read emails on a [Pimoroni Badger W](https://shop.pimoroni.com/products/badger-2040-w?variant=40514062188627) by connecting to a API running on a Raspberry Pi that retrives the messages.

Due to the very small 2.9" screen on the badger, it would be very painful to read entire emails on the Badger. A self hosted LLM (Large Language Model) will be therefore used to summerise them before sending to the Badger.

I have experimented using OpenAI's various APIs and the ChatGPT3/4 models and the summarisations were good however, due to the extreme length some of my emails can be, it would run up very large bills very quickly. Not to mention the potential privacy issues sending all my emails to a public API could cause.

Therefore, I intend to use the REST API included with [Ollama](https://github.com/jmorganca/ollama) which will allow me to run a model such as localy.
