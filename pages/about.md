---
layout: mypost
title: 关于我
---

> Welcome！欢迎访问 Limpu's Blog

该博客托管于 GitHub Page，主题使用[tmaize-blog](https://github.com/TMaize/tmaize-blog)

## 联系我

- QQ&nbsp;&nbsp;&nbsp;&nbsp;: 3233796965

- GitHub: [limpu403](https://github.com/limpu403)

## 友链

友链请至[issue](https://github.com/Limpu403/limpu403.github.io/issues/6)留言

```
本站友链：
名称：{{ site.title }}
描述：{{ site.description }}
地址：{{ site.domainUrl }}{{ site.baseurl }}
头像：{{ site.domainUrl }}{{ site.baseurl }}/static/img/logo.jpg
```

<ul>
  {%- for link in site.links %}
  <li>
    <p><a href="{{ link.url }}" title="{{ link.desc }}" target="_blank" >{{ link.title }}</a></p>
  </li>
  {%- endfor %}
</ul>
