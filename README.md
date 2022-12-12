## Overview
![Computer Vision](https://img.shields.io/badge/AI-99-green)
![Spy](https://img.shields.io/badge/Spy-100-blue)
![Cute voice](https://img.shields.io/badge/Cute%20voice-35-red)

A face recognition software that tells you long you have been in front of your computer

**What does it do?**

- Uses your camara to keep an eye on you _(spoooky)_
- Greets and says farewell to you
- Waits for you to get back to work
- Times your working session

## How to use?

First of all, you need to have python3 and pip3 installed in your system.

I would recommend using a python virtual environment to avoid any dependencies conflict. [How to create a python virtual env](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/)

In your terminal:

```python
Install dependencies:
pip install -r requirements.txt

# Run with:
python3 main.py
```

### Recognising you

The program will need to take a couple of photos of you from different angles, for it to be able to recognise you.
_No worries, photos will not leave your project's folder so no need to comb your hair or anything_.

You can, on the other hand, skip this step and just upload your good-looking photos to the _faces_ folder.

### What now?

- Will use your webcam and run a timer while it is able to recognise your face 🙋.
- Once it is not able to see you anymore, it will give you a short update of your work time session ⏰
- It will wait for you to get back to start your next session 👋
- Have a fun productive day!

### Preview
![Screenshot](https://raw.githubusercontent.com/Danielratmiroff/myblog/master/images/watchmytime/screenshot.jpg)

## Outro

I do enjoy tracking my screen session times, I usually run some sort of timer to do so, having that automated with computer vision proved beneficial since I no longer need to remember to start nor end any session.

Plus, it is funny to be greeted by my computer when it sees me 😊
