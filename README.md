# Adaptive Layout Engine for Multi-Surface Ads

This project is a small browser-based tool that takes one ad creative and automatically adapts it to different advertising formats.

Instead of creating a separate design for every platform and screen size, the engine looks at the size and shape of the surface and decides how the content should be arranged.

I built it using plain HTML, CSS, and JavaScript, so there is no framework, npm setup, or build process involved.

## Live Demo

https://karlnirmal.github.io/adaptive-layout-engine/

## What it does

You can enter:

- Brand name
- Headline
- Subheadline
- CTA text
- Image URL
- Accent color

The same content is then rendered across different ad formats, including Instagram Story, Instagram Feed, Facebook Feed, YouTube Thumbnail, X Post, Mobile Interstitial, Skyscraper, and Leaderboard Banner.

The interesting part is that the layouts are not simply resized or cropped versions of one design.

The engine first looks at the aspect ratio of the surface and classifies it as:

- Tall
- Portrait
- Square
- Landscape
- Wide

It then chooses a suitable layout for that category.

## Custom Surfaces

The project also allows you to create your own advertising surface.

For example, you can enter:

```text
Name: Pinterest Pin
Width: 1000
Height: 1500
