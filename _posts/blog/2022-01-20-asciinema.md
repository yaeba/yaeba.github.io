---
title: "Asciinema: Terminal Session Recorder"
excerpt: "Record and share your terminal session"
toc: true
tags:
  - terminal
---

<div id="welcome"></div>
<script src="/assets/js/asciinema/asciinema-player.min.js"></script>
<script>
    AsciinemaPlayer.create("/assets/asciicast/welcome.cast", document.getElementById("welcome"), {
        autoplay: true,
        loop: true
    });
</script>

## Useful links

First and foremost, open these in new tabs. They are amazing documentations from official sources.

- [asciinema.org](https://asciinema.org/){:target="\_blank"}
- [github.com/asciinema/asciinema](https://github.com/asciinema/asciinema/){:target="\_blank"}, recorder
- [github.com/asciinema/asciinema-player](https://github.com/asciinema/asciinema-player/){:target="\_blank"}, web player
- [github.com/asciinema/asciinema-server](https://github.com/asciinema/asciinema-server/){:target="\_blank"}, web app hosting asciicasts
- [github.com/asciinema/asciicast2gif](https://github.com/asciinema/asciicast2gif/){:target="\_blank"}, helper to convert to GIF

## How is "asciinema" pronounced?

> [as-kee-nuh-muh].\
> The word “asciinema” is a combination of English “ASCII” and Ancient Greek “κίνημα” (kínēma, “movement”).

> <cite>Marcin Kulik, founder of asciinema project</cite>

## Key points

**Info:** Currently asciinema only supports \*nix and macOS. Windows users could still use asciinema in WSL Linux distro as a workaround.
{: .notice--info}

1. In a nutshell, `asciinema` is a recorder that captures user input and output (stdout and stderr) in the terminal. It does this by utilizing [pseudo-terminal](http://en.wikipedia.org/wiki/Pseudo_terminal) to capture all data going in & out to terminal, timestamp it and save it to a file.
2. The file is in [asciicast](https://github.com/asciinema/asciinema/blob/master/doc/asciicast-v2.md) format (JSONL) and is comparatively smaller than video format such as mp4 and mov. This is because it only contains stream of text to be played back in a compatible terminal emulator.
3. The recorded asciicast file can be re-played back in the terminal easily. You can also use the open-source `asciinema player` to embed the player in your website.
4. asciicast file can also be uploaded to the public [asciinema.org](https://asciinema.org/) which allows the recording to be watched and shared on the web.
5. Even better, one could also host a non-public `asciinema server` instance for private use.
6. Lastly, the asciicast file can also be converted to gif using `asciicast2gif` for better compatibility. For example, the gif can be uploaded to websites such as [Medium](https://medium.com/) which don't support embedding script tag.

## Installation

Latest asciinema release can be easily installed with pipx or pip.

```bash
pipx install asciinema
# or
python3 -m pip install asciinema
```

## Usage

1. To record a terminal session,
   ```bash
   asciinema rec output.cast
   ```
   This will save the recording to `output.cast` which can be uploaded or used for playback.\
   One useful option is to include `-c <command>` which overwrites the default SHELL command to record. For eg, one could do `-c "tmux attach -t <session>"` to record a tmux session.
2. To playback the recording in terminal,
   ```bash
   asciinema play output.cast
   ```
   Keep in mind that this only plays back the recording and does not re-execute all the commands in the recorded terminal session.
3. To upload the recording to public asciinema.org
   ```bash
   asciinema auth
   asciinema upload output.cast
   ```
4. To convert the recording to gif
   ```bash
   npm install --global asciicast2gif
   asciicast2gif output.cast output.gif
   ```

## Demo

### 1. Record

<div id="demo-record"></div>
<script>
    AsciinemaPlayer.create("/assets/asciicast/demo-record.cast", document.getElementById("demo-record"), {
        speed: 2,
        idleTimeLimit: 1
    });
</script>

### 2. Playback

<div id="demo-playback"></div>
<script>
    AsciinemaPlayer.create("/assets/asciicast/demo-playback.cast", document.getElementById("demo-playback"));
</script>
