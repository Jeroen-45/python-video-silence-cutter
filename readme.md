# A tool for removing silences from a video

**This tool is made to just work!**

It automatically cuts out all the silences from your videos. This is useful for, for example, shortening lecture recordings, or automating a 'first pass' edit for your own videos. This program was adapted from the [python script by DarkTrick](https://github.com/DarkTrick/python-video-silence-cutter), and has been made to work properly cross-platform and include some more options.

## Dependencies

- python3
- ffmpeg 
- ffprobe

You need to have all of those installed.

**@Windows users**:
Make sure, that the path to `ffmpeg` and `ffprobe` are inside the "path variable". I.e. you can run both commands from the command line like `C:> ffmpeg`.

## How to use

- Easiest command: <br>
`python silence_cutter.py [input_file]`

- Show **help** and more options: <br>
`python silence_cutter.py -h`

- All options: <br>
`python silence_cutter.py [-h] [-o OUTPUT_FILE] [-n NOISE_TOLERANCE] [-d MIN_DURATION] input_file`
