---
title: "How to contribute"
date: 2020-05-21 23:30:00 -0400
categories: project contribute
---
## 프로젝트 기여 방안

### 1. 아직 지원하지 않는 명령어를 추가하여 기능을 개선한다.
   
![1](https://user-images.githubusercontent.com/49182823/82579583-fd150880-9bc8-11ea-930d-a8fb020b2260.jpg)

오류가 발생한 명령어를 파싱한 후 적절한 명령어로 찾는 작업이 필요하다. rules폴더 내에는 어떤 명령어에 적절한지 비교하는 함수들이 존재한다. 현재      apt, brew, git과 같은 명령어를 지원한다. 아직 gcc와 같은 명령어는 지원하지 않으므로 이러한 명령어들을 추가하여 기능을 개선할 수 있을 것이다.

![3](https://user-images.githubusercontent.com/49182823/82582061-6ea28600-9bcc-11ea-9240-381b35bbb2ec.jpg)
![4](https://user-images.githubusercontent.com/49182823/82582063-6fd3b300-9bcc-11ea-99f9-189f3a027f2a.jpg)


### 2. 현재 프로젝트에 존재하는 각종 버그 이슈들을 해결한다.
   
![2](https://user-images.githubusercontent.com/49182823/82579597-ff776280-9bc8-11ea-8a91-c3d24499078d.jpg)

현재 커맨드의 각 인자들을 제대로 구분하지 못하는 상황이나 일부 명령어들이 인식이 되지 않는 이슈가 존재한다. 이러한 버그들을 해결하여 프로젝트에 기여할 수 있다.
