<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>TikTok-style Video Page</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="container">
<div class="video-col">
<div class="video-wrap">
<video id="mainVideo" playsinline muted loop preload="metadata">
<source src="https://interactive-examples.mdn.mozilla.net/media/cc0-videos/flower.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>


<div class="overlay-top">
<div class="logo">@marcelodesignx</div>
</div>


<div class="overlay-bottom">
<div class="icon-btn" id="likeBtn" title="Like" aria-pressed="false">
<div class="icon">❤</div>
<span id="likeCount">1.2k</span>
</div>
<div class="icon-btn" id="commentBtn" title="Comment">
<div class="icon">💬</div>
<span>234</span>
</div>
<div class="icon-btn" id="shareBtn" title="Share">
<div class="icon">⤴</div>
<span>Share</span>
</div>
</div>
</div>


<div class="controls">
<button class="btn" id="playPause">Pause</button>
<button class="btn secondary" id="muteToggle">Unmute</button>
<div class="hint">Click video to toggle play/pause. Replace the video source with your own MP4 or HLS stream.</div>
</div>
</div>


<aside class="meta-col">
<div class="meta-card">
<div class="creator">
<div class="avatar">MD</div>
<div class="user-info">
<h3>marcelodesignx <small class="muted">@marcelodesignx</small></h3>
<p class="muted">Designer • Motion • UX</p>
<div class="follow">
<button class="btn" id="followBtn">Follow</button>
</html>
