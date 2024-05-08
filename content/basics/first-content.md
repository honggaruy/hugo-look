---
title : "howto hugo start"
date : 2024-04-16T03:54:49+09:00
draft : false
---

# Hugo-look
- 참고 링크
    - [Relearn installation](https://mcshelby.github.io/hugo-theme-relearn/basics/installation/index.html)
## Hugo의 특성
- [Hugo의 markdown 엔진](https://gohugo.io/getting-started/configuration-markup/#default-handler) : [goldmark](https://github.com/yuin/goldmark/)
    - Markdwon parser for Go
- [archetype](https://gohugo.io/content-management/archetypes/)
    - 새문서 만들때의 기본 템플릿
    - 위치 : `root/archetypes/default.md`
- [Templates Actions](https://gohugo.io/templates/)
    - Jekyll로 치면 liquid 같은 언어 ??
    - [Go template](https://pkg.go.dev/text/template#hdr-Actions) 라고 Go언어와 관련이 있는듯
- [External learning resources](https://gohugo.io/getting-started/external-learning-resources/)
    - Books

        ![Hugo In Action](https://images.manning.com/360/480/resize/book/b/032c2d9-06dd-4b4c-af42-bc3ce16f2759/Jain-Hugo-HI.png?classes=inline&height=15em) 
        ![Build Websites with Hugo](https://pragprog.com/titles/bhhugo/build-websites-with-hugo/bhhugo_hu6d5b8b63a4954cb696e89b39f929331b_1026400_250x0_resize_q75_box.jpg?classes=inline&height=15em)

## 설치 단계
1. Hugo 설치

1. create a new website ( at d:\repository )
  ```sh
  > hugo new site hugo-look
  ```
1. 
