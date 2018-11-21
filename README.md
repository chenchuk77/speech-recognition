# speech-recognition

This is a testing environment for voice recognition using python3

## Description

Creating a Python3 virtual environment and testing audio and mic

## Getting Started

### Dependencies

* python3-venv

### Installing and running

```
# creating python3 virtual env
python3 -m venv env

# activate
source env/bin/activate

# verify
chenchuk ~/dev/speech-recognition/ pip -V
pip 9.0.1 from /home/chenchuk/dev/speech-recognition/env/lib/python3.6/site-packages (python 3.6)

# back
chenchuk ~/dev/speech-recognition/ deactivate
chenchuk ~/dev/speech-recognition/ pip -V
pip 9.0.1 from /usr/lib/python2.7/dist-packages (python 2.7)

# installing packages
source env/bin/activate
pip install ipython
pip install SpeechRecognition

# install audio libs (for mic)\
sudo apt-get install python-pyaudio python3-pyaudio
sudo apt-get install portaudio19-dev
pip install pyaudio

```

## Acknowledgments

Inspiration, code snippets, etc.
* [speech recognition](https://realpython.com/python-speech-recognition)
* [virtual envs](https://realpython.com/python-virtual-environments-a-primer)
