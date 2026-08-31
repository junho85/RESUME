---
layout: page
lang: ko
permalink: /experience/daum-mail/
title: "다음메일 — 8년의 기술 경험"
subtitle: "메일개발파트 · 2012.01 ~ 2020.04"
back_url: /
back_text: "← 이력서"
ko_url: /experience/daum-mail/
en_url: /en/experience/daum-mail/
description: >-
  MAU 2천만 이상, 하루 수억 건을 처리하는 다음메일을 8년 이상 개발·운영하며 쌓은
  기술 스택, 마이그레이션, 레거시 개선, 장애 대응 경험 상세.
---

MAU 2천만 이상, 하루 수억 건의 메일 수·발신을 처리하는 **다음메일**을 8년 이상 개발·운영했습니다.
20년 넘게 살아 있는 서비스를 맡다 보니 한 세대의 기술이 다음 세대로 넘어가는 과정을 서비스 안에서 그대로 겪었습니다.
이 페이지는 이력서에 한 줄로 줄인 그 기간의 상세 기록입니다.

## 규모와 역할

<ul class="meta">
  <li><b>서비스</b> — 다음메일 (MAU 2천만 이상, 하루 수억 건 수·발신)</li>
  <li><b>기간</b> — 2012.01 ~ 2020.04 (8년 4개월)</li>
  <li><b>운영</b> — 수백 대 서버의 배포·모니터링·로그수집</li>
  <li><b>주 사용 기술</b> — Java, C, Perl, MySQL, Linux</li>
</ul>

## 기술 스택

20년 넘는 서비스를 운영하며 거쳐 온 환경입니다. 한 시점에 전부 쓴 것이 아니라, 세대가 바뀌며 누적된 목록입니다.

| 분류 | 기술 |
|---|---|
| 언어 | Java 5 ~ Java 11, C, Perl, Python, Kotlin, Groovy, Scala |
| 프레임워크 | Spring 1 ~ SpringBoot 2, Mojolicious |
| API | Web API, REST API, CGI, Webservice |
| DB | MySQL, Oracle, PostgreSQL, MongoDB |
| 빌드도구 | Gradle, Maven, Make, Ant |
| 배포 | rsync, webistrano, ansible |
| 로그수집 | logstash, filebeat, fluentd, syslog |
| 모니터링 | scouter, sentry, kibana |
| 메시지 | Kafka, RabbitMQ |
| 사용자 알림 | 카카오톡, 이메일, SMS |
| DNS | MX, SPF, DKIM |

## 이메일 도메인 지식

- **메일 프로토콜** — SMTP, LMTP 등 수·발신 경로 전반
- **DNS** — MX, SPF, DKIM 등 발신 신뢰성과 스팸 판정에 직결되는 레코드
- **프리미엄메일** — 유료 메일 서비스 운영·유지보수

## 마이그레이션

오래된 서비스에서 가장 자주, 가장 크게 했던 일입니다. 서비스를 멈추지 않고 바꿔야 한다는 제약이 항상 붙었습니다.

- **DB 이관** — Oracle → MySQL
- **OS 전환** — 32bit → 64bit
- **인프라 이전** — IDC 이전, 물리 장비(PM) → 가상 장비(VM)
- **런타임 버전업** — Java 5 → Java 8 → Java 11
- **구조 변경** — 모놀리식에서 MSA 구조로 전환

## 레거시 개선

- **불필요한 코드 400만 라인 이상 제거** 및 구조 개선
- 버전업 — Java, JUnit, OS, Ant → Gradle, httpd 1.3 → 2.4, Tomcat
- **보안 개선** — SMTP TLS 1.2 지원

## 운영과 장애 대응

- **운영툴 개발** — 메일 수·발신 이력, 로그 조회, 사용자 활동 이력 확인
- **대응한 장애 유형** — HW/SW 장애, 네트워크 장애, 데이터 손실, 작업 실수, 저장소 장애

수천만 사용자가 쓰는 서비스에서 장애는 "일어나는가"가 아니라 "일어났을 때 얼마나 빨리 원인을 찾고 되돌릴 수 있는가"의 문제였습니다.
이 기간에 쌓은 습관 — 로그를 남기고, 조회 도구를 먼저 만들고, 되돌릴 방법을 준비한 뒤 바꾸는 것 — 이 이후 프로젝트에서도 그대로 이어졌습니다.

## 이 시기의 프로젝트

이력서 Projects 섹션에 개별 항목으로 정리되어 있습니다 — 카카오메일, 메일 발송 로그 수집 시스템, 회원시스템 의존성 제거, EMS 대량 메일 발송, 통합사내메일, 메일-CS시스템 연동, 스마트워크, 파란메일 이관.
