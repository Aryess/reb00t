---
layout: default
---

# Fedy

[Fedy][fedy] is a community extension to Fedora that "lets you install multimedia codecs and additional software that Fedora doesn't want to ship, like mp3 support, Adobe Flash, Oracle Java etc., and much more with just a few clicks."

[fedy]: http://folkswithhats.org/

## Installation

{% highlight sh %}
$ bash -c 'su -c "curl http://folkswithhats.org/fedy-installer -o fedy-installer && chmod +x fedy-installer && ./fedy-installer"'
{% endhighlight %}

## (My) Configuration

### Apps
* Multimedia codecs
	* Activate codecs in Firefox (`about:config`):
		* `media.mediasource.enabled` => `true
		* `media.mediasource.webm.enabled` => `true`
		* Check conf at [https://www.youtube.com/html5]() (currently 5/6 OK)
* Sublime Text 3
	* [Mod it!](/dev/subl.html)

### Themes
Nope

### Tweaks
* Permissive SELinux
* Touchpad tap
