---
layout: default
---

# Oh My Zsh

[Oh My Zsh][ohmyzsh] (along with [zsh][zsh]) has been my shell of choice for a while now. Prettier than default bash, and most important, so more powerfull and efficient! If you're not convinced, have a look at [these slides][zshelliscool] that showcases zsh best features.

[ohmyzsh]: https://github.com/robbyrussell/oh-my-zsh
[zsh]: http://www.zsh.org
[zshelliscool]: http://slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692

## Installation

### Install zsh and default to zsh
{% highlight sh %}
$ please dnf install zsh
$ chsh -s `which zsh`
{% endhighlight %}
Close and reopen terminal to start using zsh.

### Install oh-my-zsh
{% highlight sh %}
sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
{% endhighlight %}

### (My) Configuration
* Theme: `ZSH_THEME="miloshadzic"`
* Aliases:
	* `alias gitrefresh="git stash && git pull && git stash apply"`
	* `alias startall="please service mariadb start; please service beanstalkd start; please service elasticsearch start; please service httpd start"`
* Plugins: `plugins=(git laravel5)`