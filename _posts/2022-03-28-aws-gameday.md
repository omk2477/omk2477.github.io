---
layout: post
title: "AWS Gameday에 참가하다"
excerpt: Unicon rental에서 생긴 일
categories:
  - 대외활동
tags:
  - [aws, awsgameday, 대회, 2등]
date: 2022-03-28
last_modified_at: 2022-03-29
#TODO: 이미지가 나타나지 않는 오류 수정
image:
  path: /post_images/2022-03-28-aws-gameday/kurly.png
  width: 1000   # in pixels
  height: 400   # in pixels
  alt: image alternative text
---
![kurly](/post_images/2022-03-28-aws-gameday/kurly.png)

AWS Gameday에 참가하였다.  
AWS Gameday는 일종의 카오스 엔지니어링 시뮬레이션을 통해 점수를 얻어 경쟁하는 게임으로,  
넷플릭스에서 IT 인프라의 회복력을 테스트하기 위해 만든 Chaos Monkey를 이용한 게임이다.

## Chaos Monkey?
Chaos Monkey는 위에서 설명한 바와 같이 인프라의 회복력을 테스트하기 위해 만든 것으로,  
인스턴스를 종료하거나 인위적인 지연을 발생시키는 등 다양한 방법으로 인프라에 문제를 일으킨다.

## 카오스 엔지니어링
모든 서비스들은 장애로부터 자유롭지 못하다. 프로그램이 완벽하지 않을수도, 트래픽이 예상 밖으로 급증하여 인프라가 버티지 못할수도, 심지어는 프로그램도 인프라도 괜찮은데 클라우드 서비스 제공 회사가 장애를 겪을 때에도 장애를 겪을 수 있다.  
그래서 최대한 다양한 상황에 대해 대비가 필요하며, 이러한 상황들을 테스트 환경에서 직접 시뮬레이션 해보는 것이 카오스 엔지니어링이다.  
따라서 카오스 엔지니어링은 현재 우리 서비스의 안정성이 어느정도인지 파악함과 동시에 부족한 점을 보완할 수 있는 계기가 된다.

## 참가 의의와 후기
나는 데브옵스 및 SRE를 시작한지 그렇게 오래되지 않았고, 늘 부족하다는 생각을 많이 하고 있었다.  
그래서 늘 관련 행사든 대회든 참여를 해보고 다양한 경험을 쌓아야겠다는 생각이 있었다.  
그러던 중 회사 내에서 AWS Gameday에 참가할 팀원을 구한다는 공지가 올라왔고,  
같은 SRE팀원과 개발팀 몇 분과 함께 참여하게 되었다.  
  
처음 참가하는 클라우드 대회였기 때문에 걱정이 많았지만, 진행 측에서 재미있는 상황극과 자세한 설명 및 지원이 있어 가벼운 마음으로 대회에 임할 수 있었다.  
  
관련 내용과 후기는 [AWS 한국 블로그 'Microservice Magic의 우승팀을 인터뷰하였습니다!'](https://aws.amazon.com/ko/blogs/korea/aws-gameday-microservice-magic-interview/) 에서 확인이 가능하다!

앞으로 이런 대회 참여의 기회가 많은 사람들에게 주어져서  
사람들에게 많은 동기부여와 경험을 선사해주면 좋을 것 같다.
