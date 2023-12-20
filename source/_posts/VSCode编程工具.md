---
title: VSCode编程工具
date: 2023-12-20
categories:
  - 大数据
  - 开发环境
tags:
  - 大数据
---

# idea 基本快捷键
- psvm + 回车  main方法
- sout + 回车  输出语句
- alt + 1 工程目录结构
- alt + 4 控制台
- ctrl + D 复制一行
- ctrl + X 剪切当前行
- ctrl + alt + L 格式化代码 
- alt + 回车 提示
- ctrl + / 注释
- alt + shift + 方向键上 上移当前行
- alt + shift + 方向键下 下移当前行
- alt + shift + 方向键左 跳转上一个停留位置
- alt + shift + 方向键右 跳转下一个停留位置

# Debug
- F7 步入 step into ，如果当前行有方法，可以进入方法内部，一般进入自定义方法，不会进入官方类库方法
- F8 步过 step over ，一行一行往下执行，如果这一行有方法不会进入方法
- shift + F8  单步执行到子函数内时，使用step out 就可以执行完剩余子函数代码，返回上一层函数。
- F9 resume program 如果下面代码没有断点，那么执行完全部代码，如果有断点，则跳转到下一个断点处。
