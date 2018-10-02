# Hugo-LaosPR theme for LaosPR Hugo Edition

[Hugo-LaosPR](https://github.com/laospr/hugo-laospr) is ported from the [Hugo-Initio](https://miguelsimoni.github.io/hugo-initio-site/) template by [laospr.net](https://laospr.net/).

![ScreenShot](https://raw.github.com/laospr/hugo-laospr/master/images/hugo-laospr.png)

### Original Template Info

**Licensing:** Creative Commons (for more options, go to the [original template site](http://www.gettemplate.com/info/initio/))  
**Released:** Feb 21, 2014  
**Last Updated:** Feb 21, 2014  
**Version:** 1.0  
**Bootstrap:** 3.3.4 or higher  
**Libraries:** jQuery  
**Designer:** Sergey Pozhilov  

## Installation

```
$ cd /<your-hugo-site-directory>
$ git submodule add https://github.com/laospr/laospr.git themes/hugo-laospr
```

More info: [hugo setup guide](https://gohugo.io/overview/installing/)

## Configuration

[Example Site](https://github.com/laospr/hugo-laospr/tree/master/exampleSite)

[config.toml](https://github.com/laospr/hugo-laospr/tree/master/exampleSite/config.toml)

### Sections


```toml
showSubheader = true
showServices = true
showRecentWorks = true
showDownload = true
showClients = true

footerEnableContact = true
footerEnableFollowme = true
footerEnableTextWidget = false
footerEnableFormWidget = false
```
### Social Networks Icons

You can add as many social networks as you want in the params.social array following this template:

```toml
[[params.social]]
  title = "facebook"
  url = "https://www.facebook.com/lohn.xongmixay"
  icon = "fa-facebook-square"
  footer = true
  sharethis = true
  network = "facebook"
```

See the whole configuration in the [config.toml](https://github.com/laospr/hugo-laospr/tree/master/exampleSite/config.toml) file.

### Comments

Powered by [Netlify](https://www.netlify.com)

### Google Analytics

```toml
[params.google.analytics]
    trackerID = "GA-000000000-0"
```

Disable the Google Analytics by leaving `params.google.analytics.trackerID` empty.

### Almost there...

In order to see your site in action, you can run Hugo's built-in local server.

```
$ hugo server
```

Now enter [`http://localhost:1313/hugo-laospr-site/`](http://localhost:1313/hugo-laospr-site/) in the address bar of your browser.

## Deployment

- [Hosting on GitHub](https://gohugo.io/hosting-and-deployment/hosting-on-github/)
- [More hosting and deployment options](https://gohugo.io/hosting-and-deployment/)

## Contributing

- Found a bug?
- Got an idea for a new feature?

Let me know it using the [issue tracker](https://github.com/miguelsimoni/hugo-initio/issues).
Or make it directly: [pull request](https://github.com/miguelsimoni/hugo-initio/pulls).

## License

This port is released under the MIT License. Check the [original theme license](http://www.gettemplate.com/info/initio/) for additional licensing information.

## Thanks

Thanks to [Steve Francia](https://github.com/spf13) for creating Hugo and the awesome community around the project. And also thanks to [Sergey Pozhilov](http://www.gettemplate.com/) for creating this awesome theme.
# hugo-laospr
