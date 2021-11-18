# Prosemirror Collab Example

Stripped out prosemirror website collab example into a stand alone environment for learning and toying around.

## Get Started

```bash
npm install
npm run watch
npm run start
```

## Why not directly use prosemirror/website?
Mainly I have trouble get website to build and run properly
- using `ModuleServer` handling different versions of prosemirror-view and prosemirror model
- `getdocs` package tries to parse prosemirror-model and throws error

