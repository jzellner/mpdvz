mpdvz
=====

VISUALIZE SHIT YO

instructions
------------

put this in your mpd.conf:

    audio_output {
        type    "fifo"
        name    "my_fifo"
        path    "/tmp/mpd.fifo"
        format  "44100:16:2"
    }

build:

    make

run:

    ./mpdvz

etc
---

inspiration and initial code from: http://stackoverflow.com/questions/21762412/mpd-fifo-python-audioop-arduino-and-voltmeter-faking-a-vu-meter
