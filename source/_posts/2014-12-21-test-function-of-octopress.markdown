---
layout: post
title: "test function of hexo"
date: 2014-12-21 21:42:34 +0800
comments: true
categories: test
tags: test
---

***  
* 目录
{:toc}

<!-- more -->

Welcome to [Hexo](http://hexo.io/)! This is your very first post. Check [documentation](http://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](http://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

<!-- more -->
# 快速开始

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](http://hexo.io/docs/writing.html)

## Run server

``` bash
$ hexo server
```

More info: [Server](http://hexo.io/docs/server.html)

## Generate static files

``` bash
$ hexo generate
```

More info: [Generating](http://hexo.io/docs/generating.html)

## Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](http://hexo.io/docs/deployment.html)

{% blockquote %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque hendrerit lacus ut purus iaculis feugiat. Sed nec tempor elit, quis aliquam neque. Curabitur sed diam eget dolor fermentum semper at eu lorem.
{% endblockquote %}

# 功能测试

## 代码测试
java：

``` java java test code
public static void main(String[] args) {
    System.out.println("Hello world");
}
```

python:

``` python python test code
def hello(str):
    print str

if __name__ == "__main__":
    hello()
```

***

## 图片测试

{% img [test image] /images/timage.jpg 'title' 'alt text' %}
{% img right [test image] /images/timage.jpg 200 300 'title' 'alt text' %}
{% img [test image] /images/timage.jpg 200 300 'title' 'alt text' %}

***

## 块引用测试

{% blockquote 屈原, 离骚 %}
路漫漫其修远兮，吾将上下而求索
{% endblockquote %}

***

## 拉出引用测试

这是一些拉出引用测试的外部内容。  
{% pullquote %}
这是引用测试的内部内容。  
{" 这部分作为拉出部分出现 "}
{% endpullquote %}

## 公式测试

段内公式 $X_1, X_2, X_3$ 段内

中间对齐公式

$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$

另一个公式

$$F=ma$$

$$e^{i\pi} = -1$$

## 表格

|-----------------+------------+-----------------+----------------|
| Default aligned |Left aligned| Center aligned  | Right aligned  |
|-----------------|:-----------|:---------------:|---------------:|
| First body part |Second cell | Third cell      | fourth cell    |
| Second line     |foo         | **strong**      | baz            |
| Third line      |quux        | baz             | bar            |
|-----------------+------------+-----------------+----------------|


***

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

***

| A simple | table |
| with multiple | lines|

没有成功实现？？？
