# htMarquee Animated Poster Pack

Free, ready-to-drop-in animated movie posters for [htMarquee](https://htmarquee.com).

<p align="center">
  <img src="docs/wonder_woman_demo.gif" alt="Wonder Woman" width="200">
  <img src="docs/back_to_the_future_demo.gif" alt="Back to the Future" width="200">
  <img src="docs/pacific_rim_demo.gif" alt="Pacific Rim" width="200">
</p>
<p align="center">
  <img src="docs/avatar_fire_and_ash_demo.gif" alt="Avatar: Fire and Ash" width="200">
  <img src="docs/stargate_demo.gif" alt="Stargate" width="200">
  <img src="docs/jurassic_park_demo.gif" alt="Jurassic Park" width="200">
</p>
<p align="center">
  <em>A sample of what's in the pack &mdash; Wonder Woman &bull; Back to the Future &bull; Pacific Rim &bull; Avatar: Fire and Ash &bull; Stargate &bull; Jurassic Park</em>
</p>

## Download

Grab the latest pack from **[Releases](https://github.com/htMarquee/poster-pack/releases)**. Each release is a set of portrait MP4 clips at 1296&times;1920, ready to upload to htMarquee.

## What's in the pack

Hand-curated animated posters for popular titles &mdash; gentle camera drift, atmospheric particles, subtle lighting shifts.

## About htMarquee

[htMarquee](https://htmarquee.com) turns a 4K TV into a smart home-theater lobby sign. It runs on a Raspberry Pi 5, cycles movie posters in portrait at 60 FPS with GPU-accelerated transitions, plays trailers, and switches to a "Now Playing" view the moment Plex or Jellyfin hits play. Animated posters make the lobby feel alive between transitions &mdash; this pack is a free way to stock your display with them on day one.

## How the posters are made

Every poster in this pack is generated with **[PostAnimate](https://github.com/htMarquee/PostAnimate)**, an open-source CLI and Python library that drives AI image-to-video models through [PiAPI](https://piapi.ai). PostAnimate supports 11 models (Kling, Luma, Veo 3, Hailuo, Wan, and others) and preserves the exact 27:40 movie poster aspect ratio.

If you want to generate your own animated posters &mdash; for movies not in this pack, or with different motion styles &mdash; grab PostAnimate and point it at any poster image.

## Installation

1. Download the latest pack from [Releases](https://github.com/htMarquee/poster-pack/releases) and unzip it.
2. Open your htMarquee web app (typically at `http://htmarquee.local/app`).
3. Find the movie you want to animate and open its movie card.
4. Use the **Upload Animated Poster** option on the card to upload the matching MP4 from the pack.
5. The animated poster will appear the next time that movie cycles through the slideshow.

## Contributing

Requests for specific titles are welcome &mdash; open an issue with the movie name and (if possible) a TMDB ID. Pull requests adding new posters are also welcome; see [PostAnimate](https://github.com/htMarquee/PostAnimate) for how to generate new clips.

## License

Posters are provided free for personal use with htMarquee. Movie posters themselves remain the property of their respective studios; the animation layer is derivative work intended for non-commercial home-theater display.
