# MP3-Multimedia

MP3 files store audio data. Most MP3 files have a ID3v2 tag. In a ID3v2 there is other data stored - text, images and time stamp information. Combining this different data types in a smart war makes it possible to store multimedial user experiances in MP3 files.

This section presents samples - MP3 files containing multimedial user experiances.

# Some frames of a ID3v2 tag and their name

| Frame | Known as                           |
|:----- |:---------------------------------- |
| TCON  | Genre                              |
| TALB  | Album                              |
| TIT2  | Title                              |
| TRCK  | Track Nr.                          |
| TPE1  | Interpret                          |
| COMM  | Comment                            |
| TDRC  | Date of Recording (at least Year)  |
| APIC  | Image                              |
| SYLT  | Text and synchronising timestamps  |

# id3v2FrameList.py

This python script lists the frame names, found in the ID3v2.3 or ID3v2.4 tag of a MP3 file.

# mm01_presentation.mp3

Example of a MP3 multimedia file. It contains audio data, a cover image, 4 more images in the format 16x9 and text. The appearance of the text and the images is syncronised with the audio. Therefore the SYLT frame is used. 

# mm02__543210.mp3

Example of a MP3 multimedia file. It contains audio data, a cover image and text. The appearance of the text is syncronised with the audio. Therefore an experimental frame, called XSRT, is invented and used. This XSRT frame has a structure similar to the USLT frame. It contains the text in SRT format.
