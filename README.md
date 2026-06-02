# ig-reels-media

mp4 hosting for Instagram Reels auto-publishing via Meta Graph API.

## Structure
```
reels/
  YYYY/
    MM/
      DD_<keyword>.mp4
```

## Raw URL pattern
```
https://raw.githubusercontent.com/pluscoach/ig-reels-media/main/reels/YYYY/MM/DD_<keyword>.mp4
```

## Purpose
Meta Graph API `video_url` parameter must be publicly accessible.
This repo serves as a stable CDN-grade host (raw.githubusercontent.com = Azure-backed).
