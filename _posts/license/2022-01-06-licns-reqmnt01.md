---
title: 소프트웨어 생명 주기 SDLC(Software Development Life Cycle)
categories: [license, 정보처리기사]
tags: [자격증, 정보처리기사, 정처기, 소프트웨어 설계, 요구사항, 소프트웨어 생명 주기, SDLC]
---

<span style="font-size:20pt; color=#2f2f2f;">**정보처리기사-소프트웨어 설계 : 요구사항 확인01**</span>

아래 내용은 정보처리기사 자격증 시험공부를 위한 요약 및 정리입니다.<br>
내용은 [**인프런 - 정보처리기사 필기**](https://www.inflearn.com/course/%EC%A0%95%EB%B3%B4%EC%B2%98%EB%A6%AC%EA%B8%B0%EC%82%AC-%ED%95%84%EA%B8%B0-1/dashboard)를 참고하였습니다.

---
### **소프트웨어 생명주기**
><span style="color:#986BB2">소프트웨어를 체계적으로 개발하고 관리하기 위하여 개발 과정을 단계별(개발을 위한 정의, 운용, 유지보수 등)로 나누어 구분한 것</span>

<br>
1.폭포수형 모형
: 순차적으로 한 단계, 한 단계를 진행해 나가는 방식으로 전 단계가 완료되기 전에는 다음 단계로 진행할 수 없도록 제한하는 방식<br>
- 가장 오래되고 가장 폭넓게 사용된 `고전적 생명 주기 모형`<br>
- 추가적인 요구사항을 받아들이기 어려움
- 선형 순차적 모형<br>
<span style="color:#81BCAC">(요구자의 요구사항이 명확한 경우 사용)</span><br>
<span style="color:#9a9a9a">*마치 폭포는 위에서 내려오지만 거슬러 올라가지 못하듯 단계가 반드시 순차적으로 진행되는 것!</span>

![Desktop View](/assets/img/file/blog/license/weterfall_model.PNG)
_폭포수형 모형 단계_
<br>

2.프로토타입 모형
: 개발초기에 시스템 모형을 간단히 만들어 사용자에게 보여주고 직접 사용할 수 있게하여 발생하는 요구 사항에 따라 재구축 과정 반복하며 시스템을 개선시켜 나가는 방식<br>
- 추가, 변경, 삭제 등 즉시 반영이 가능하다<br>
- 프로토타입을 만들어 수정해 나가는 방식<br>
- 비용, 시간을 예측할 수 없음<br>
- 원형(prototype) 모형<br>
<span style="color:#81BCAC">(요구사항이 명확하지 않은 경우 사용)</span><br>
<span style="color:#9a9a9a">*말 그대로 프로토타입으로 요구사항 충족엔 용이하나 비용과 시간을 예측할 수 없음!</span>

![Desktop View](/assets/img/file/blog/license/prototype_model.PNG)
_프로토타입 모형 단계_
<br>

3.나선형 모형
: 고객과의 소통을 통하여 계획수립과 위험분석, 구축, 고객 평가의 과정을 반복적으로 거쳐 소프트웨어를 개발하는 방식<br>
- 시스템 개발시 발생하는 `위험을 최소화` 하기 위한 방식<br>
- 위험 부담이 큰 대형 시스템 구축에 적합<br>
<span style="color:#9a9a9a">*목표설정, 위험분석, 구축, 고객평가를 돌고돌고 돌려 위험성을 줄이는 것!</span>

![Desktop View](/assets/img/file/blog/license/spiral_model.PNG)
_나선형 모형 단계_
<br>

4.애자일
: 고객과의 소통에 초점을 맞춘 방식<br>
- 고객 중심<br>
- 요구자의 요구사항 충족<br>
- 소규모 시스템에 적합<br>
<span style="color:#9a9a9a">*고객 중심으로 요구사항 충족을 위한!</span>
