# img

A simple bash script to create URLs for images on your computer. Idea stolen from [Paul Irish's dotfiles](https://github.com/paulirish/dotfiles/blob/master/.functions#L18).

Requires an [AWS](http://aws.amazon.com/) account and [s3cmd](http://s3tools.org/s3cmd).
    
### Warning

I have only tested this on OS X. And it is heavily hardcoded with my defaults. I will plan to generalize this later for a more user-friendly approach.  Feel free to make pull-requests if this is actually easy.

### Setup
Run:

    ln -s /path/to/git/repo/img /usr/local/bin/img

### Using img

To use img simply run `img file.ext`. I meant for it to work with images, but maybe anything? Not sure how AWS S3 deals with returning headers for other file-types.

## TODO
* Generalize for open-source goodness.
* Possibly rename, `img` is very generic, but works for now.
* Review this when not tired or delusional.