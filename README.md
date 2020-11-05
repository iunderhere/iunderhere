<h1 "align=center">SUGENG RAWUH GENG</h1>

<img src="https://telegra.ph/file/ecd88f989fe4faea50b13.png">

<a href="https://www.youtube.com/runggawe">
  <img align="right" alt="Yutubku" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />
</a>
<a href="https://pinterest.com/runggawe">
  <img align="right" alt="Pinterestku" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/pinterest.svg" />
</a>
<a href="https://t.me/iunderhere">
  <img align="left" alt="Telegramku" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/telegram.svg" />
</a>
<a href="https://twitter.com/runggawe">
  <img align="left" alt="Twitterku" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />
</a>
<a href="https://www.instagram.com/runggawe">
  <img align="left" alt="Instagramku" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />
</a>
<a href="https://www.facebook.com/runggawe">
  <img align="right" alt="Facebooku" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/facebook.svg" />
</a>
<br>
<br><p align="center"><a href="https://github.com/iunderhere"><img src="https://img.shields.io/badge/dynamic/json?logo=github&label=GitHub+Followers&labelColor=282c34&color=181717&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dgithub%26queryKey%3Diunderhere&longCache=true"></a></p>
<p align="center"><a href="https://github.com/iunderhere"><img src="https://github-readme-stats.vercel.app/api?username=iunderhere&show_icons=true&theme=radical"></a></p>
<p align="center"><a href="https://github.com/iunderhere"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iunderhere&theme=radical&layout=compact"></a></p>


```python3

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        for attr in attrs:
            if not attr.startswith("_"):
                __annotations__[attr] = Tuple[str, ...]
        attrs["__annotations__"] = __annotations__
        new_cls = super().__new__(cls, name, bases, attrs)
        new_cls = dataclass(new_cls)
        return new_cls
        

print("A little more about me")

iunderhere = {
    'pronouns': 'he' or 'him' or 'his',
    'fullname': 'Ｒａｖｉｔａｍａ 凉',
    'nationality': ['Indonesia', 'ID'],
    'location': 'Central Java',
    'contact': {
        'email': 'contact@gojek.com',
        'website': 'www.warline.my.id',
    },
    'about': [
        '16 y.o' ,
        'A student',
        'A fan of Ambiiyah',
        'I\'m considering myself as a runner. (even tho rarely do it) xd',
        'Love girl and money',
        'Human.',
        'a misleading virtual world'
    ],
    }
```
