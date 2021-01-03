Title: Pelican 101
Date: 2021-01-03 12:22
Modified: 2021-01-03 12:23
Category: Python
Tags: pelican, publishing
Slug: my-super-post
Authors: Ofa
Summary: recording for my learnings

# Building my site with Pelican from scratch

## First step, create github repos for both site and github pages, then
```
git clone https://github.com/username/repo.git
git submodule add https://github.com:username/username.github.io.git output
```

## Second step, install pelican with pipenv
```
pipenv install pelican
pipenv shell
```

## Third, initialize site config
```
pelican quickstart
```

And there will be a bunch of options editable afterward

```
Welcome to pelican-quickstart v4.5.3.

This script will help you create a new Pelican-based website.

Please answer the following questions so this script can generate the files
needed by Pelican.


> Where do you want to create your new web site? [.]
> What will be the title of this web site? SITENAME
> Who will be the author of this web site? USERNAME
> What will be the default language of this web site? [en]
> Do you want to specify a URL prefix? e.g., https://example.com   (Y/n)
> What is your URL prefix? (see above example; no trailing slash) https://username.github.io
> Do you want to enable article pagination? (Y/n)
> How many articles per page do you want? [10]
> What is your time zone? [Europe/Paris] 
> Do you want to generate a tasks.py/Makefile to automate generation and publishing? (Y/n)
> Do you want to upload your website using FTP? (y/N)
> Do you want to upload your website using SSH? (y/N)
> Do you want to upload your website using Dropbox? (y/N)
> Do you want to upload your website using S3? (y/N)
> Do you want to upload your website using Rackspace Cloud Files? (y/N)
> Do you want to upload your website using GitHub Pages? (y/N) y
> Is this your personal page (username.github.io)? (y/N) y
```