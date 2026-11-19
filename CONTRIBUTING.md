# Contributing

Thanks for wanting to help with Korn.

## How it is built
Everything lives in one self-contained `index.html`: no build step, no dependencies.
Open it in a browser (or `npx serve .`) and you are running it.

## Ways to help
- **Bugs:** open an issue with browser, device and steps to reproduce.
- **Ideas:** open a feature request and describe the sound or workflow you want.
- **Code:** fork, branch, change, open a pull request.

## Pull requests
- Keep one change per PR and describe what it does to the sound.
- Test in at least one desktop and one mobile browser.
- Audio code runs in the audio thread or an AudioWorklet: no allocation in the per-block path.
- Keep the file self-contained: no external scripts except Google Fonts.
- Do not copy code from GPL projects such as PaulXStretch; this repo is MIT.
- By contributing you agree that your contribution is licensed under the MIT License.
