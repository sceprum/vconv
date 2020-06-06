# vconv
Python script to automate multiple files video conversion with ffmpeg and h264 codec

# Installation 

`sudo cp vconv /usr/bin/`

# Usage

Convert single file:
`vconv [-crf <h264 crf value>] /path/to/input/file.mp4 /path/to/input/out.mp4`

Convert multiple files
`vconv [-crf <h264 crf value>] file1.mp4 file2.mp4 file3.mp4 /path/to/output/dir`

Convert files by pattern
`vconv [-crf <h264 crf value>] GOPR*.MP4 /path/to/output/dir`

