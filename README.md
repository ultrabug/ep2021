# Create beautiful and localized documentations and websites using MkDocs + Github

## Setup

```bash
$ python3 -m venv ep2021_venv
$ source ep2021_venv/bin/activate
(ep2021_venv) $ pip install -r requirements.txt
...
```

## Talk Abstract

In this talk I will walk you through all the steps needed to create and host feature rich and localized documentations (and even websites) using MkDocs + Github Pages.

MkDocs is a famous Python powered project used to build documentation for a lot of projects. It's based on Markdown and supports Markdown extensions, custom themes and plugins to extend its rendering capabilities.

But it did not support building documentations in multiple languages and this was a wanted feature since 2014...

After building documentations using MkDocs I decided to use it to switch my website and blog from Wordpress to a static page generator. I thus took on the challenge to contribute localization support to the MkDocs project because I needed it and it could benefit the community.

After 2 months of work, 175 comments and 85 commits over 55 files I'm glad that my PR have been merged and is part of the MkDocs 1.2 version.

I learned a lot along the way and I wanted to share my experience and a comprehensive walk through to get you ready and happy to use these new MkDocs features!
