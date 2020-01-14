# gitbook

# 如何使用gitbook来管理我们的学习笔记


## 新建一个文件夹 hibernate 表示是hibernate的知识点汇总

## hibernate文件夹分别新建2个文件夹content docs

## 进入content文件夹执行 gitbook init

## 举例修改summar.md

# 目录

* [前言](README.md)
* [第一章](Chapter1/README.md)
  * [第1节：衣](Chapter1/衣.md)
  * [第2节：食](Chapter1/食.md)
  * [第3节：住](Chapter1/住.md)
  * [第4节：行](Chapter1/行.md)
* [第二章](Chapter2/README.md)
* [第三章](Chapter3/README.md)
* [第四章](Chapter4/README.md)

分别新建对应的文件夹即可

## 进入hibernate文件夹执行npm init -y  把项目转为node项目

## 修改当前文件夹的package.json

添加

​    

"scripts": {

        "build": "gitbook build ./content ./docs"

}, 


## 执行npm run build 编译

## 页面预览 gitbook serve (先cd到content目录)

## http://localhost:4000 

## gitbook.zip 为创建好的压缩模板 直接修改文件夹名称 即可创建新的笔记

## 博客参考

[https://www.jianshu.com/p/4e109a1113b2](https://www.jianshu.com/p/4e109a1113b2)

[https://blog.csdn.net/lu_embedded/article/details/81100704](https://blog.csdn.net/lu_embedded/article/details/81100704)

[https://chrisniael.gitbooks.io/gitbook-documentation/content/format/chapters.html](https://chrisniael.gitbooks.io/gitbook-documentation/content/format/chapters.html)

[https://cloud.tencent.com/developer/article/1449410](https://cloud.tencent.com/developer/article/1449410)

