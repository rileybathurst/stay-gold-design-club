# Stay Gold Design Club

Partial working dev environment for a headless CMS Strapi working with Gatsby to have a running site.

## Partially Online

At this stage I am hosting the CMS on github but not as a live server, this is probably something I should deal with at some point but as it's a single author thing it really doesn't matter at this stage and I really want to just be able to showcase the speed of a system running SSG that I have built.
This also means that I don't have to have full build tools as everything just runs locally and I can control the system in that way pushing what I want live.

### Build

Following along to the [https://strapi.io/blog/building-a-static-website-using-gatsby-and-strapi](strapi tutorial)

#### Strapi
$ cd cms
$ strapi develop

#### Gatsby
$ cd blog
$ gatsby develop

Both need to be running to be locally working on the development
I think this handles all the webpack and sass compression as well?