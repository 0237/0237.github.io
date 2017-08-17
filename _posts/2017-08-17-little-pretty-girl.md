---
layout: default
title:  "王尧小仙女"
date:   2017-08-17
published: true
category: jekylltest
---
> Github Pages 测试页

## 哼，
不听话一口吃了你

{{ site.time | date_to_xmlschema }}

{% highlight ruby linenos %}
def foo
  puts 'foo'
end
{% endhighlight %}


![小仙女]({{ site.url }}/assets/TIM图片20170817123936.jpg)

---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

---
<center>
Copyright © 2017 MYoung<br>
All Rights Reserved
</center>