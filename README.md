# Fast-Whisper
Whisper audio to text transcription that is very fast, accurate and does not have high hardware requirements

## Setup 

1. Install [python](https://www.python.org/) and then run the following in your Terminal / Command Prompt.
``` python
pip install --upgrade pip
pip install --upgrade transformers accelerate datasets[audio]
```

2. Download / git clone this repository onto your computer.
``` python
git clone https://github.com/LetsConnectWell/Fast-Whisper.git && cd Fast-Whisper
```
3. Place the mp3/mp4/m4a/wav files that you want to transcribe in the audio folder.

4. Run
``` python
python whisper.py
```
5. View your transcripts in the transcripts folder.
