---
layout: post
title: "My example post?"
categories: misc
last_modified_at: 2021-05-25
agents:
- nugu: SKT NUGU
  its:
  - said: SKT 누구는 날씨를 알고 있습니다.
  - img: false
- gigagenie:
  said: false
  img: false
- clova:
  said: 클로바가 오늘의 날씨를 알려드립니다.
  img: false
- kakaoi:
  said: 오늘 최고기온은 16도, 최저기온은 9도 입니다.
  img: false
- google: Google
  said: It's google sky.
  img: true
- siri:
  said: What a Siri day.
  img: false
---

<h2>test area</h2>

{% for item in page.agents %}

    <h2>{{ item }}</h2>

{% endfor %}

<br>
{{ page.agents.dir }}
