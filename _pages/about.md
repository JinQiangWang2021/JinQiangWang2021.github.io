---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!DOCTYPE html>
<html>
<head>
<style>
  body {
    font-family: 'Georgia', serif; /* 英文字体 */
  }
  .chinese {
    font-family: 'SimSun', 'NSimSun', '宋体', 'SimHei', '黑体'; /* 中文字体 */
  }
</style>
</head>
<body>
<div class="chinese">


<!-- <span class='anchor' id='about-me'></span> -->
{% include_relative includes/intro.md %}
<hr style="border: 1px solid #C0C0C0;" />
{% include_relative includes/interests.md %}
<!-- <hr style="border: 1px solid #4B4B4B;" /> -->

<!--{% include_relative includes/news.md %}-->

 <hr style="border: 1px solid #C0C0C0;" /> 
{% include_relative includes/pub.md %}
<!-- <hr style="border: 1px solid #4B4B4B;" /> -->
<!--{% include_relative includes/honers.md %}-->
<!-- <hr style="border: 1px solid #4B4B4B;" /> -->
{% include_relative includes/others.md %}
<hr style="border: 1px solid #C0C0C0;" /> 
{% include_relative includes/society.md %}