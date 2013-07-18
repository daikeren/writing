# 好書推薦 - Two Scoops of Django

![Two Scoops of Django](https://s3.amazonaws.com/twoscoops/img/tsd-cover-beta.png)

如果你是跟我一樣自認對於 Django 略懂略懂的 Developer，那麼你可能會在寫一陣子 Django 之後對以下問題感到疑惑：

* Project Layout/Project Settings 應該怎麼樣才是最好的呢？
* 什麼時候要用 class-based view?
* 哪些 code 要放在 view？template？models？
* 看某某某說 Django template 很慢，要不要換成 Jinja2
* 我的 Django Project 好像有點慢，是不是該用 NoSQL 了

如果你也有這些疑問，那麼你應該來看看 [Two Scoops of Django](https://django.2scoops.org/) 這本書。這本書是由 [Daniel Greenfeld](http://pydanny.com/) 還有 [Audrey Roy](http://audreymroy.com/) 這兩位很有經驗的 Django Developer 寫的。你可能不知道他們是誰，不過你一定用過 [Django Packages](https://www.djangopackages.com/) 這個網站，這個站就是他們的作品！

那麼這本書告訴我們什麼呢？這些是我隨意選幾個章節的內容大概：

### Chapter 1: Coding Conventions

注意 [PEP8](http://www.python.org/dev/peps/pep-0008/)、還有用 relative imports (from .models import Model)。這本書從第一章就告訴你作者認為好的 coding style，從剛開始就給你一個很好的基礎。

### Chapter 2: The Optimal Django Environment Setup

很好！第二章就告訴你要用 [virtualenv](https://pypi.python.org/pypi/virtualenv)！要什麼時候 Django 官方的 Tutorial 才會把 virtualenv 寫進去呢？

### Chapter 5: Settings and Requirements Files

Django 裡面的 settings.py 一堆路徑設定還有 local_settings.py 這些讓你覺得很煩嗎？看看這個 Chapter 或許會有些收穫。

### Chapter 7: Function- and Class-Based Views

什麼時候要用 Function-Based View? 什麼時候要用 Class-Based Views？來看看作者的意見！

### Chapter 14: Tradeoffs of Replacing Core Components

要不要把原本的 ORM 換掉？要不要把 Django 的 template 換掉？來看看作者的想法吧！

### Chapter 20: Finding and Reducing Bottlenecks

Django Project 好像有點慢怎麼辦？請使用 [django-debug-toolbar](https://github.com/django-debug-toolbar/django-debug-toolbar)！這邊還告訴你一些其他的 performance 相關的 Packages！

### Chapter 21: Security Best Practices

還記得 [Github 被 hacked](http://www.extremetech.com/computing/120981-github-hacked-millions-of-projects-at-risk-of-being-modified-or-deleted) 的新聞嗎？Django 會不會一樣有安全性相關的問題咧？這個 Chapter 會告訴你一些安全性該注意的問題。

### Chapter 24: What About Those Random Utilities?

這個 Chapter 告訴你一些你可能不知道的 Django Utilities。舉例來說，你知道 [django.contrib.humanize](https://docs.djangoproject.com/en/dev/ref/contrib/humanize/) 是幹啥的嗎？

如果你自認是個寫過一陣子的 Django Developer，那麼請務必[買這本書](https://gumroad.com/l/uyqN)！區區的 17 美金絕對會讓你有值回票價的感覺。

最後打個廣告：無論你是 Django 的新手或是老手，都相當歡迎來 [Taipei.py](http://www.meetup.com/Taipei-py/) 或是 [Django Workshop](http://www.meetup.com/Taipei-py/events/126421922/) 來聊聊天或是彼此分享一下經驗，多交流大家才會有進步 :)