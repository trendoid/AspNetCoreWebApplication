# AspNet Core Web Application
Sample ASP.NET Core Application for performance testing
## Inspiration

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Fresh out the box .net 6 MVC site deployed to azure with just a logo.<br>Google Lighthouse: 8/10 for speed.<br><br>Literally just rendering bootstrap, thoughts <a href="https://twitter.com/shanselman?ref_src=twsrc%5Etfw">@shanselman</a>? <a href="https://t.co/8FGQ7ZNnVy">pic.twitter.com/8FGQ7ZNnVy</a></p>&mdash; Jim (@GolfJimB) <a href="https://twitter.com/GolfJimB/status/1459386187940982785?ref_src=twsrc%5Etfw">November 13, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## Steps
There are several steps that depend on your content and testing environment. If you are hosting on Azure, you need to enable HTTP2. If you are testing locally, HTTP2 is probably already running.

You might also have to enable HTTPS with an SSL certificate. All the major cloud providers have mechanisms for free certs. You might also try free certs from [Let's Encrypt](https://letsencrypt.org).

If you are hosting on IIS, take a look at [Certify the Web](https://certifytheweb.com). It's a great GUI tool and not very expensive for production.

### Compression

### Caching

### Removed jQuery

### Added SVG Logo

### Converted other images to WebP

