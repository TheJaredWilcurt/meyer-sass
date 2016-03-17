<img src="http://i.imgur.com/jlVfuJA.png" align="right" width="200" />

# meyer-sass
## Eric Meyer's CSS Resets in `.sass` format
### Resets the default styles in all browsers so they don't render things differently by default.

The Meyer resets are great at old browser compatibility and catching fringe cases. It is recommended that you load "Normalize.css" after this file as it is more up to date and will support more modern browsers and mobile better. They're a great team!

* * *

### Version

We keep the first two digits matching the latest Meyer Reset (`2.0`). The last one tells you if there are any updates in this repo (`.0`).

Code        | Version | Date
:--         | :--     | :--
Meyer Reset | v2.0    | 2011-01-26
meyer-sass  | v2.0.1  | 2016-03-17

* * *

### Use

1. Download [Node.js](http://nodejs.org) and install it
2. Run the command `npm install -g bower`
3. In your project folder run `bower install meyer-sass --save`
4. Then copy **one** of the following lines and paste it at the top of your main Sass file

```
@import "..\bower_components\meyer-sass\_meyer.sass";
@import "..\bower_components\meyer-sass\_meyer-scss.scss";
@import "..\bower_components\meyer-sass\_meyer.min.css";
```

You will likely see visual changes occur in your website after using this. That is the point. Anything that looks different is something that would have looked different in at least one browser had you not used the reset. Manually correct all visual changes and your site will now be much less likely to have cross-browser CSS issues.

* * *

#### License

This repo and all of it's files are released into the **public domain**.

* http://github.com/TheJaredWilcurt/meyer-sass
* http://meyerweb.com/eric/tools/css/reset/
