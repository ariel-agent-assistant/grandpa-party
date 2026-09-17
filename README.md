# Grandpa Party 🎬

Shout a scenario -> a 30-second hero video of grandpa plays on the TV, in his face, his voice, speaking Russian.

**Pure static app - no server.** Open the GitHub Pages URL on the party laptop, fullscreen.

## Setup (once per device, in the page)
1. Pick a site password, paste fal + OpenRouter keys (sessionStorage only).
2. Upload 4-9 clear photos of grandpa + optionally a 2-15s voice clip (IndexedDB only).
Nothing secret is in this repo; keys and photos never leave the browser except directly to fal/OpenRouter over HTTPS.

## Use
SHOUT AN IDEA -> check transcript -> MAKE THE VIDEO -> ~30s later chunk 1 plays, 2-3 follow. Every confirmed idea queues.

## How
STT: fal Wizper. Director: gemini-3-flash (funny 30s episode, 3 x 10s chunks, grandpa-as-hero, family tone, short Russian lines, SETTING LOCK). Video: fal minimax/h3-max/reference-to-video @ 768P 16:9, up-to-9-photo identity lock + reference audio (his real voice), shared seed, parallel chunks.
