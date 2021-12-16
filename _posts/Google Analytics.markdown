---
layout: post
title:  "Google Analytics"
date:   2021-12-16
comments: true
---

#### Google Analytics? 
*구글에서 무료로 제공하는 웹 분석 서비스*

#### How to link Gitbub page with Google Logistics
*https://analytics.google.com/analytics/web/provision/?hl=ko&pli=1#/provision
위 링크에 들어가 Google Analytics 계정을 생성한다.*

*그 다음엔 속성 만들기를 눌러 속성 이름과 시간대, 통화를 입력한다.
나는 시간대와 통화 같은 경우 현재 거주 중인 대한민국 기준으로 입력했다.*

*그 다음, 추적 ID로 G-가 아닌 UA-가 필요한 경우,
유니버설 애널리틱스 속성 만들기를 활성화하고 URL 입력 후
고급 옵션 중 유니버셜 애널리틱스 속성**만** 만들기 항목에 체크해 준다.*

*비즈니스 정보에 대해 설정한 뒤 만들기를 클릭하면 완료!*
  
#### Modify \_config.yml
```
# Header Option
# header: large

markdown: kramdown
highlighter: rouge
plugins: [jekyll-paginate]
paginate: 5

navigation:
  - title: Home
    url: /index.html
  - title: About
    url: /about
  - title: Contact
    url: /contact

social:
  github: choheehan
  email: cherror@kookmin.ac.kr

google_analytics: "UA-215461057-1"

comment:
  provider: "disqus"
  disqus:
    shortname: "choheehan"
```

*형식을 갖춰 google_analytics 부분을 수정하고 커밋하면
완성!!*
