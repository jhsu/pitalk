# PiTalk

24/7 webcam streaming with microphone.

* webcam
* microphone (preferably with a mute button)

## Requirements

* alsa
* nginx
* vlc (for streaming)

## Alsa

Make sure to select your microphone in `alsamixer` (`f4` then `f6`) and turn up
the volume.

## nginx

Authentication using basic auth and password file `htpasswd` in the same
directory as the `nginx.conf`.

## Notes

You may need to tweak `./bin/start_stream` settings for cvlc based on your
webcam.

This has only been tested on archlinux-arm.
