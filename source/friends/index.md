---
title: friends
date: 2022-03-19 21:06:13
onlyTitle: false # 只显示title
toc: false # 不显示文章目录
# type: "friends" # 这个不要了
# layout: "friends" # 这个不要了
---



{% issues sites | api=https://api.github.com/repos/sakura-501/friends/issues?sort=updated&state=open&page=1&per_page=100&labels=active %}


