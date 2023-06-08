---
layout: post
title: github 블로그 만들기
subtitle: jekyll 이용한 간편한 블로그 만들기
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [github]
comments: true
---

jekyll 에서는 github 호스팅을 통해 간편하게 블로그를 생성할수 있는 방법이 있다.
기본적인 셑팅이 힘든 사람의 경우 Tstory 등의 서비스를 이용하는걸 추천한다. 

1.github 가입 및 Repository 생성 
 github 가입 하기 [github 사이트]( https://github.com/)

**Here is some bold text**

## Here is a secondary heading

Here's a useless table:

| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.