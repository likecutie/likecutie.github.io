---
layout: default
title: "解决python环境下opencv找不到dll的问题"
date: 2020-01-09 21:01:16 +0800
---


# 问题重现

- 用conda安装的环境，突然提示找不到dll
- conda安装opencv使用`conda install opencv`

# 一个直接的解决方案

- 用pip覆盖安装一次解决问题
- `pip install opencv-python`

# 2020-01-21 新增

- base环境被其他开发软件破坏，删干净anaconda重装就可以用了
- 推荐使用miniconda，base坏了可删掉重装，envs可保留使用
