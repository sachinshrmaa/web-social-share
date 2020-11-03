
# Web Social Share 

In this repo, I'll show you how you can add social share link, buttons to your web applications.

### Top Social Sites
* Facebook
* Twitter
* LinkedIn

## Social Sharing with Anchor Tags

Use html anchor tags to share links on major social networks.

Basic URL Text Encoder: [http://meyerweb.com/eric/tools/dencoder/](http://meyerweb.com/eric/tools/dencoder/)


### Facebook

```
<a href="https://www.facebook.com/sharer/sharer.php?u={{request.build_absolute_uri}}" target="blank" >Facebook</a>
```
Naturally you can replace `{{request.build_absolute_uri}}` with your own link. Here I've used the social share in my django project. 


### Twitter

```
 <a href="https://twitter.com/share?url={{request.build_absolute_uri}}" target="blank">Twitter</a>
```
Similary to facebook, replace the `{{request.build_absolute_uri}}` with your own link.

Base URL :
``` 
<a href="https://twitter.com/share?url=">Share on Twitter</a>
```


### LinkedIn

Very similiar to Twitter and Facebook:

```
<a href="https://www.linkedin.com/sharing/share-offsite/?url={{request.build_absolute_uri}}" target="blank"> LinkedIn </a>
```
Base url:  
```
https://www.linkedin.com/sharing/share-offsite/?url=
```

Add your attributes to the base url as needed
```
url = https://www.sachinshrmaa.com/
# Your website's url

```





Feel free to fork and make changes, and I'd love to hear from you at twitter: @sachinshrmaa