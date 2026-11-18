# ALFRED 2.0

A responsive, Jarvis-inspired personal assistant interface with browser speech recognition, spoken replies, and a secure Netlify server-side AI proxy.

## Deploy

Connect this repository to Netlify. Publish directory: `.`. Functions directory: `netlify/functions`.

Set `OPENAI_API_KEY` in Netlify environment variables with the **Functions** scope. Never put the key in browser code or commit it to Git.

## Voice notes

- Open the deployed site over HTTPS and allow microphone access.
- Tap **ACTIVATE ALFRED** to start foreground wake-phrase listening.
- Say **“Alfred”**, then your request.
- iPad Safari speech recognition support varies by iPadOS version. Browser wake-word listening is not guaranteed while the page is backgrounded or the device is locked.
- The voice uses the best available English UK system voice; exact voice availability depends on the device.
