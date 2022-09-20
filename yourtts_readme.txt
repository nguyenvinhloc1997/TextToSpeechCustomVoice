
I laydown here step by step as to how I created this yourtts.ipynb
===================================================================

1- Create the virtual env:
    a- python3 -m venv v0.7.1_pip
    b- source v0.7.1_pip/bin/activate

2- Install tts version 0.7.1 becaause this guy says so:
    (Follow this thread for Kaoru8 - https://github.com/coqui-ai/TTS/discussions/1249)
    * git clone https://github.com/coqui-ai/TTS
    * cd TTS
    * pip install -e .[all] tts==0.7.1

3- Download the pretrained 
    "tts_models/multilingual/multi-dataset/your_tts" model + speaker encoder ZIP. 
    Download URL is in "TTS/.models.json". 
    The version that worked for me is here 
    (https://coqui.gateway.scarf.sh/v0.6.1_models/tts_models--multilingual--multi-dataset--your_tts.zip) 
    and references commit e9a1953 as being compatible.

    unzip the ZIP file
    rename the directory to yourtts_models

