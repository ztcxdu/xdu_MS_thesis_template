# What is XDUthesis_xelatex?

XDUthesis_xelatex is an *unofficial* XeLaTeX template for preparing bachelor, master, or doctor thesis in Xidian University.

# 西安电子科技大学学位论文LaTex模板


本模板根据https://github.com/103yiran/XDUthesis_xelatex修改而成，主要修复的问题有：
### 学硕论文封面冒号缺失
### 正文与页眉间距与学校模板不一致
### 参考文献插入会议论文格式不正确
### 偶数页页眉横线长度或左右位置异常

## 如何使用

* 论文和作者的相关信息可在XDUthesis.cfg文件中进行修改。

* 参考文献在./bib/tex.bib文件中录入。百度学术和谷歌学术均支持BibTeX格式导出，但其中夹杂很多不规范的条目，应注意进行检查。


## 系统需求

本模板需要使用 XeTeX 引擎编译。Linux下编译时需首先配置windows系统中提供的SimSun和SimHei字体。模板验证无问题的平台为Debian 8 和TeX Live 2016。

## 知已问题
使用XeTeX时，AutoFakeBold选项导致复制乱码。模板中在`\begin{document}`后插入一个日文的空格'　'，使得除章节一级标题外其他内容可复制。


