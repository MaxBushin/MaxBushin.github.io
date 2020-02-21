---
layout: post
title:  "Блог на Jekyll и GitHub"
date:   2020-02-21
image: githubBlog.jpg
categories: blog github jekyll
---
<p class="intro">Это тест блога, внутри заметки по установке. </p>

{% highlight PowerShell %}

	для установки блога

bundle install
gem install jekyll-sitemap
gem install jekyll-paginate
gem install jekyll-feed
gem install jekyll-paginate
gem install jekyll-theme-clean-blog
gem install sassc-rails
gem install rails
gem install wdm
gem install github-pages


jekyll b
jekyll s



	залив на сайт

удалить Gemfile.lock
удалить версии в Gemfile
без лок и папки сайт

git config --global user.email "maxim.bushin@gmail.com"
git config --global user.name "MaxBushin"

git clone https://github.com/MaxBushin/MaxBushin.github.io.git
cd MaxBushin.github.io
git add .
git status
git commit -m "v1"
git push -u origin master



	темы Jekyll

index.html домашняя страница
_layouts макеты страницы
include позволяет включать содержимое из другого файла, хранящегося в папке _includes
  header - заголовок (можно убрать)
_config.yml настройки для сайта, заполняются пользователем

{% endhighlight %}

