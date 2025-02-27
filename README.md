# My Hugo Theme

This hugo theme is a fork of
[github.com/digitalcraftsman/hugo-cactus-theme](https://github.com/digitalcraftsman/hugo-cactus-theme)
started after I both realized it was no longer maintained and the recommended
fork had changed so much I couldn't switch to it without significant changes to
my blog.

## Original theme description

Cactus is a minimalistic theme for bloggers based on the default theme of the same-named [Cactus static site generator](//github.com/koenbok/Cactus) written in Python and [Nick Balestra](//github.com/nickbalestra/kactus)'s Jekyll port. Noteworthy features of this Hugo theme are the integration of a comment-system powered by Disqus, a customizable about page, support for RSS feeds, syntax highlighting for source code, and sharing options for blog posts.

### Please note that this theme is no longer maintained. 
*A fork of this theme can be found at [github.com/nodejh/hugo-theme-cactus-plus](https://github.com/nodejh/hugo-theme-cactus-plus)*


![Screenshot](https://raw.githubusercontent.com/digitalcraftsman/hugo-cactus-theme/dev/images/screenshot.png)


## Installation

Inside the folder of your Hugo site, run:

    $ cd themes
    $ git clone https://github.com/digitalcraftsman/hugo-cactus-theme.git

For more information, please read Hugo's official [setup guide](//gohugo.io/overview/installing/).

### The config file

Take a look inside the [`exampleSite`](//github.com/digitalcraftsman/hugo-cactus-theme/tree/dev/exampleSite) folder of this theme. You'll find a file called [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml).

To use it, copy the [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml) file to the root folder of your Hugo site. Feel free to change the strings as you like to customize your website.

Make sure to update the `themesDir` property in the config file to point to your site's theme folder, otherwise an error will be thrown indicating the themes folder is unable to be found.

## About page

Use the about page to introduce yourself to your visitors. You can customize the content as you like in the [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml). Furthermore, you should replace the [avatar placeholder](//github.com/digitalcraftsman/hugo-cactus-theme/blob/master/static/images/avatar.png) with a great image of yourself.

## Disqus

This theme features a comment system powered by Disqus too. Just add your Disqus-shortname to the [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml) and let readers respond to your blog posts.

## Social link icons

You can add a social link panel in the footer by adding entries to the `social` block in the [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml). You can choose between two icon fonts:

- [Font awesome](https://fortawesome.github.io/Font-Awesome/) or
- [Mono social icons](https://github.com/drinchev/monosocialiconsfont)

Assign either `font-awesome` or `mono-social` to the `iconFont` variable. The Mono social icons offer three styles of icons: circle, rounded, or default (empty).

## Nearly finished

To see your site in action, run Hugo's built-in local server.

    $ hugo server

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.


## Contributing

Found a bug or got an idea for a new feature? Feel free to use the [issue tracker](//github.com/digitalcraftsman/hugo-cactus-theme/issues) to let me know. Or directly make a [pull request](//github.com/digitalcraftsman/hugo-cactus-theme/pulls).

Please create a separate branch for your pull request.


## License

This theme is released under the MIT license. For more information read the [license](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/LICENSE.md).


## Acknowledgements

Thanks to

- [Nick Balestra](//github.com/nickbalestra/kactus) for creating the original theme
- [Steve Francia](//github.com/spf13) for creating Hugo and the awesome community around the project.
