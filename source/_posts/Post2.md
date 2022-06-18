---
title: hexo踩坑记录
date: 2022/6/17 hh:mm:ss # 时间
categories: # 分类
- Others
tags: # 标签
- hexo
- 踩坑
---
博客的环境是Hexo+Debian+GitHub

前前后后折腾了好几遍，记录一下踩坑的地方

* _config.yml 文件格式一定要保证正确，如 new_post_name 处的值不需要重复使用“：”
* 注意md文件的格式需与模板相匹配，建议先使用hexo new一个，再在生成的模板中撰写
* 有一个奇怪的bug，不知是不是我独有的现象：md文件命名为“blog1.md”时hexo g无法通过，会报错
* 遇见problem时有条件最好Google，会比Baidu和bing高效

**事物的发展不是径直遂愿的，是曲折向前的**
