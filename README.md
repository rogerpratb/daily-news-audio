# daily-news-audio

Versió en àudio del Daily News Briefing diari, generada automàticament amb
[Piper](https://github.com/OHF-Voice/piper1-gpl). Els MP3 i la pàgina per escoltar-los
viuen a la branca `claude/audio`, publicada amb GitHub Pages:
https://rogerpratb.github.io/daily-news-audio/

Només es conserven els àudios dels últims 14 dies.

## Veu

`voice/es_ES-sharvard-medium.onnx` i `.onnx.json` provenen de
[rhasspy/piper-voices](https://huggingface.co/rhasspy/piper-voices), entrenada amb el
corpus Sharvard, llicència [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/).
Es guarden aquí perquè l'entorn que genera l'àudio no pot accedir a Hugging Face.
