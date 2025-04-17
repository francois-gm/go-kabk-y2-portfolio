# Fine-tuning

## 1. Questions / issues

Some questions from the class:

- How to create a pretty looking image-based multi-column index page?
- How to make image carrousels?
- How to implement a custom cursor?

### Multi-column index page

With CSS flexbox:

- See the CSS tricks [full guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- Or some more CSS tricks [Flexbox layout tips](https://css-tricks.com/dont-overthink-flexbox-grids/)

(see class tutorial files for more details on implementation)

### Image carrousels

Different possible JavaScript plugins (with straighforward implementation, but also various options):

- [Swiper](https://swiperjs.com/get-started#add-swiper-html-layout)
- [Slick](https://kenwheeler.github.io/slick/)
- [Flickity](https://flickity.metafizzy.co)
- Or also [PhotoSwipe](https://photoswipe.com) (does also "zoom" on images)

Or also, [a CSS only solution](https://css-tricks.com/css-only-carousel/) with the `snap-scroll` property.

### Custom cursors

With the CSS `cursor` property. You can use `.png` or `.svg` image files (with transparency).

```
cursor:url('../cursor/mycursor.png'), auto;
```

Where your cursor image is located under a folder named `cursor`, itself located in your `assets` folder.

## 2. Getting your website online

### Domain

A domain name is a unique name specific for your website, it's what you type in your address bar.

You can register domains separately but easiest is to get it together with hosting so that your domain and web server are automatically linked and setup.

Domains differ in price based on how popular/general a name is and the extension (i.e. '.com' is cheaper than '.io').

**Do you need a domain?**

Not necessarily.

If you don't mind a URL which isn't something like "yourname.lol" or "myname.xyz" or "studioname.com" then you can use things like GitHub Pages or Netlify to host your website and those come with their own default url, i.e. https://username.github.io or https://something.netlify.app.

### Hosting

Hosting is a service you buy to get server space allocated. For instance you can get 10GB space and pay a yearly fee. With this you usually get some extra services such as: email and FTP.

Before people can see your website that you put on your server you need a domain, as mentioned before it's easiest to get a domain and hosting together.

**How much space do you need?**

**5** **gigabytes** is more than enough. As explained in the using media section below you need to really take care of file size and this will reduce the costs needed for hosting.

### Hosting companies & domain providers

Make sure to compare prices between hosting & domain providers, it differs quite a bit! These companies offer both hosting and registering domains.

- [Vimexx](https://www.vimexx.nl/)
- [Namecheap](https://www.namecheap.com)
- [Webreus](https://www.webreus.nl)
- [Antagonist](https://www.antagonist.nl)
- [OVH](https://www.ovhcloud.com/nl/web-hosting/personal-offer/)
