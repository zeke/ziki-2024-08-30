This repository contains training data for a Flux image generation model.

https://replicate.com/zeke/ziki-2024-08-30

## How it works

The training data is a series of frames extracted from a short video of me spinning around in front of a green screen.

## Extract frames from a video

1. Edit [PROMPT.md](PROMPT.md) and describe the task in plain English.
2. Run `npm i -g yolox && yolox PROMPT.md` to magically turn PROMPT.md into a working shell command and run it.
3. 🎉 Voila! Video turns into frames.