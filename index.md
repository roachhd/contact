---
layout: page
title: Bootstrap 4 Github Pages
---

[![GitHub Repo stars](https://img.shields.io/github/stars/nicolas-van/bootstrap-4-github-pages?style=social)](https://github.com/nicolas-van/bootstrap-4-github-pages)

A [Bootstrap 4](https://getbootstrap.com/) template project for [Github Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/).

Step into the dynamic realm of `ROACH HAUS PHOTOGRAPHY`, where sports action freezes in exhilarating moments, events come alive with vibrant energy, and portraits unveil the essence of people and their beloved pets. From the intensity of competitive sports to the joy of celebratory events, each image tells a unique story, capturing the passion, spirit, and connection within every frame. Whether it’s the thrill of victory on the field, the warmth of family gatherings, or the playful antics of furry companions, `ROACH HAUS` expertly immortalizes these moments with finesse and artistry

#GeoSnapShot Events
####View and Buy your photos
<iframe src="https://geosnapshot.com/RoachHaus/events?embed=true" allow="camera; geolocation; clipboard-write" style="width: 98%;height: 800px; border: 1px solid #e6e7e8;"></iframe>

#The Great Ocean Road RUNNING Festival 
###14km paradise trail run 

<iframe id='mapmyfitness_route' src='https://www.mapmyride.com/routes/view/embedded/1523908795?width=600&height=355&elevation=true&info=true&line_color=E6f749a5&rgbhex=a549f7&distance_markers=0&unit_type=metric&map_mode=SATELLITE&show_marker_every=1&last_updated=2017-04-18T23:51:23+00:00' height='658px' width='100%' frameborder='0' /><div class="jss1361" id="embed-frame-footer"><a rel="noopener noreferrer" target="_blank" href="https://www.mapmyride.com/routes/view/1523908795" class="jss1362"><p class="MuiTypography-root jss1363 MuiTypography-body1" string="View Route Details">View Route Details</p></a><div class="jss1364"><p class="MuiTypography-root jss1365 jss1386 MuiTypography-body1">Create routes or search for a route at <span><a rel="noopener noreferrer" target="_blank" href="https://www.mapmyride.com/" string="MapMyRide." class="jss1363">MapMyRide.</a></span></p></div></div>

`OTHER`
---

### Change your theme

This website uses the [Minty](https://bootswatch.com/minty/) Bootstrap theme by default. And you don't want to use the same theme everyone else uses do you?

You can of course modify anything in the `_includes`, `_layouts` and `_sass` folders to customize both the HTML or CSS of your website, possibly referring to the [Bootstrap documentation](https://getbootstrap.com/) or the [Jekyll documentation](https://jekyllrb.com/) when needed. This is a normal part of web development and it is outside the scope of this guide.

But if you don't know where to start I can recommend you to import a theme from [Bootswatch](https://bootswatch.com/).

* Go on [Bootswatch](https://bootswatch.com/) and choose a theme that you like.
* Using the top bar, download its `_variables.scss` and `_bootswatch.scss` files.
* Copy the content of `_variables.scss` in `_sass/_variables.scss`.
* Copy the content of `_bootswatch.scss` in `_sass/_bootstrap_customization.scss`.

That's it, you now have a totally different appearance for you website.

### Modify the content

You probably don't want the present guide to be the front page of your website, so you should edit the `index.md` file. You probably also want to edit or delete the `CONTRIBUTING.md`, `README.md` and `LICENSE.md` files.

Aside from that you can of course create new pages and posts like with any Jekyll website by refering to the [Jekyll documentation](https://jekyllrb.com/).

### Run Jekyll on your computer to speed up testing

Editing your website's content or theme directly on Github is completely possible but, due to the time Github Pages takes to update your website, it will probably be much more effective to work using a local Jekyll installation.

To do so:

* Install the [requirements for Jekyll](https://jekyllrb.com/docs/installation/).
* Type `bundle install` at the root of your project to install the necessary Ruby dependencies.
* Type `bundle exec jekyll serve` to launch the test Jekyll web server that will re-compile your work if you edit it.
* You can then open `http://localhost:4000` in your web browser to see your work-in-progress website.

Please note that, to ensure maximum compatibility with Github Pages, the `Gemfile` of this project references the `github-pages` gem, not Jekyll directly. This implies some differences in behavior compared to the official documentation of Jekyll.

## Known issues

* Bootstrap 4 should normally be post-processed using [Autoprefixer](https://github.com/postcss/autoprefixer). Even if it is possible to use autoprefixer with Jekyll, it is not possible with a classic Github Pages installation without adding some kind of pre-processing before publication. Since this project mostly aims compatibility with Github Pages I prefer to keep it that way. The consequences of this choice is that some Bootstrap features could not work as expected on older browsers.

## How to contribute

Like this project ? [Consider adding a star on Github](https://github.com/nicolas-van/bootstrap-4-github-pages).

[You can also see the contribution guide](https://github.com/nicolas-van/bootstrap-4-github-pages/blob/master/CONTRIBUTING.md).

## Websites using Bootstrap 4 Github Pages

* [My personal blog](https://nicolas-van.github.io/)
* [the wavelet's profile](https://thewavelet.github.io/)
* [William Moore's website](https://will2bill.com/)
* [roseblood.github.io](https://roseleblood.github.io/)
* [borislouis.github.io](https://borislouis.github.io/)
* [dariusnwadike.github.io](https://dariusnwadike.github.io/)
* [libcoap.net](https://libcoap.net/)

## Other Github Pages related projects

I'm a fan of Github Pages for the possibilities it offers to anyone to publish a website for free. I have multiple projects that could be of interest if that's your case too:

* [Easy Markdown to Github Pages](https://nicolas-van.github.io/easy-markdown-to-github-pages/)
* [Parcel Github Pages Boilerplate](https://github.com/nicolas-van/parcel-github-pages-boilerplate)

