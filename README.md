# My Personal Blog

This repo contains everything I need to run my blog <www.joshuaku.com>. The template was inspired from the template [Clean Blog Jekyll](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll). 

## Installation & Setup

### Using Docker

To keep this as simple as possible I am leveraging the [jekyll-serve](https://github.com/BretFisher/jekyll-serve) docker image to do local deployments for testing.

You can use the image that is hosted in [Docker Hub](https://hub.docker.com/r/bretfisher/jekyll-serve/) which is just the `latest` tag or you can build the image yourself to get the most updated packages before deploying. 

1. Make sure the `docker-compose.yml` file is in this repo
1. Run `docker-compose -d up`

### Non-Docker

Make sure you have ruby installed then run `bundle exec jekyll serve`

## Adding a new post

All posts are added to the `_posts` directory. For each post, include the following metadata to the head of the file

```markdown
---
layout: post
title: "Post Title"
subtitle: "This is the post subtitle."
date: YYYY-MM-DD HH:MM:SS
background: '/PATH_TO_IMAGE'
---
```
All post images are in the `img/posts` directory.

## Copyright and License

Just like the upstream repo, the code is released under the MIT license
