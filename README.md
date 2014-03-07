## This is a gh-pages branch

Please visit http://financial-times.github.io/ui-style-guide to view the site

## Building

Since this is a GitHub pages site, built CSS and JS bundles must be committed to the repository.  We store them in `buildcache` to avoid any confusion - these files should not be edited.  To regenerate them, use Grunt:

1. Clone the repo
1. Type `npm install` in terminal, from the directory in which you cloned the repo
1. Edit main.scss and main.js as desired
1. Type `grunt` (or if you prefer, `grunt js` or `grunt css`)

Unless upgrading the bower dependencies or editing main.scss or main.js, you should not need to rebuild.

## Testing locally

This site uses [Jekyll](http://jekyllrb.com/).  To generate pages locally on a Mac OS X machine:

* You should already have Ruby if you have a Mac with XCode installed.  To check this, run Terminal and type `ruby -v`.  You should see something like:

```
[user.name@FT-12345 style-guide]$ ruby -v
ruby 2.0.0p247 (2013-06-27 revision 41674) [universal.x86_64-darwin13]
```
* You also need to check if command line tools are installed for xcode

* Install Jekyll with `sudo gem installl jekyll` (you will require administrative access to your machine to do this).  Hopefully you will see something like this:

```
[user.name@FT-12345 style-guide]$ sudo gem install jekyll
Password:
Fetching: liquid-2.5.5.gem (100%)
Successfully installed liquid-2.5.5
Fetching: jekyll-1.4.3.gem (100%)
Successfully installed jekyll-1.4.3
Parsing documentation for liquid-2.5.5
Installing ri documentation for liquid-2.5.5
Parsing documentation for jekyll-1.4.3
Installing ri documentation for jekyll-1.4.3
2 gems installed
```

* From the directory you cloned this module in, run `jekyll serve --watch --baseurl=''` to run Jekyll and create a web server (by default on port 4000):

```
[user.name@FT-12345 style-guide]$ jekyll serve --watch --baseurl=''
Configuration file: /Users/user.name/sandboxes/local/style-guide/_config.yml
            Source: /Users/user.name/sandboxes/local/style-guide
       Destination: /Users/user.name/sandboxes/local/style-guide/_site
      Generating... done.
 Auto-regeneration: enabled
    Server address: http://0.0.0.0:4000
  Server running... press ctrl-c to stop.
```

* Now you can view the site on your browser at [http://localhost:4000](http://localhost:4000).  Every time you make a change, the site will update automatically (except changes to main.js or main.scss, for which, see the Building section above)
