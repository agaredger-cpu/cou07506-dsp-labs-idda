# COU 07506 — Digital Signal Processing Laboratory Reports (Weeks 1–4)

**Idda Symphorian Ngaiza** · Registration No. **240242413094**
BENG24COE — Bachelor of Engineering in Computer Engineering
Department of Computer Engineering, Dar es Salaam Institute of Technology
Academic year 2026/2027 · Submitted 25 November 2026

This repository holds my four COU 07506: Digital Signal Processing laboratory
reports. Each folder contains the executed notebook, the same notebook printed
to A4 behind the laboratory cover page, the speech clip the audio tasks read,
and a short note describing the folder.

| Week | Laboratory | Topic | Folder |
| --- | --- | --- | --- |
| 1 | Lab 0 | Setting up the DSP laboratory | [`Week01_Lab0_Setup/`](Week01_Lab0_Setup) |
| 2 | Lab 1A | Sampling, aliasing and quantization | [`Week02_Lab1A_Sampling/`](Week02_Lab1A_Sampling) |
| 3 | Lab 1B | Convolution and linear time-invariant systems | [`Week03_Lab1B_Convolution/`](Week03_Lab1B_Convolution) |
| 4 | Lab 2 | The z-transform and system response | [`Week04_zTransform/`](Week04_zTransform) |

```
Week01_Lab0_Setup/
├── COU07506_Week01_240242413094.ipynb
├── COU07506_Week01_240242413094.pdf
├── README.txt
└── data/my_voice.wav
Week02_Lab1A_Sampling/  Week03_Lab1B_Convolution/  Week04_zTransform/
```

## Running a notebook

Every notebook is already executed, so all outputs, figures and printed results
are stored in the file and visible in the PDF without running anything.

```bash
pip install numpy scipy matplotlib jupyter
cd Week02_Lab1A_Sampling
jupyter notebook COU07506_Week02_240242413094.ipynb
```

Then choose **Kernel → Restart & Run All**. Keep the `data/` folder beside the
notebook: the audio tasks read `data/my_voice.wav`, and fall back to a synthetic
test tone only if the file is missing.

## Audio

`data/my_voice.wav` is a 3.5-second American-English Harvard-sentence recording
from the **Open Speech Repository**, file `OSR_us_000_0010_8k.wav` (female
speaker), 16-bit PCM at 8 kHz:

<https://www.voiptroubleshooter.com/open_speech/american.html>

The repository states that the material may be freely copied, downloaded and
incorporated into other work provided the source is identified as "Open Speech
Repository". That citation appears in the audio task of each notebook.
