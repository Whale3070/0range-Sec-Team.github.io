---
ID: 196
post_title: Rundll32绕过applocker执行rubeus
post_name: 'rundll32%e7%bb%95%e8%bf%87applocker%e6%89%a7%e8%a1%8crubeus'
author: Meteors
post_date: 2021-08-07 13:24:13
layout: post
link: 'https://0range.team/2021/08/07/rundll32%e7%bb%95%e8%bf%87applocker%e6%89%a7%e8%a1%8crubeus/'
published: true
tags: [ ]
categories:
  - 域渗透
---
在玩儿htb prolab的时候遇到了委派无法执行rubeus的问题
执行rubeus.exe 进程有但是没回显，一通操作发现不是UAC的问题，那么应该是applocker
发现有大佬提前造好了轮子
使用rundll32来绕过applocker白名单的技术
![file](https://0range.team/wp-content/uploads/2021/08/image-1628313763861.png)

[github](https://github.com/rvrsh3ll/Rubeus-Rundll32 "github")