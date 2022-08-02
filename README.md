# Effective-python-study 🐍
파이썬 코딩의 기술(Effective python) 스터디

## 1. 협업방식 🧑🏻‍💻🧑🏼‍💻🧑‍💻
git-flow light 방식으로 협업

- *git-flow light란?*
  - git-flow 방식을 간소화한 형태
  - remote-repo는 master 브랜치만 관리하며 local-repo로부터 push된 브랜치들을 merge하여 전체적인 프로젝트 관리 진행
  - local-repo는 feature 브랜치를 통해 기능 개발을 담당하고 실질적인 프로젝트 발전 담당
  <pre>
  <code>
    remote-repo
        L master
    local-repo
        L master
        L feature/[개발하고자 하는 기능]
  </code>
  </pre>

## 2. 파일 작성 관련 규칙 🔥
  1. 파이썬 기초를 아는 사람이 파일 내용만 읽어도 이해가능할 정도로 친절하게 작성한다.
  2. 파일명은 Effective python의 Better way 이름과 동일해야 한다.
  3. 파일 가장 윗 부분에 작성일자와 작성자를 명시해야 한다. 형식은 아래와 같다.
        >작성일자 : YYYY-MM-DD
        >작성자 : 김파이썬