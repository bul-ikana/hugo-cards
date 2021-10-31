# Hugo cards

A Hugo theme, ported from [Webjeda-cards](http://webjeda.com/cards)

![Screenshot](https://github.com/bul-ikana/hugo-cards/blob/master/images/screenshot.png)

## Features

Responsive theme built on bootstrap. Great for showcasing content with featured images.

Easily add disqus, google analytics, social links and a facebook like box.

## Customization

### Images
To change the featured image of your post, you must provide a `img` param in your post front-matter. This theme now supports [page resources](https://gohugo.io/content-management/page-resources/) so your featured image should be in the same directory than your `index.md` post file.

If you don't include one, a default image will be used. You can also customize this default image by changing the `defaultImage` param in your theme config. Be aware that this default image should be located on your `static/images` directory

### CSS
There is a `custom.css` file included where you can write and override any style you need. If you need additional files, you can add their relative links to the `custom_css` param in the theme config.


## Configuration

Please see the sample [`config.toml`](https://github.com/bul-ikana/hugo-cards/blob/master/exampleSite/config.toml).

### Social links

#### facebook
A link to your facebook profile or page. This will show in the footer.

#### quora
A link to your quora profile. This will show in the footer.

#### twitter
A link to your twitter profile. This will show in the footer.

#### github
A link to your github profile. This will show in the footer.

#### email
Your email address. This will show in the footer and will opes as a `mailto:`.

### Facebook like box

#### fbLikeBox
Wheter you want to show a facebook like box. Accepted values are `yes` or `no`. Leave empty for `no`

#### fbAppId
The app id you obtained from facebook developers page.

#### fbPageUrl
A link to the facebook page or profile that will be shown in the like box.

#### fbPageTitle
The title of the like box. This text will be shown while the box is loading.

### Tracking and comments

#### analytics
The Google Analytics tracking ID supporting both Universal Analytics and GA4. Universal Anylitics will be used by default, unless`params.analytics.type` is set as `GA4`.

#### disqus
The disqus_thread ID
