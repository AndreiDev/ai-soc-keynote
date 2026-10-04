# The AI SOC, made visible

Ten working components of an AI-native SIEM, presented as a six-act keynote. Each component is a real tool an AI-SOC team would use, built on modern web technology. That technology is what makes AI decisions explainable, investigations faster and autonomous response safe.

**Live:** https://andreidev.github.io/ai-soc-keynote/

| Act | Component | Technology |
|---|---|---|
| Trust the AI | Explainable verdict ("Why 97%?") | Explorable explanation, D3 |
| Protect the AI | Prompt-injection firewall | Transformers.js (on-device models) |
| | Tamper-evident decision ledger | Web Crypto SHA-256 hash chains |
| Cut the noise | Nine alerts become one case | GSAP Flip, SMIL, CSS @property |
| Understand fast | Attack replay | Pure-function canvas rendering, Remotion |
| | Blast radius across 1,964 entities | Gaussian splatting (Spark) |
| Act safely | Approve with consequence simulation | D3, CSS @property, Web Audio |
| Get ahead | Attack paths to crown jewels | WebGPU physarum solver |
| | Telemetry blind spots | Radiance-cascade global illumination |
| | Ten million sign-ins, hunted in the browser | WebGPU compute (Three.js TSL) |

## Using it
- Press **P** for presenter mode: the arrow keys move between slides, Esc exits.
- Each component plays its own story, then hands control to you. Hover a stage for **Full screen** or **Open alone**.
- Every component also runs on its own page: `components/<name>.html`. Add `?t=12` to jump to a moment, or `?captions=0` to hide captions.

## Requirements
- Use a recent Chrome or Edge, ideally with a GPU. WebGPU powers attack paths and the 10M-event explorer; other browsers get fallbacks.
- Libraries load from jsDelivr, and fonts from Google Fonts.
- The injection firewall can download real models (54 MB) after a click; by default it shows a recorded snapshot.
- Everything runs client-side: there is no server and no data leaves the browser.

The scenario (Meridian Freight, CASE-4127) and every person, IP and incident in it are fictional.
