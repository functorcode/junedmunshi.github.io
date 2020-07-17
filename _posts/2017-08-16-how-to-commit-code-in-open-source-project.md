---
layout:     post
title:      "How to git commit your code into open source project"
date:       2017-08-16 12:00:00
author:     "Juned Munshi"
published: true
header-img: "img/post-bg-02.jpg"
---
## 7 simple steps
1. Fork the project repository
 ![]({{ site.url }}/img/postimages/github-fork-2017-08-17.png){:class="img-responsive"}
2. Clone forked repository
 ![]({{ site.url }}/img/postimages/github-clone-url-2017-08-17.png){:class="img-responsive"} <br>
Open terminal and execute following command. Replace url with yours.  
```
git clone git@github.com:junedmunshi/fb-bot-framework.git
```
3. Create new branch ("newfeature")
```
git branch newfeature
git checkout newfeature
```
4. Make modification
5. Test your code
6. Commit and push your code
```
git commit -am "YOUR Comment"
git push origin newfeature
```
7. Create new pull request
![]({{ site.url }}/img/postimages/github-pull-request-2017-08-17.png){:class="img-responsive"}

![]({{ site.url }}/img/postimages/github-pull-request-created-2017-08-17.png){:class="img-responsive"}


## Quick Tip: How to undo push
```
git push -f origin HEAD^:master
```
![]({{ site.url }}/img/postimages/github-undo-push-2017-08-17.png){:class="img-responsive"}
