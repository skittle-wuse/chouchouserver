---
layout: home
layoutClass: 'm-home-layout'

hero:
  name: 臭臭服务器
  text: 官网
  tagline: 臭臭服务器官网哦
  image:
    src: /logo.png
    alt: chouchouserver
  actions:
    - text: 茂茂物语
      link: https://notes.fe-mm.com
    - text: 前端导航
      link: /nav/
      theme: alt

features:
  - icon: 📖
    title: 进服指南
    details: 如果你是第一次游玩请看这里
    link: ./docs/404.html
    linkText: 新人指南
  - icon: 📘
    title: 服务器简介
    details: 关于服务器的很多信息
    link: ./docs/404.html
    linkText: 简介
---

<style>
/*爱的魔力转圈圈*/
.m-home-layout .image-src:hover {
  transform: translate(-50%, -50%) rotate(666turn);
  transition: transform 59s 1s cubic-bezier(0.3, 0, 0.8, 1);
}

.m-home-layout .details small {
  opacity: 0.8;
}

.m-home-layout .bottom-small {
  display: block;
  margin-top: 2em;
  text-align: right;
}
</style>
