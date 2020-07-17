---
layout:     post
title:      "How to install github project as module into nodejs project"
date:       2017-08-16 12:00:00
author:     "Juned Munshi"
published: true
header-img: "img/post-bg-02.jpg"
---
1. Add following under "dependencies" into package.json 
```
 "packagename":"username/reponame"
```
For example,
```
 "dependencies": {
    "fb-bot-framework":"junedmunshi/fb-bot-framework"
  }
```
 ![]({{ site.url }}/img/postimages/nodejs-add-repo-2017-08-17.jpg){:class="img-responsive"} 
2. Install
```
npm install
```
 ![]({{ site.url }}/img/postimages/nodejs-install-2017-08-17.jpg){:class="img-responsive"} 

