---
layout: default
---

# List of settings and conf files that didn't make it into their own page

## Settings   
* Set the hostname 
{% highlight sh %}
	$ hostnamectl set-hostname --static "Suzaku"
{% endhighlight %}

* Install [htop](http://hisham.hm/htop/)
{% highlight sh %}
	$ sudo dnf install htop -y
{% endhighlight %}

## Config files
> Jekyll sucks at serving files starting with a dot, so download the file and add the dot yourself.

* [gitconfig]({{ site.baseurl }}/conf-files/gitconfig)
