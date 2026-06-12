# מילון קולי (Voice Dictionary)

A one-page web app for the iPad: tap the mic, say an English word, hear the most
accurate one-word Hebrew translation. Say **"תפרט"** within a few seconds to get a
short spoken Hebrew explanation of the word.

## How it works
- Speech-to-text: the device's built-in recognition (Safari Web Speech API) — free
- Translation/explanation: OpenAI chat completions (default model `gpt-5.4-mini`) — fractions of a cent per word
- Text-to-speech: the device's built-in Hebrew voice — free

## Setup
Open the page, tap ⚙︎, paste an OpenAI API key (stored only in the browser's
localStorage on that device), and start tapping the mic. The model name can also be
changed in the same panel.

Requires HTTPS for microphone access — GitHub Pages provides that.
