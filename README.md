# RTBT: Predictive Real-Time Beat Tracking from Music for Embedded Application

RTBT implements the algorithm introduced in the following [paper](https://ieeexplore.ieee.org/abstract/document/8397024):
```
Predictive Real-Time Beat Tracking from Music for Embedded Application.
Al-Hussaini, I., Humayun, A.I., Alam, S., Foysal, S.I., Al Masud, A., Mahmud, A., Chowdhury, R.I., Ibtehaz, N., Zaman, S.U., Hyder, R. and Chowdhury, S.S., 
2018 IEEE Conference on Multimedia Information Processing and Retrieval (MIPR)
```

#### The algorithm and demonstration through the standalone embedded system won an *Honorable Mention* in the *IEEE Signal Processing Cup 2017*.
## Video Demonstration

[![RTBT Demo](https://github.com/iah3/RTBT/blob/master/media/rtbt.PNG)](https://youtu.be/fyENs0ABZhw)

## Dependencies:

- Python (2.7)
- PortAudio Version 19

To install the required Python modules you can simply run the following in the terminal:
```
pip install -r requirements.txt
```
- Numpy
- Scipy
- ffmpeg
- PyAudio
- CFFI (C Foreign Function Interface for Python)
- Six (Python 2 and Python 3 compatibility library)
- serial (only required if paired with an Arduino)

## Basic Usage:

To run RTBT on the sample file, [sample.wav](https://github.com/iah3/RTBT/blob/master/media/sample.wav), run the following:
```
python test.py
```
[test.py](https://github.com/iah3/RTBT/blob/master/media/test.py) also contains other use cases in comments including processing music acquired through the microphone in real-time.

## Citation:
```
@inproceedings{al2018predictive,
  title={Predictive real-time beat tracking from music for embedded application},
  author={Al-Hussaini, Irfan and Humayun, Ahmed Imtiaz and Alam, Samiul and Foysal, Shariful Islam and Al Masud, Abdullah and Mahmud, Arafat and Chowdhury, Rakibul Islam and Ibtehaz, Nabil and Zaman, Sums Uz and Hyder, Rakib and others},
  booktitle={2018 IEEE Conference on multimedia information processing and retrieval (MIPR)},
  pages={297--300},
  year={2018},
  organization={IEEE}
}
```

Please read the [README.pdf](https://github.com/iah3/RTBT/blob/master/README.pdf) for details on running the code and the following [paper](https://ieeexplore.ieee.org/abstract/document/8397024) for details on the algorithm.
