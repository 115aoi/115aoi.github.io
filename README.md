# aoi blogへようこそ
こんにちは！aoiです。
日々のアクティビティについて日記っぽいものを書こうと思いました。
よろしくお願いします。

## 投稿一覧
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%Y-%m-%d" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
