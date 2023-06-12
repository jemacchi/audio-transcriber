# Audio-transcriber
Simple Python audio transcriber using OpenAI's Whisper speech recognition model

Table of Contents
=================
* [Installation Instructions](#Installation-Instructions)

# Installation Instructions

1. Install required packages with pip

`pip install -r requirements.txt`

2. Run a program with Python3

`python3 transcriber.py -u, --url <URL>`

# Tips

- In case you get an error message like this FileNotFoundError: [Errno 2] No such file or directory: 'ffmpeg' , ensure that you have ffmpeg installed.
  
  Reference: https://github.com/kkroening/ffmpeg-python/issues/251

  In linux env:
  
    `sudo apt install ffmpeg`


- If you want to see a progress bar while transcription is done, then ...
  
  Visit https://github.com/openai/whisper/discussions/850 for a reference
