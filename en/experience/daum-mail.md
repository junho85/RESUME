---
layout: page
lang: en
permalink: /en/experience/daum-mail/
title: "Daum Mail — Eight Years of Detail"
subtitle: "Mail Development Part · 2012.01 ~ 2020.04"
back_url: /en/
back_text: "← Resume"
ko_url: /experience/daum-mail/
en_url: /en/experience/daum-mail/
description: >-
  The full technical record behind eight years on Daum Mail — over 20 million MAU
  and hundreds of millions of daily transactions: the stack, the migrations, the
  legacy work and the incidents.
---

I developed and operated **Daum Mail** for more than eight years — over 20 million MAU and
hundreds of millions of send/receive transactions a day. Working on a service that had already
been alive for two decades meant living through one generation of technology handing over to the
next, inside a system that could not stop. This page is the detail behind the single line on the
resume.

## Scale and role

<ul class="meta">
  <li><b>Service</b> — Daum Mail (20M+ MAU, hundreds of millions of daily transactions)</li>
  <li><b>Period</b> — Jan 2012 ~ Apr 2020 (8 years 4 months)</li>
  <li><b>Operations</b> — deployment, monitoring and log collection across hundreds of servers</li>
  <li><b>Primary stack</b> — Java, C, Perl, MySQL, Linux</li>
</ul>

## Technology

What follows accumulated across generations of the service rather than being used all at once.

| Area | Technology |
|---|---|
| Languages | Java 5 ~ Java 11, C, Perl, Python, Kotlin, Groovy, Scala |
| Frameworks | Spring 1 ~ SpringBoot 2, Mojolicious |
| APIs | Web API, REST API, CGI, Webservice |
| Databases | MySQL, Oracle, PostgreSQL, MongoDB |
| Build tools | Gradle, Maven, Make, Ant |
| Deployment | rsync, webistrano, ansible |
| Log collection | logstash, filebeat, fluentd, syslog |
| Monitoring | scouter, sentry, kibana |
| Messaging | Kafka, RabbitMQ |
| User notifications | KakaoTalk, email, SMS |
| DNS | MX, SPF, DKIM |

## Email domain knowledge

- **Mail protocols** — SMTP, LMTP and the delivery path end to end
- **DNS** — MX, SPF and DKIM, the records that decide sender reputation and spam handling
- **Premium Mail** — operated and maintained the paid email service

## Migrations

The most frequent and the largest work on an old service, always under the same constraint: the
service could not go down while it changed.

- **Database** — Oracle to MySQL
- **Operating system** — 32bit to 64bit
- **Infrastructure** — IDC relocation, physical machines to virtual machines
- **Runtime** — Java 5 to Java 8 to Java 11
- **Architecture** — monolith to an MSA structure

## Legacy work

- Removed **over 4 million lines** of unnecessary code and restructured what remained
- Upgrades — Java, JUnit, the OS, Ant to Gradle, httpd 1.3 to 2.4, Tomcat
- **Security** — added SMTP TLS 1.2 support

## Operations and incidents

- **Internal tooling** — mail send/receive history, log search, user activity lookup
- **Incidents handled** — hardware and software failures, network outages, data loss, operator
  error, storage failures

On a service used by tens of millions, an incident is never a question of whether but of how fast
you can find the cause and undo it. The habits formed here — leave logs, build the tool that reads
them first, and have a way back before changing anything — carried into every project since.

## Projects from this period

Listed individually in the Projects section of the resume — Kakao Mail, the mail delivery log
collection system, decoupling the member system, EMS bulk mail delivery, unified corporate mail,
mail–CS system integration, Smart Work and the Paran Mail migration.
