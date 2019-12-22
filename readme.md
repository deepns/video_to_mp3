# A simple python app to extract audio from video using moviepy library

This is a simple script to demo the usage of moviepy library to extract the audio stream out of a video file and save it to a mp3 file. Moviepy library makes it so easy to do that with just couple of calls.

## Steps to run

1. Download the code. Initialize the virtual environment and activate it.

```text
$ python3 -m venv .venv
$ source .venv/bin/activate
```

2. Install the dependencies

```text
$ pip3 install -r requirements.txt
```

3. Run the app. Here is an example.

```text
(.venv) $ ./app.py -h
usage: app.py [-h] -s SOURCE

Extract audio from a video and save to mp3

optional arguments:
  -h, --help            show this help message and exit
  -s SOURCE, --source SOURCE
                        Source file to extract

(.venv) $ ./app.py -s 01@.mp4
MoviePy - Writing audio in 01@.mp3
MoviePy - Done
$
```

4. Deactivate the virutal environment once done.

```text
(.venv ) $ deactivate
```
