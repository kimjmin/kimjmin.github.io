---
title: 커뮤니티 밋업 사전 설문
tags:
  - Hackathon
  - Meetup
subtitle: Elasticsearch 커뮤니티 밋업 단상 및 사전 설문조사 내용
categories:
  - ICT
date: 2017-02-16 14:46:43
---

2017년 2월 22일 Elasticsearch 한국 커뮤니티 밋업을 진행합니다. 시간, 장소는 [여기](http://onoffmix.com/event/90317) 에서 확인 할 수 있습니다.

이번에도 시작하자 마자 많은 분들이 신청을 해 주셔서 얼마 안 되어 마감되었습니다. 사실 밋업을 진행 할 때 마다 고민이 되는 부분이 참석을 하고 나타나지 않는 분들과 미처 신청 하지 못했는데 꼭 오고자 하시는 분들 때문에 평소에도 고민이 많은데, 일단 여기에 대해서는 커뮤니티에 길게 남긴 글이 있어 그 글 좌표 공유하는걸로 정리하겠습니다.
페이스북 공지 : https://www.facebook.com/groups/elasticsearch.kr/permalink/1239898569429314/

우선 지금 신청 완료 된 분은 

1. 처음 온오프믹스에서 신청 하시고
2. 온오프믹스에 링크 된 설문 까지 완료 하신 분

중 선착순 120분들에 한하여 제가 참여확정자로 변경 해 드렸습니다. 온오프믹스가 예전과 뷰가 달라져서 모임 페이지에서 확인이 되는지 모르겠는데, 아마 참여확정자라고 메일 받으신 분들은 확정 되신 분들이고 신청 하셨는데 아무런 피드백을 못 받으신 분들은 대기자 라고 생각하시면 될것 같습니다.

일단 커피랑 다과는 120인분에 대해 주문을 했습니다. 참여 확정 되신 분들에 한해 이름 확인 하고 현장에서 커피랑 다과 나눠 드릴 예정입니다. 신청을 못 하셨는데 올 수 없냐고 문의 주시는 분들이 항상 계시는데 그런 분들께서 오시는 걸 제가 어떻게 막거나 제재 할 명분은 없습니다. 다만 신청하지 않거나 확정이 아닌데 오신 분들은 우선 커피는 못 받으시는걸로 양해 부탁드리고, 신청 확정 하셨는데 못 오시는 분들이 계신 경우 중간에 그 분들 몫을 다시 분배하는 걸로 하겠습니다.

신청 확정까지 하시고 따로 말씀 안 주시고 노쇼 하시는 분들 또한 제가 딱히 어떻게 할 방법은 없지만, 다른 성실하게 참여하시는 분들께 피해가 가지 않게 하기 위해 나중에 커뮤니티 운영 참여에는 제한을 두거나 하는 방안을 생각중입니다.

이제 이번 밋업 참석하시는 분들 추이를 공유하려고 합니다. 사전 설문에는 지금까지 138분께서 답변을 주셨습니다.

## 설문 응답 내용

![](001.png)

늘 그렇듯 개발자 분들이 제일 많으시며 112 입니다. 그 외에 관리자 7, 경영자 5 , 학생 2, 교수/연구원 3, 출판/언론 2, 그 외 6 입니다.

![](002.png)

실무에서 사용 중인 분들이 절반이 조금 안 되고, 막 시작하는 분들이 26.3%, 처음 들어보는 분들이 9.5% 입니다.

![](003.png)

항목 전체명은 다음과 같습니다. (복수 응답 가능)
- 데이터 분석, 검색, 집계 (Indexing, Searching, aggregation) - Elasticsearch - 129 (94.2%)
- 데이터 수집 (Ingest) - Logstash, Beats - 89 (65%)
- 데이터 시각화 (Visualization) - Kibana - 75 (54.7%)
- 상용 플러그인 - Security (Shield), Alert - 13 (9.5%)
- 클라우드 서비스 - Elastic Cloud (Found) - 19 (13.9%)
- Elastic 회사의 비즈니스 및 기업문화 - 11 (8%)
- 그 외 - 2 (1.5%)

![](004.png)

항목 전체명은 다음과 같습니다. (복수 응답 가능)
- Apache, Ngnix, mobile app  등의 웹, 앱 로그 - 68 (56.2%)
- 시스템, 서버, 스위치, 보안장비의 CPU, Mem, 네트워크 패킷 등의 머신 로그 - 44 (36.4%)
- html, doc, hwp, txt 등의 아카이브 문서 - 13 (10.7%)
- 쇼핑, 커머스 데이터 - 25 (20.7%)
- 게임, 미디어, 엔터테인먼트, 방송 데이터 - 13 (10.7%)
- 증권, 보험, 금융 데이터 - 5 (4.1%)
- 특정 분야의 학술 연구 데이터 - 9 (7.4%)
- 그외 - 13 (10.7%)

## 질문
당일 발표하실 분들과 제게 남겨주신 질문들입니다.

#### 허광남 발표자님께 
>- 커뮤니티 로그데이터 분석 후 얻게 된 인사이트가 무엇이있는지와 해당 인사이트가 커뮤니티의 운영에 실질적인 도움이 되었는지 궁금합니다.
- 보안 관련 해서 어떤 구성들을 하고 계신지 궁금합니다
- Elasticsearch 보안에 대한 Best Practice가 어떤 것인지 알려주세요
- 로그 데이터 분석 관련해서 자세한 수치 및 데이터 규모 등을 알고 싶습니다.
- filebeat 사용 경험이 있으신지요? 있으시다면 사용 후 느낀점이 궁금 합니다. (예를 들어 nxlog 이런 것 보다 이런 면에서는 좋았고 이런 면에서는 별로였다.)

#### 김정환 발표자님께
>- 엘라스틱 운영하실 때 리소스 할당을 하는 기준 같은 게 있나요? 예를 들면 하루에 색인할 로그가 100G정도면 엘라시틱 노드, 메모리는 어느정도 하는 게 좋겠다 같은...
- 시스템 운영 아키텍처 운영 결과 어떤 방향으로의 개선을 더 하고 싶으신지 궁금합니다.
- logstash 5.1.1 에서 플러그인 추가시 버그나면 어떻게하나요?
- HA 구성 best case

#### 제게 & 일반적인 질문 

**기술 관련**
>- 엘라스틱 제품군의 단점, 엘라스틱 제품군들을 이용해 어떠한 분석시도들이 이루어지고 있는지
- 엘라스틱서치의 보안 가이드 
- 엘라스틱을 시작해보고 싶은 사람을 위한 가이드
- 프로젝트를 진행하면서 겪은 트러블 슈팅 ( 메모리, 퍼포먼스 튜닝 문제 등) 에 대해
- elasticsearch 5.x에서 불편하게 바뀐 부분이 있다면 무엇이라 생각하시는지요?(보통은 좋아진 이야기들 위주가 되니까 반대로 질문해봤습니다.)
- Machine Learning(Prelert)의 세부 기능을 자세히 알고 싶습니다~
- 머신 러닝, 실제 사용 사례
- 검색 필드에 어떤 분석기를 어떻게 사용하시는지 궁금합니다.
- local Timezone 이슈
- 엘라스틱 서치를 처음 접하는 개발자가 연습으로 실행해보기 좋은 프로젝트 예시는 어떤게 있을까요?
- 적절한 shard 크기 및 운영시 인덱스 여부

**커뮤니티 운영 관련**
>- 카페 또는 사이트를 통한 국내 사용자 커뮤니티(정보 공유) 운영 계획이 있으신지 궁금합니다.

**그 외**
>- splunk라이센스 비용 절감을 위한 Elastic Stack을 통한 로그모니터링 시스템구축 노하우,
- 처음 접해보는 것으로 MS의 Azure와 어떤 차이점이 있는지요?
- 데이터 분석 적용 방안
- Elastic 구성후 회사에 어느정도 업무가 도움이 되었는지?, 기능 추가에 대한 유지? 보수 등이 편한지
- 엘라스틱 서치와 다른 제품과 비교시 장단점을 알고 싶습니다.

기대했던 것 보다 많은 분들께서 질문을 남겨주셔서 일단 지금 제가 답변 드릴 수 있는 말씀들은 드려보려고 합니다. **그 외** 항목에 모아놓은 질문들은 내용이 애매하고 아직 Elasticsearch가 무엇인지 정확히 모르시는 분들이 질문하신 것 같아서 밋업 시작때 제가 Overview를 한번 할 예정이니 그 때 들으시면 될것 같습니다.

먼저 보면, **보안 구성** 관련해서 질문들을 많이 해 주셨는데, Elasticsearch가 자체 보안 기능이 없기 때문에 Ngnix 같은걸로 웹 프록시를 구성하거나 X-Pack 의 Security (유료) 를 적용 하시면 됩니다. 마침 이광식님 께서 인증 적용에 대해 좋은 글을 얼마전에 남겨주셔서 공유합니다. 
[x-pack을 이용하여 엘라스틱서치와 키바나에 인증 적용하기](http://www.popit.kr/x-pack%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%98%EC%97%AC-%EC%97%98%EB%9D%BC%EC%8A%A4%ED%8B%B1%EC%84%9C%EC%B9%98-%ED%82%A4%EB%B0%94%EB%82%98-%EC%9D%B8%EC%A6%9D-%EC%A0%81%EC%9A%A9%ED%95%98%EA%B8%B0/)

또 **클러스터 설정** 에 관련하여 노드, 메모리 용량은 어느정도로 하고, 샤드 크기는 어느정도가 좋은지에 대한 질문들, 퍼포먼스 튜닝에 대한 질문들은 항상 끊임 없이 나오는 부분입니다. 저도 항상 같은 대답을 드리는데, 참 성의없는 대답이라고 느끼실지 모르겠지만 이게 그때 그때 다르기 때문에 이런 질문에 대해서는 뭐라 정답을 드릴 수가 없습니다. 이 사이트에서 이렇게 적용 했다는 사례를 가지고 우리 사이트에 적용했을 때 그게 동일한 성능이 나온다는 보장은 전혀 없기 때문에 항상 샘플 테스트로 산정할 수 밖에 없는 것이 현실입니다.
다만 시스템 구성을 처음 시작하기 위해 elastic 블로그에 바이블처럼 보셔야 할 글이 몇가지 있어 공유 드립니다. 한글로도 번역 되어 있습니다.
- [Elasticsearch 2.0 인덱싱 성능 고려사항](https://www.elastic.co/kr/blog/performance-indexing-2-0)
- [Elasticsearch 인덱싱에 대한 성능 고려 사항](https://www.elastic.co/kr/blog/performance-considerations-elasticsearch-indexing)
- [A Heap of Trouble](https://www.elastic.co/blog/a-heap-of-trouble) (영어)

그리고 앞서 말씀드린 보안에 대해서도 얼마전 있었던 랜섬웨어 공격 관련해서 중요하게 읽을 포스트 몇개 소개 해 드립니다.
- [금품을 노린 데이터 인질(Ransom) 공격 차단](https://www.elastic.co/kr/blog/protecting-against-attacks-that-hold-your-data-for-ransom)
- [Securing Your Elasticsearch Cluster](https://www.elastic.co/blog/found-elasticsearch-security) (영어)

시스템 운영에 대한 부분은 커뮤니티에도 올려드렸지만 보통은 몸값 비싼 전문가 분들이랑 같이 실무에서 오랜 시간 고민 해 가며 풀어야 하는 문제들입니다. 많은 기업들이 그 때문에 저희에게 비싼 비용을 지불하며 자문을 받고 있고, 저희 같은 오픈소스 기업들이 먹고 살 수 있는 길이기도 합니다.

**Elastic Stack 사용 사례** 에 대해서도 질문 주셨는데, Elastic 홈페이지에 가시면 어마무시하게 많습니다. - https://www.elastic.co/use-cases

**머신러닝** 에 대한 질문들도 주셨는데, 모르시는 분들을 위해 잠시 설명드리자면, 저희 Elastic 에서 작년 9월에 Prelert 라는 머신러닝 기업을 인수했습니다. 지금 Prelert 모듈을 X-Pack 에 내장하는 작업을 하고 있는데 3월 샌프란에서 열리는 Elastic{on}의 큰 주제 중 하나로 발표가 될 예정입니다. 머신러닝 예제는 Prelert 홈페이지에 가 보시면 각 사례별로 필터링 해서 볼 수 있는 형식으로 자세히 나와 있습니다. 친절하게 PDF 보고서로 다운로드도 가능합니다.
http://info.prelert.com/behavioral-analytics-for-security-use-cases

**커뮤니티 운영, 한글 매뉴얼** 관련해서 마찬가지로 페이스북 그룹 외에 다른 까페나 사이트 관리를 할 계획이 있는지 물으셨는데, 있습니다. 다만 이건 저 혼자 할 수 있는게 아니라서 도움이 필요합니다. 다음주 밋업 이후로 함께 운영에 참여하고자 하는 분들을 다시 또 모집 할 계획입니다. 그리고 페이스북에서 다시 찾아보기가 어려운 점 때문에 https://discuss.elastic.co/c/in-your-native-tongue/korean 한글 페이지를 소개 해 드렸는데, 그 때문인지 최근에 글들이 다시 좀 올라오기 시작했습니다. 가능하면 오래 보관했으면 하는 질문들은 여기에 올리고 링크를 페이스북에 공유하는 식으로 하면 좋을 것 같습니다. 한글 매뉴얼도 저 혼자 할 수 있는 작업이 아니라서 이 부분도 같이 참여 해 주실 분이 계시면 좋겠습니다. 자세한건 밋업 때 다시 얘기 하겠습니다.

**세미나 및 행사** 관련해서는 한국에서도 Elastic{on} 행사가 열렸으면 좋겠다라고 하셨는데, 작년에 했었습니다. [행사 리뷰 포스트입니다.](http://kimjmin.net/2016/10/elastic-seoul-seminar/) 다만 이게 세일즈 그룹에서 주관한 행사라 고객(가능성이 있는 기업 위주)로 진행 되어 커뮤니티에 오픈하지 못한 점 사과드립니다. 올해 또 Elastic사 차원에서 한국 행사가 계획 되어 있으니 기대 해 주셔도 좋을 것 같습니다.

여하튼, 부족하지만 좋은 커뮤니티가 될 수 있도록 노력하겠습니다. 응원 해 주시고 도와주셔서 감사드리고요, 앞으로도 잘 부탁드리겠습니다.

