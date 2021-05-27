---
title:  "How's the weather?"
last_modified_at: 2021-05-25
google: "It's google sky"
img_google: assets/img/google-assistant-cover.jpg #구글 이미지 위치
siri: "What a Siri day"
kakao: "오늘 최고기온은 16도, 최저기온은 9도 입니다."
---
## 이미지 테스트

# 2
{% include imgframe.html file='./assets/img/google-assistant-cover.jpg' alt='GA' %}

# 5
![{{ page.google }}]({{ page.img_google | relative_url }})

* * *
{% include projector.html %}
