# NeuroBot
Speech Feature Extraction
The repository describes the feature extraction methods for speech signals.

Free speech datasets
OpenLSR: OpenSLR is a site devoted to hosting speech and language resources, such as training corpora for speech recognition, and software related to speech recognition.
VoxForge: VoxForge is now mirroring the LT and the Teleccoperation group Open Speech Data Corpus for German with 35 hours of speech from about 180 speakers.
Mozilla Speech: Mozilla Releases the world's Second Largest Public Voice Data Set on Nov 29th, 2017.
Open Data for Deep Learning
File description

feature_extraction_functions.py: a set of feature extraction functions from RDShi-SpeakerCount.
MFCC: Mel-frequency cepstral coefficients calculation.
MFCC.py, MFCCTest.py: Compute the MFCC feature.
FeatureExtraction.ipynb: Speech preprocessing, including loading data, pre-emphasis, framing, window, Fourier-transform, power spectrum, filter banks, mfccs and mean normalization.
Volume: volume calculation.
![](https://github.com/raj2199/NeuroBot/blob/main/Volume/VolumeTest.png?raw=true)


ZeroCR: Zero-Crossing Rate calculation.
![](https://github.com/raj2199/NeuroBot/blob/main/ZeroCR/ZeroCR.png?raw=true)

Pitch: Pitch calculation and pitch tracking.
![](https://github.com/raj2199/NeuroBot/blob/main/Pitch/pitch.png?raw=true)
![](https://github.com/raj2199/NeuroBot/blob/main/Pitch/pitchTrack.png?raw=true)

Timbre: spectrogram drawing.
![](https://github.com/raj2199/NeuroBot/blob/main/Timbre/spectrogram.png?raw=true)

VAD: EPD (End-Point Detection), or Speech Detection, or VAD(Voice Activity Detection).
![](https://github.com/raj2199/NeuroBot/blob/main/VAD/VAD01.png?raw=true)
![](https://github.com/raj2199/NeuroBot/blob/main/VAD/VAD02.png?raw=true)
