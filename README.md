# AI Writing Toolkit

A privacy-conscious writing workspace with browser-based text utilities and an AI prompt builder.

## MVP features
- Rewrite helper with selectable tone and approach.
- Limited proofreading for common spelling and punctuation patterns.
- Extractive summary helper with short, medium and detailed lengths.
- Structured expansion suggestions that do not fabricate facts.
- AI prompt builder for use with a service selected by the user.
- Word and character counts, copy and text download.
- Responsive layout and dark mode.
- GitHub Pages deployment and JavaScript syntax validation workflows.

## Important distinction
The built-in rewrite, proofreading, summary and expansion functions are rule-based utilities. This project does not connect to a generative AI model or send text to an external AI provider. The prompt builder creates a prompt for the user to copy into a service of their choice.

The proofreading dictionary is limited. The summariser uses simple word-frequency sentence ranking. These tools can miss errors or context and their output must be reviewed.

## Run locally
Serve this directory with any static HTTP server, or open index.html in a modern browser. No build step or API key is required.

## Privacy
Text entered into the built-in tools is processed in the browser. There is no application upload endpoint or account system. If you copy a generated prompt to a third-party AI service, that service's privacy policy applies.

## Technology
HTML, CSS and vanilla JavaScript.