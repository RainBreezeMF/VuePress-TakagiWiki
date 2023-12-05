---
title: 为什么我们选择了Vue/Vite作为站点构建器？
author: 一只鬆
category: 建设心得
date: 2023-08-17
---
我们在高木Wiki信息站与高木站点导航中分别应用到了VuePress与VitePress。

不过也可能有些时候可能会有人想问：为什么我们选择了这两个站点构建器？

VuePress是基于Vue.js的站点构建器，它简洁，快速，功能强大，而且为文档量身定制，我们可以快速用它建设我们需求的文档。

不过其实我们在早年的站点建设探索中是使用过其他站点框架的，比如Hexo与NotionNext，他们都曾经应用在我们的Wiki资料站上。

最早，我们使用的是NotionNext。这是一个很棒的基于Next.js的站点构建器，它使用Notion这个富文本编辑器作为后端，成功让不是很理解Markdown以及难以独自维护站点框架的用户也能很好的使用它制作一个属于自己的站点，但Notion在中国大陆境内糟糕的网络速度与Notion的文件诸多限制，使我们不得不放弃NotionNext，转向Hexo为我们新的资料站建设方向。

Hexo是一个不错的静态站点生成器，它的上手门槛也不算很高，但Hexo本身其实是博客框架，它似乎在博客框架道路上已经有些积重难返，基于此来写文档将会束手束脚。而且缺少热重载使得我们每次调试都需要重启开发服务器，它的生成站点速度也不能说很快，这些都大大延长了我们的站点开发时间。

所以，在其他人建议下，我们开始使用并学习VuePress的使用方法，最终完成了资料站的框架转型。

感谢你看到这里，我是一只鬆，希望你能够在这篇文章里得到更多有关建设站点的思路。

Tips: 我非常期望能够有更多热爱高木并且具备能力的开发者和爱好者加入我们的组织，一同参与站点建设，为高木站点的发展贡献自己的力量。我们将秉持开源精神，站点建设公开透明，站点仓库开源可查。