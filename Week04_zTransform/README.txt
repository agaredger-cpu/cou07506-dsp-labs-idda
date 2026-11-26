COU 07506 Digital Signal Processing 2026/27
Week 4 — zTransform

Student          : Idda Symphorian Ngaiza
Registration No. : 240242413094
Class            : BEng24COE (Computer Engineering)
Notebook         : COU07506_Week04_240242413094.ipynb

Files
-----
COU07506_Week04_240242413094.ipynb   final notebook, already executed (outputs stored)
COU07506_Week04_240242413094.pdf     the same notebook printed to A4 with its cover page
data/my_voice.wav                     speech clip used by the audio tasks (offline)

Audio source
------------
Open Speech Repository, file OSR_us_000_0010_8k.wav — female speaker,
16-bit PCM, 8 kHz, Harvard sentences:
https://www.voiptroubleshooter.com/open_speech/american.html

The repository states that the material is freely available for use in VoIP
testing, research and development and any other reasonable application,
provided the source is identified as "Open Speech Repository". The citation
appears in the notebook, in the audio task itself. The downloaded clip was
trimmed to 3.5 s and saved as data/my_voice.wav; nothing else was changed.

How to run
----------
    jupyter notebook COU07506_Week04_240242413094.ipynb
    Kernel > Restart & Run All

Keep the data/ folder beside the notebook: the audio tasks read
data/my_voice.wav, and fall back to a synthetic tone if it is missing.
