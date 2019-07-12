---
layout: default
title:  "Hello, world!"
date:   2019-07-12
---
## {{ page.title }} | {{ page.date | date: "%Y-%m-%d" }}

It’s really easy. Create `hello.rb` file with content:

{% highlight ruby %}
puts "Hello, world!"
{% endhighlight %}
and then just type in terminal:

{% highlight bash %}
ruby hello.rb
{% endhighlight %}
