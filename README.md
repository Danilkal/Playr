# Playr
Is a HTML5 Video and Audio on well as Bare
# Quick Setup
# HTML
### HTML5 Video
```html
<video id="player" playsinline controls data-poster="poster.jpg">
  <source src="video.mp4" type="video/mp4" />

  <!-- Captions are optional -->
  <track kind="captions" label="English captions" src="captions.vtt" srclang="en" default />
</video>
```
### YouTube and Vimeo
```html
<div class="playr__video-embed" id="player">
  <iframe
    src="https://www.youtube.com/embed/i8g7UdkGKFMc="
    allowfullscreen
    allowtransparency
    allow="autoplay"
      ></iframe>
</div>
```
or
```html
<div class="playr__video-embed" id="player">
  <iframe
    src="https://player.vimeo.com/video/772595268?h=787e6e12bc"
    allowfullscreen
    allowtransparency
    allow="autoplay"
  ></iframe>
</div>
```
```html
<script src="playr.js"></script>
<script>
  const player = new Playr('#player');
</script>
```
```html
<script src="https://https://danilkal.github.io/cdn/playr.js"></script>
```
## CSS
```html
<link rel="stylesheet" href="playr.css" />
```
```html
<link rel="stylesheet" href="https://danilkal.github.io/cdn/playr.css" />
```
