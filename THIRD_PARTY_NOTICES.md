# Third-party notices

Korn contains no third-party code. Everything in `index.html` (granular engine,
spectral STFT engine, Paulstretch, UI) is original work under the MIT License in `LICENSE`.

## Fonts (loaded at runtime from Google Fonts, not redistributed here)
- **Inter** – © The Inter Project Authors, SIL Open Font License 1.1 – https://github.com/rsms/inter
- **JetBrains Mono** – © The JetBrains Mono Project Authors, SIL Open Font License 1.1 – https://github.com/JetBrains/JetBrainsMono

On Apple devices the system font (SF Pro) is used first; it is not bundled.

## Algorithm credit
The extreme time-stretch is an independent implementation of the random-phase
STFT technique by Nasca Octavian Paul (Paulstretch). No code from Paulstretch or
PaulXStretch is included, so their licenses do not apply to Korn's code.

- **Paulstretch** – Nasca Octavian Paul – https://github.com/paulnasca/paulstretch_python
- **PaulXStretch** – Xenakios, Jesse Chappell (sonosaurus) – https://github.com/essej/paulxstretch
  – GNU GPL v3 with a section 7 app-store exception. Full text for reference:
  [licenses/PaulXStretch-GPL-3.0.txt](licenses/PaulXStretch-GPL-3.0.txt)
