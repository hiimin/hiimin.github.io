---
layout: post
title:  "클라우드 시대의 빅테이터 관리 전략"
date:   2019-05-17 11:00:00
author: jeongmin
categories: seminar
tags:	jekyll welcome
cover:  "/assets/instacode.png"
---

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

## 데이터 관리와 분석, 활용

현재 IT분야에서는 데이터 관리와 분석이 가장 중요시된다. 유투브도 Cloud라고 할 수 있다.(Cloud(공유)와 On-premise() 차이점 인지 필요)

### AI, BigData, IOT
IOT란 전기가 통하는 모든 장치들에 센서를 부착하여 네트워크를 이용해 제어하고 상태를 파악
이를 이용해 데이터를 수집해서 저장하여 분석 가능하다.

이때 엄청난 양의 데이터가 발생하고, 이 방대한 양의 데이터를 수집, 가공, 저장, 분석하는 것을 BigData라고 한다.

ai에서 가장 중요한 것은 데이터의 양
중국이 ai 강대국인 이유는 뭐든지 크고 많기 때문에 그만큼 데이터의 양이 많기 때문이다.

앞으로 프로그래머는 데이터 저장, 관리, 분석 능력이 중요된다.

[jekyll-archive][jekyll-archive]

### information
구글 애널리스틱 : 구글에서 무료로 제공하고 있는 웹분석 서비스 
가트너 : 올 해 가장 중요한 기술 분석 사이트
book review - 센스 

### 결론
db를 이용해서 데이터를 활용하는 능력이 가장 중요하다.

### Cover Images

To add a cover image to your post, set the "cover" property in the front matter with the relative URL of the image (i.e. <code>cover: "/assets/cover_image.jpg"</code>).

### Code Snippets

You can use [highlight.js][highlight] to add syntax highlight code snippets:

Use the [Liquid][liquid] `{% raw %}{% highlight <language> %}{% endraw %}` tag to add syntax highlighting to code snippets.

For instance, this template...
{% highlight html %}
{% raw %}{% highlight javascript %}    
function demo(string, times) {    
  for (var i = 0; i < times; i++) {    
    console.log(string);    
  }    
}    
demo("hello, world!", 10);
{% endhighlight %}{% endraw %}
{% endhighlight %}

...will come out looking like this:

{% highlight javascript %}
function demo(string, times) {
  for (var i = 0; i < times; i++) {
    console.log(string);
  }
}
demo("hello, world!", 10);
{% endhighlight %}

Syntax highlighting is done using [highlight.js][highlight]. You can change the active theme in [head.html](https://github.com/bencentra/centrarium/blob/2dcd73d09e104c3798202b0e14c1db9fa6e77bc7/_includes/head.html#L15).

### Images

Lightbox has been enabled for images. To create the link that'll launch the lightbox, add <code>data-lightbox</code> and <code>data-title</code> attributes to an <code>&lt;a&gt;</code> tag around your <code>&lt;img&gt;</code> tag. The result is:

<a href="//bencentra.com/assets/images/falcon9_large.jpg" data-lightbox="falcon9-large" data-title="Check out the Falcon 9 from SpaceX">
  <img src="//bencentra.com/assets/images/falcon9_small.jpg" title="Check out the Falcon 9 from SpaceX">
</a>

For more information, check out the [Lightbox][lightbox] website.

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
[highlight]:   https://highlightjs.org/
[lightbox]:    http://lokeshdhakar.com/projects/lightbox2/
[jekyll-archive]: https://github.com/jekyll/jekyll-archives
[liquid]: https://github.com/Shopify/liquid/wiki/Liquid-for-Designers
