<img src="http://i.imgur.com/jlVfuJA.png" align="right" width="200" />

# meyer-sass
## Eric Meyer's CSS Resets in `.sass` format

...and also `.scss`, `.less`, `.styl`, and manually minified CSS.

### Resets the default styles in all browsers so they don't render things differently by default.

The Meyer resets are great at old browser compatibility and catching fringe cases. It is recommended that you load "Normalize.css" after this file as it is more up to date and will support more modern browsers and mobile better. They're a great team!

Meyer Reset is **< 0.5 KB** when minified and gzipped (yes...less than half a KiloByte, ~460 bytes). Meaning that there is no reason not to use it. Even on old flip phones used in poorer countries with slow connections and low data caps, this is a completely acceptable addition to your payload. And in cases were you are targeting a wide range of devices like the ones mentioned above, you'll need these resets anyways.

* * *

### Version

We keep the first two digits matching the latest Meyer Reset (`2.0`). The last one tells you if there are any updates in this repo (`.0`).

Code        | Version | Date
:--         | :--     | :--
Meyer Reset | v2.0    | 2011-01-26
meyer-sass  | v2.0.1  | 2016-03-17

* * *

### Use

#### NPM

1. Download [Node.js](http://nodejs.org) and install it
2. In your project folder run `npm install meyer-sass --save`
3. Then copy **one** of the following lines and paste it at **the top of** your main Sass/LESS/Stylus file

```
@import "..\bower_components\meyer-sass\_meyer.sass";
@import "..\bower_components\meyer-sass\_meyer-scss.scss";
@import "..\bower_components\meyer-sass\_meyer.min.css";
@import "..\bower_components\meyer-sass\_meyer.less";
@import "..\bower_components\meyer-sass\_meyer.styl";
```

#### Bower

1. Download [Node.js](http://nodejs.org) and install it
2. Run the command `npm install -g bower`
3. In your project folder run `bower install meyer-sass --save`
4. Then copy **one** of the following lines and paste it at **the top of** your main Sass/LESS/Stylus file

```
@import "..\bower_components\meyer-sass\_meyer.sass";
@import "..\bower_components\meyer-sass\_meyer-scss.scss";
@import "..\bower_components\meyer-sass\_meyer.min.css";
@import "..\bower_components\meyer-sass\_meyer.less";
@import "..\bower_components\meyer-sass\_meyer.styl";
```

You will likely see visual changes occur in your website after using this. That is the point. Anything that looks different is something that would have looked different in at least one browser had you not used the reset. Manually correct all visual changes and your site will now be much less likely to have cross-browser CSS issues.

* * *

#### License

This repo and all of it's files are released into the **public domain**.

* http://github.com/TheJaredWilcurt/meyer-sass
* http://meyerweb.com/eric/tools/css/reset/
