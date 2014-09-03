## This is a gh-pages branch

Please visit http://financial-times.github.io/ui-style-guide to view the site

## Prerequisites

- Install node and npm from [npmjs.org](http://npmjs.org).  Check that it's installed by running `node --version`.
- Install [origami-build-tools](https://github.com/Financial-Times/origami-build-tools).

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

* Install Jekyll with `sudo gem install jekyll` (you will require administrative access to your machine to do this).  Hopefully you will see something like the below, but there'll be a delay where nothing happens for several minutes first:

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


## Restarting Jekyll
To run this Jekyll again the next time you turn on your computer follow the following steps. Open the terminal and change directory (type cd before) to the folder containing your local copy UI style guide.

```
cd /Users/paul.oneill/Workspace/ui-style-guide/
```
Then once inside this directory run a "watch", which sets Jeykll running.

```
jekyll serve --watch --baseurl=''
```
To turn Jekyll off press ctrl C in the terminal. The localhost link will stop working.


##Summary
Here's a quick summary of the steps needed to get Jekyll running on your local machine.

* Download the style guide from git hub and put in a new folder


* In terminal:

sudo gem install jekyll

(change directory to your new folder)

jekyll serve --watch --baseurl=''


* In folder:

Should now have a _site folder

Move all style guide files out of the ui-style-guide folder and into the parent folder 


* In your browser:

http://localhost:4000/

