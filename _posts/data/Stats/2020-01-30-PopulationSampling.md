---
date: 2020-01-30 02:36:00 +09:00
title: 통계학 - 모집단과 표본추출
category: Stats
tags: [bigdata, statistics, stats, 통계학, 모집단, 표본, 표본추출]
description: 제대로 시작하는 기초 통계학 강의 노트
---
{% assign path = page.imgpath | append: page.id %}

# 모집단과 표본추출

## 모집단(Population)
- 조사 대상 전체를 의미
- 현실적으로 모집단 전체를 조사하기 어렵다

## 표본추출(Sampling)
- 모집단을 대표할 수 있는 일부를 추출해서 실제로 조사를 실시하는 대상
- 표본을 조사하여 모집단에 대해 추론(모수 추정)한다
- 결과의 정확도를 위해서 원하는 목적에 맞게 모집단을 잘 대표할 수 있는 표본 추출이 관건이다

![Image]({{path}}/img01.png){:width='460px'}  
*이미지 출처 : https://images.app.goo.gl/Road7UaJd5niy37K6*

## 모수(Parameter)
- 모집단을 분석해서 얻은 결과 값
- 모평균($\mu$), 모분산($\sigma^2$), 모표준편차($\sigma$), 모비율($p$)

## 통계량(Statistic)
- 표본을 분석해서 얻은 결과 값
- 표본평균($\bar{x}$), 표본분산($s^2$), 표본표준편차($s$), 표본비율($\hat{p}$)

# 표본추출 방법
1. 확률적 표본추출 방법 : 동일한 확률 하에 추출하는 방법
2. 비확률적 표본추출 방법 : 조사자 또는 조사 대상의 의지로 표본을 추출하는 방법. 확률적 표본추출이 어려운 경우 사용.

## 확률적 표본추출 방법(probability sampling method)

- **단순 무작위 표본추출** : 가장 단순한 방법으로 랜덤하게 표본을 추출. 표본 크기가 작으면 왜곡될 가능성 높다.
- **체계적 표본추출** : 표본을 순서대로 나열해서 n번 째 대상을 선택하는 방법 eg. 선거 출구조사
- **비례 층화 표본추출** : 어떤 특성을 집단을 나눈 다음, 그 집단의 크기에 비례하여 표본을 추출하는 방법 eg. 대학교 학년별 인원수에 따라 추출
- **다단계 층화 표본추출** : 집단 구분을 여러 단계로 나누어 그 크기에 비례하여 추출하는 방법 eg. 단과대/학과별 인원수에 따라 추출
- **군집 표본추출** : 모집단 구성이 내부 이질적/외부 동질적이면, 그중 일부 집단을 통째로 선택하는 방법 eg. 서울시의 몇 개 구를 선택해서 추출

## 비확률적 표본추출 방법(non-probability sampling method)
- **편의 표본추출** : 조사자의 편의에 따라 임의의 표본을 무작위로 추출. 모집단 대표성이 떨어질 우려가 많다.
- **판단 표본추출** : 조사자의 적합다하고 판단하는 표본을 추출
- **할당 표본추출** : 모집단의 특성을 대표할 만한 연령, 학력, 직업 등의 구분과 크기를 미리 결정하고, 그에 맞춰 조사자가 임의로 표본을 추출
- **자발적 표본추출** : 조사 대상이 자발적으로 참여하는 방법. 단, 조사자의 관심도가 높아서 왜곡될 가능성이 높다.

![Image]({{path}}/img02.png)  
*출처 : [이훈영의 연구조사방법론](https://socialinnovation.tistory.com/122){:target='_blank'}*

> **REF**  
> [제대로 시작하는 기초 통계학 | 노경섭 지음](https://www.youtube.com/playlist?list=PLsri7w6p16vs-rMb1uXHfh3FiCk2WjEUG){:target='_blank'}