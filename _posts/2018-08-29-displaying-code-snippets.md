---
layout: post
published: true
author: robert barretto
description: examples of code blocks to show syntax.
categories: mostlycurious
image:
excerpt_separator: \{% endhighlight %\}
---
Using liquid curly brackets to generate code blocks:
{% raw %}
```html
{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}

{% highlight matlab %}
function [output]=multiply(x,y)
  output = x*y;
end
{% endhighlight %}
```
{% endraw %}

Renders:
{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}

{% highlight matlab %}
function [output]=multiply(x,y)
  output = x*y;
end
{% endhighlight %}


Using Liquid apostrophes to generate code blocks:
`````html
  ```ruby
  def foo
    puts 'foo'
  end
  ```
  ```matlab
  function [output]=multiply(x,y)
    output = x*y;
  end
  ```
`````
Renders:
```ruby
def foo
  puts 'foo'
end
```
```matlab
function [output]=multiply(x,y)
  output = x*y;
end
```

To embed liquid templating into a markdown code block, see [Ozzie Liu's solutions](http://ozzieliu.com/2016/04/26/writing-liquid-template-in-markdown-with-jekyll/).

If your jekyll engine gives a warning for parsing the liquid syntax, see
[this bug](https://github.com/jekyll/jekyll/issues/5596).