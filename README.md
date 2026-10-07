# Back to Base certificate generator

The complete, responsive certificate generator for **Back to Base — Founder Investor Connect**. Enter a participant name, generate the certificate, and save it as PNG or PDF. The background has subtle glow and star animations, with reduced-motion support.

## Run locally

This is a static site with no build step or server-side secrets. Serve the `dist` directory with any static HTTP server, then open its local URL. For example, with Node.js:

```bash
npx serve dist
```

Opening `dist/index.html` directly may restrict browser features; use a local HTTP server when checking downloads.

## Files

| Path | Purpose |
| --- | --- |
| `dist/index.html` | Complete HTML, CSS, and JavaScript application |
| `dist/reference.png` | Original uploaded visual reference, preserved unchanged |
| `dist/blank-reference.png` | Certificate artwork with the sample recipient name removed for clean personalization |
| `dist/mobile-scene.png` | Text-free version of the scene used behind the responsive mobile layout |
| `.openai/hosting.json` | Configuration for the existing ChatGPT Site |

The certificate is composed in the browser. Names are not sent to a server. PNG and PDF files are generated client-side.

## Published version

[Open the ChatGPT Site](https://back-to-base-certificate-studio.y4wjsz692k.chatgpt.site/) (access is controlled by the Site owner).
