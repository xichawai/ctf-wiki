本文旨在帮助信息安全爱好者快速入门 CTF 竞赛，提供了 CTF 竞赛各大题型的基础知识、常见题型及解题思路、常用工具等。

# 主要内容

## MISC

以诸葛建伟翻译的《线上幽灵：世界头号黑客米特尼克自传》和一些典型 MISC 题为切入点，内容主要包括信息搜集、编码分析、取证分析、隐写分析等。

## Crypto

主要包括古典密码学和现代密码学两部分内容，古典密码学趣味性强，种类繁多，现代密码学安全性高，对算法理解的要求较高。

## WEB

主要介绍了 WEB 安全中常见的漏洞，如 SQL 注入、XSS、CSRF、文件包含、文件上传、代码审计、PHP 弱类型等，WEB 安全中常见的题型及解题思路，提供了一些常用的工具。

## Reverse Engineering

主要介绍了逆向工程中的常见题型、工具平台、解题思路，进阶部分介绍了逆向工程中常见的软件保护、反编译、反调试、加壳脱壳技术。

## Mobile

主要介绍了安卓逆向中的常用工具和主要题型，安卓逆向常常需要一定的安卓开发知识，iOS 逆向题目在 CTF 竞赛中较少出现，因此不作过多介绍。

## PWN

PWN 题目主要考察二进制漏洞的发掘和利用，需要对计算机操作系统底层有一定的了解。在 CTF 竞赛中，PWN 题目主要出现在 Linux 平台上。

## CTF 竞赛模式

介绍了 CTF 竞赛的常见模式：解题、攻防、分享，并总结了几种模式的一些经验。

## CTF 学习与进阶

列出了 CTF 学习过程中可能会用到的一些网站、工具、OJ、书籍等资源。

# 使用说明

Github 仓库中包含本书所有 markdown 文件，本书采用 Gitbook 制作。

## Requirements

* NodeJS \(v4.0 and above is recommended\)

* Windows, Linux or Mac OS


## Install with NPM

```bash
npm install gitbook-cli -g
```

## 创建电子书

初始化

```bash
gitbook init
```

预览

```bash
gitbook serve
```

生成静态站点

```bash
gitbook build
```


