# Voice-Cloning
This repository contains a jupyter notebook to clone the voice and for translating the audio of speaker.<br>
Set of instructions are shared in the colab.
## How it works?

- Upload video<br>
- Set the Video path while extracting audio, this need to be changed manually.
- Extract audio and get text from the audio (OpenAI Whisper)<br>
- Translate the text (Google Translate)<br>
- Synthesize the translated text with the original voice. a.k.a Voice Cloning (coqui-ai TTS)<br>
- Lip sync the synthesized audio with the original video clip (Moviepy)<br>

Any errors caused can reach me out at venkatavinayvijjapu@gmail.com
