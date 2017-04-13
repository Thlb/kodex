# Kodex

![Ghost version](https://img.shields.io/badge/Ghost-0.11.x-brightgreen.svg?style=flat-square)

Kodex is a theme designed for [Ghost](https://github.com/TryGhost) with a timeline main page.

More precisely, it's a fork of Ghost default theme : [Casper](https://github.com/TryGhost/Casper).

It takes again the bases of Casper and is enhanced by the same features of awesome [Odin's](https://github.com/h4t0n/odin) theme. The main page display the posts with a timeline.

Any suggestion? report a bug? Open an Issue !

Hope you'll enjoy this theme !

## Features
* Tested with Ghost 0.11.7
* Display post's list as a timeline (main page + author posts).
* Display individual post with Casper display
* Fully responsive (for mobiles and tablets)
* Google Analytics (configurable by code injection in the admin area)
* [Pace](http://github.hubspot.com/pace/docs/welcome/) loading progress bar (configurable by code injection in the admin area)
* [Disqus](https://disqus.com) comments (configurable by code injection in the admin area)
* [Prism](http://prismjs.com/) Syntax Highlighting (no configuration needed)
* [RRSSB](https://github.com/kni-labs/rrssb) Social Sharing Buttons (no configuration needed)
* [Font Awesome](http://fontawesome.io) home page Social Link Icons (configurable by code injection in the admin area)

## Demo
Live demo [here!](https://kodex.while-true.io) 

## Installation
Clone or download the content of this repository inside your Ghost theme folder.

```bash
$ cd /path-to-ghost-root
$ git clone https://github.com/thlb/kodex/.git content/themes/kodex
```

Then restart Ghost, and select the theme on the Admin control pannel.

## Configuration

### Disqus
Coming soon...

### Pace

Pace's Javascript is already included. You just have to specify the theme of the progress bar.
Choose a theme [here](http://github.hubspot.com/pace/docs/welcome/), and paste the css code in the code injection (admin area).

Here's the css code of the 'minimal' theme :

```html
<style>
.pace {
  -webkit-pointer-events: none;
  pointer-events: none;

  -webkit-user-select: none;
  -moz-user-select: none;
  user-select: none;
}

.pace-inactive {
  display: none;
}

.pace .pace-progress {
  background: #29d;
  position: fixed;
  z-index: 2000;
  top: 0;
  right: 100%;
  width: 100%;
  height: 2px;
}
</style>
```

### Google Analytics
Coming soon...

### Font Awesome
Coming soon...

### RRSSB
No configuration needed...

### Prism
No configuration needed...

## Copyright & License

Released under the MIT License.  

