# Chrome Crash - DevTools Overrides (JS)

This repo reproduces a crash that happens when using Overrides to change the JS loaded by the page.

Currently this crashes on all versions of Chrome:
- Beta: Chrome 76
- Canary: Chrome 77
- Local build: `24c051788c32e3a057efca5753838db3296080c8`


## Steps to reproduce

To reproduce the bug locally:

1. Clone this repo
2. Open a chrome tab and go to http://example.com/
3. Open your DevTools
4. Add the root of this repo as the root of your overrides
5. Reload
6. Boom

