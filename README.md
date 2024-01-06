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
<br> You can check out the input and outputs at https://www.dropbox.com/scl/fo/9icq1vwhnge4f14c4jvt6/h?rlkey=db1yof5tya7f3oajvei01csxn&dl=0 


# Note:
<br>If you want to add new language then Just add the language and it's ISO-639 code in the code.<br> There are total 100+ languages available in internet. 
