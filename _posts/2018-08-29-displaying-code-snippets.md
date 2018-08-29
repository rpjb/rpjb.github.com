---
layout: post
published: true
author: robert barretto
description:
categories: mostlycurious
image:
---
{% raw %}
Using liquid to generate code blocks:
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

Using liquid to generate code blocks:
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
