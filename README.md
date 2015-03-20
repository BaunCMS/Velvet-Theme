# Velvet-Theme
A minimal blogging theme for [Baun](http://bauncms.com).

* Fully responsive (uses Bootstrap)
* Google Fonts
* HTML5 & CSS3
* Google Analytics Support
* Disqus Comments Support

![Velvet Theme](http://f.cl.ly/items/0r0D060E2r1a2F1V2E1f/w92qfiHoe2DkQAAAABJRU5ErkJggg==.png)

## Install

* [Download the latest version](https://github.com/BaunCMS/Velvet-Theme/releases) of Velvet
* Extract the folder into the `public/themes` folder of your Baun site
* Rename the folder to "velvet"
* In `config/app.php` set the `theme` to "velvet"

## Setup

### Show blog on the front page

To show the blog on the front page of your site create an `content/index.md` file and set
the `template` to "blog". For example:

    title: Home
    exclude_from_nav: true
    template: blog
    ----

### Setup Google Analytics

To setup Google Analytics tracking open up `layout.html` and un-comment the GA code in the `<head>` section.
Then replace `UA-XXXXXXX-XX` with your site ID.

### Setup Disqus Comments

To setup Disqus Comments open up `post.html` and un-comment the HTML. Then replace `example` with your disqus shortname.