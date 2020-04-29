---
layout: page
title: "Arashi"
---
<style>
.index-content {
	margin-top: 30%;
	margin-bottom: 30%;
	font-size: 20px;
	line-height: 40px;
}
</style>

## Forewords

此站为堆砌平日的一些读书笔记与摘抄所用。对于歌词，日语的假名标注在html下极为好用，在自己开始学习日语以来，也是建立这个网站的一个契机。

我的个人网站与个人信息在此处不放链接。本身这个网站与个人网站是一个，后来因为个人网站毕竟和工作相关，没有必要让工作上有来往的人直接看到自己一大堆业余的兴趣爱好。于是单独放在GitHub小号上。此站的读者，如果机缘巧合来到这里，也请不要挖掘我的个人信息。毕竟自己没有刻意隐藏，挖出来也不是什么难事，但还是希望能把这些有的没的，和个人工作与生活分开。

敬请欣赏吧。

<body>
## Log

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

</body>
