# London Hack && Tell website

This site should be serving at https://london.hackandtell.github.io and https://london.hackandtell.org


Check list of things London Hack and Tell uses for organizing:

 * [Meetup group](https://www.meetup.com/London-Hack-and-Tell/)
 * [Github org](https://github.com/londonhackandtell)
 <!-- * FIXME JD: [Google doc signup form](https://docs.google.com/forms/d/15F33kAQFgI825JECUI7uAqXrdgbr1dkjO0DRK4MOKq4/viewform) -->
 <!-- * FIXME JD: [Google doc for notes](https://docs.google.com/document/d/1DM_qVHEGPNP-UzSGKNlee8lmroNqap4Fg4RgERxxTiY/edit) -->
 * [Twitter account](https://twitter.com/lndhackandtell)
 * Gmail account

## Editor's notes

To build and serve the site locally:

    jekyll serve

then visit [http://127.0.0.1:4000/](http://127.0.0.1:4000/)

To add a new post, put it in the correct directory under `_posts/{year}`.

#### Ubuntu 16.04 installation pre-reqs

This should be enough to build the site:

    sudo apt-get install jekyll

### Mac OS X (10.13.4 High Sierra) installation with brew

Step by step this is how to go about this. First, check ruby version

    $ ruby -v
    ruby 2.3.3p222 (2016-11-21 revision 56859) [universal.x86_64-darwin17]

Install the jekyll gem (package)

    $ sudo gem install jekyll

Verify installation with

    $ jekyll -v
    jekyll 3.8.1
