# Vue-Video-Player

This is a fork of [Vue Video Player](https://github.com/surmon-china/vue-video-player) including the following changes:

- Upgrade video.js to 7.0.0
- Remove `videojs-contrib-hls`
- Remove `videojs-contrib-flash`

### Installing

1. Add this to your package file, under dependencies: 

```
"vue-video-player": "git+https://github.com/MosheAtOwal/vue-video-player.git",
```

2. Run `yarn`


### Using in Vue

1. Add these imports to your component:

``` 
import 'video.js/dist/video-js.css'
import {videoPlayer as VueVideoPlayer} from 'vue-video-player'
```

2. Register `VueVideoPlayer` in `components`.
3. You're ready to use `<vue-video-player... >` in your template.

### Notes

- Reference the original repo for more documentation.
- This is for internal use, but public because it's simpler than setting up private npm modules etc.
- Use as-is, at your own risk. No warranty, etc, etc.
