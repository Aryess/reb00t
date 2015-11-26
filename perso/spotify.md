---
layout: default
---
# Spotify

Do I really need to introduce Spotify? Source for Fedora install [here](http://www.smittix.co.uk/fedora-22-quick-easy-install-of-spotify/).

{% highlight sh %}
$ sudo dnf config-manager --add-repo=http://negativo17.org/repos/fedora-spotify.repo
$ sudo dnf install spotify-client
{% endhighlight %}

Done. Easy right? No more using the webclient, this one works just as good as the windows one, remote control included.