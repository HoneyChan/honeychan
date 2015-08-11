# HoneyChan
#####A (heavily modified) instance of tinyboard/vichan running on HoneyChan
![](http://honeychan.net/static/mascots.png)
## HoneyChan Instance Structure
- instance-config.php contains the global configuration
- under /$board/config.php is each board specific configuration
- static content is found under /static/
- board specific static content is under /static/$board/
- flags are under /static/flags/
- board specific static flags are under /static/$board/flags/
- banners are found in /static/banners/
- the code for loading the banners is found in the file banners.php
- for the themes, the templates have been *modified*

#### Things to Note

- All HTML is minified
- Javascript is minified and then compiled into main.js

## Todo

- [ ] Add Caching Support
- [ ] Revamp Moderation Panel
- [ ] Add userstyles as built-in themes
- [ ] Create a Radio (shoutcast, ogg-stream)
- [ ] add post-hover.js to recent.html
- [ ] add thumbnails for most filetypes
- [ ] fix webm thumbnailing

