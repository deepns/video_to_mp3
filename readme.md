# A simple app to convert mp4 to mp3 using moviepy library

This is a simple script to demo the usage of moviepy library to extract the audio stream out of an mp4 video file and save it to a mp3 file. Moviepy library makes it so easy to do that with just couple of calls.

## How to run

1. Download the code. Initialize the virtual environment and activate it.

```text
$ python -m venv .venv

$ source .venv/bin/activate
```

2. Install the dependencies

```text
$ pip3 install -r requirements.txt
```

3. Run the app

```text
(.venv) $ ./app.py -s 01@.mp4
MoviePy - Writing audio in 01@.mp3
MoviePy - Done
$
```
