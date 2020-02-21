---
layout: post
title:  "Блог на Jekyll и GitHub"
date:   2020-02-21
image: githubBlog.jpg
categories: blog github jekyll
---
<blockquote>Этот пост написан для тестирования работы блога. </blockquote>
<p class="intro">При установке, в основном, пользовался <a href="https://www.youtube.com/watch?v=xrxY5h906iI&feature=youtu.be&list=PLyHuZVg03hQjtV45HPlfuPzHJOtEoK6DT">вот этими уроками</a>. За основу взял сборку от <a href="https://gosha20777.github.io/">GOSHA20777</a>. Ниже мои заметки по установке, которые могут служить дополнением к <a href="https://gosha20777.github.io/blog/github/jekyll/2017/01/28/blog-with-github/">этому посту</a>.</p>

{% highlight PowerShell %}

	гемы для установки блога

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
без папки сайт

git config --global user.email "maxim.bushin@gmail.com"
git config --global user.name "MaxBushin"

git clone https://github.com/MaxBushin/MaxBushin.github.io.git
cd MaxBushin.github.io
git add .
git status
git commit -m "v1"
git push -u origin master



	настройка темы Jekyll

index.html домашняя страница
_layouts макеты страницы
include позволяет включать содержимое из другого файла, хранящегося в папке _includes
  header - заголовок (можно убрать)
_config.yml настройки для сайта, заполняются пользователем
style.css длинная строка внизу - это стили
{% endhighlight %}

<h3> Полезные ссылки</h3>

<ul>
  <li><a href="https://jekyllrb.com/docs/">Официальная документация</a></li>
  <li><a href="https://habr.com/ru/post/336266/">Статья на харбе от 2017 года</a></li>
  <li><a href="https://webdesign.tutsplus.com/ru/tutorials/how-to-set-up-a-jekyll-theme--cms-26332">Настройка темы</a></li>
</ul>
