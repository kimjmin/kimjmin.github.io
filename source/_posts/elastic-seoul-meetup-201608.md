---
layout: post
title: ES Training & Meetup
subtitle: "Core Elasticsearch Training 그리고 서울 밋업"
date: 2016-08-08 10:35:59
tags:
  - Elastic
  - Elasticsearch
  - Meetup
  - Training
categories:
  - Elasticsearch
---

## Core Elasticsearch Training

지난 8월 2일~4일 동안 서울 시청에 있는 웨스틴조선 호텔에서 Core Elasticsearch Training 이 열렸습니다. Elasticsearch Training 은 아래와 같은 과정들이 있으며 일정과 장소는 http://training.elastic.co/ 에서 확인이 가능합니다.
- Core Elasticsearch: Operations
- Core Elasticsearch: Developer
- Hands on Workshop with Elasticsearch, Logstash, Kibana
- Kibana Workshop

가장 주로 하는 것이 CoreES (Operations, Developer) 인데, Operations는 1일, Developer는 2일 과정입니다. 각 도시별로 돌아다니면서 교육을 하는데 보통 저 두개 과정을 묶어서 3일간 진행 하는 것이 보통입니다. 경우에 따라 2개 과정 모두 참석하시는 분도 계시고, Operations, Developer 1개만 참석하는 분들도 계십니다. Operations 는 1인당 800 달러, Developer는 1,600 달러이니 제법 비싼 교육입니다.

보통은 저희 Education Engineer 들이 2명씩 짝지어 다니며 교육을 진행합니다. 하지만 Education Engineer 팀들 인원이 그렇게 많지 않고 대부분 유럽 그리고 미주에 있어서 필요한 경우 (비용 절감 차원에서) 특히 아시아에서 교육을 하는 경우에는 로컬이나 근처 가까운 곳에 있는 다른 엔지니어 (SA, SE 등)이 같이 지원을 하기도 합니다. 이번이 한국에서는 3번째 교육인데 암스테르담에서 온 트레이너와 제가 같이 진행을 하게 되었습니다. 같이 한 트레이너의 이름은 Pablo Musa 인데 원래는 브라질 태생이고 현재는 네델란드 암스테르담에 거주하고 있습니다. 저희 회사에 스페인어 하는 직원은 많은데 포르투갈어 하는 직원은 Pablo 말고는 거의 없는것 같습니다. 여튼 저도 교육을 받아만 보았지 진행하는 것은 처음이라 좀 긴장도 되고 했는데, 파블로와 교육 며칠 전에 미리 만나 같이 진행 할 파트 나누고 하면서 준비 했습니다.

장소는 시청의 웨스틴 조선 호텔에서 열렸고요, 보통은 강남에서 하는데 이번에 준비 한 오거나이저가 왜 이쪽으로 잡았는지는 저도 잘 모르겠습니다. 여하튼, 밖에서는 엄청난 무더위가 몰아쳤으나 호텔 안은 정말 추울 정도로 에어컨이 빵빵해서 파블로는 둘째 날 부터는 긴팔 옷 가져와서 입고 했습니다. 교육 첫날에는 같은 층 다른 홀에서 한미 연합 무슨 행사가 있었는데 교육장 못 찾아 어슬렁 거리고 있으니 양복 차려 입으신 어깨형님들 여럿이 오셔서 여긴 무슨용무로 오셨냐고 둘러싸기도 했습니다. 움찔.

![](IMG_7115.jpg) ![](IMG_7117.jpg)

Operations 는 24분, Developer는 25분 (한분은 전날에 등록)이 등록 해 주셔서 꽉 찬 상태로 진행했습니다. 정원은 25명인데 본사 Training 팀에서도 보통 20명 이상 등록하면 상당히 성공적으로 오픈했다고 좋아합니다. 네트워크 장비, 게임, 이커머스, 포털 서비스 등 다양한 곳에서 참석 해 주셨습니다.

한국에서 하는 교육이라 처음에 본사에서 저한테 같이 교육 진행할 수 있겠냐고 했을때 흔쾌히 하겠다고 하고, 나중에 파블로랑 준비하면서도 난 한국어로 할테니 질문 나오거나 하면 영어로 통역해서 같이 풀어 나가자라고 얘기를 했었는데, 교육 참석하신 분들 중에 태국에서 2분이 참석을 하셔서 하는 수 없이(?) 23분의 한국분을 앞에 두고 저도 영어로 진행을 해야 했습니다. 원래 어느 나라에서 하던지 간에 Elasticsearch 교육은 영어로 진행 하는 것이 원칙입니다. 한군데 예외가 있는데 일본에서 하는 교육은 일본에 ES 엔지니어가 3명이 있어서 일본어로 진행을 합니다. elastic training 웹페이지에도 다른 트레이닝은 언어가 영어로 표시되어있는데 일본에서 열리는 교육은 일본어로 한다고 안내되어 있습니다. 

교육을 신청하고 나면 교육 자료와 예제 덤프가 들어있는 아카이브를 내려받는 링크가 메일로 전달되고 교육이 끝나고 나면 교육을 수료했다는 확인 메일이 가면서 평가를 해 달라고 하는 survay 링크가 포함되어 갑니다. Elastic 회사 내부에서도 Elastic Stack 을 써서 저희 내부 자료도 다양하게 분석을 하고 있는데 (ex. 세일즈 현황, 트위터 해쉬태그 추척 등) 교육 survay 결과도 training team 에서 만든 Elastic Cloud 안에 집계가 된다고 하네요. 파블로가 자기가 만든 Kibana 대시보드 링크와 접속 id/pw 알려줘서 저도 들어가서 봤습니다.

![](training_summary.png)

대략 평점 8 이상으로 많이 부족했을 교육인데 잘 받았다고 평가 해 주셔서 감사했습니다. :)


## Elasticsearch Seoul Meetup

교육 둘째날인 8월 3일에 거의 4개월 만에 다시 밋업을 했습니다. 이번에도 네이버의 후원을 받아 [D2 Startup Factory](http://d2startup.com/) 에서 진행을 했습니다. 이번에도 온오프믹스에 120석 정도로 오픈을 했는데 하루만에 다 찼습니다.

![](meetup_onoffmix.png)

2014년 처음 진행한 밋업(? 오프라인 모임)은 12명이 왔는데 Elasticsearch 에 대한 국내 위상이 많이 높아져서 정말 너무 기쁩니다. ^^. 늦게 신청하신 분들이 어떻게 갈 수 있는 방법이 없냐고 페이스북 쪽지나 메일로 문의를 주셨는데 보통 그냥 오셔도 된다고 말씀 드립니다. 대부분의 경우 신청하신 분들도 다 안 오시거든요. 그 날 바빠서 갑자기 못 오시는 분들도 계시고 해서요.

밋업 한지 멀마 안 됬을 때 꽤 비싼 음식(인당 2만원선)을 100 인분 시킨 적이 있었는데 50명도 채 안 와서 절반 넘게 버린적이 있었습니다. 그때는 [디캠프](http://dcamp.kr/) 에서 했었는데 남은 음식은 디캠프 입주하신 분들 드시라고 모아서 아래층에 내려놓고 갔습니다. 꾸준히 밋업 참여하시고 커뮤니티 활동 열심히 하시는 몇몇 분들이 밋업도 유료로 진행 하라고 권하시기도 했는데, 네이버에서 장소 후원 조건 몇가지가 있는데 그 중 하나가 모임은 무료 모임이어야 하고 발표에 사용된 자료는 D2 커뮤니티에 공유하는 것이 조건입니다. 그리고 개인적인 생각에 평일 저녁 업무 끝나고 어렵게 시간 내서 오신 분들께 참가비 받는 것도 예의는 아닌것 같고요.

여튼, 교육 중에 밋업을 또 오픈을 했습니다. 이유가, 의외로 교육 오시는 분들이 기존에 Elasticsearch 잘 쓰셨던 분들 보다 처음 써보는 분들이 꽤 많습니다. 교육 들으시는 분들도 밋업 초청하고 커뮤니티 조인 시키고자 하는 목적이 있습니다. 또 두번째는 보통 교육은 코엑스나 강남에서 진행해서 저도 어차피 그 주는 계속 그 지역으로 출근을 해야 하니 겸사겸사 근처에서 밋업도 같이 하자... 라는 생각이 있었는데 이번에는 교육을 시청에서 하는 바람에 이 계획은 실패! 했네요. 그리고 교육하는 동안에는 본사에서 엔지니어들이 오니 엔지니어들한테 한꼭지 발표 시키기도 했는데 이번에는 그렇게 하진 않았습니다. 앞으로도 밋업 발표는 가능하면 커뮤니티 멤버들 위주로 할 계획입니다.

파블로에게 밋업 있다고 같이 갈래? 라고 하니 어디서 하냐고 묻길래 강남에서 한다고 하니 "오우! 캉남!" 하면서 자기 와이프 데리고 같이 가자고 합니다. 그래서 교육 끝나고 파블로 내외랑 같이 택시 타고 강남쪽으로 왔습니다. 잠깐 장소 구경이나 하고 나가서 와이프하고 같이 놀고 내일 보자고 했습니다. 아직 시간이 좀 있는것 같아서 잽싸게 저녁 먹고 오려고 했는데 저녁이 늦게 나와서 밋업 시작 10여분 전에 들어왔습니다. 이번에는 커피를 [커피라디오 & 메모지](http://coffeeradio.co.kr/) 에서 주문했는데 호스트도 없는 밋업에 실장님이 2시간 전 부터 와서 기다리고 계셔서 죄송했습니다. 와서 부랴부랴 인사 드리고, 의자 정리 하고 시작했습니다.

- 첫 발표는 제가 Elastic Stack 5.0 버전에서 추가되는 부분들에 대한 발표를 했습니다. - [발표자료](Elastic v5.0.0 Update uptoalpha3 v0.2.pdf)
- 두번째는 조인중님께서 NetFlow와 Elastic Stack을 이용한 네트워크 분석에 대해 발표를 해 주셨습니다. - [발표자료](Netflow Analysis using Elastic Stack_Injung_Cho.pptx)
- 새번째는 오근문님께서 아파트 정보를이용한 ELK Stack활용에 대해 발표를 해 주셨습니다. - [발표자료](Apartment_ELK_Stack.pdf)
- 네번째는 정호욱님께서 Elasticsearch 모델링에 대해 발표를 해 주셨습니다. - [발표자료](Elastic-Meetup-on-Seoul-Henry20160803.pdf)

![](IMG_7129.jpg) ![](IMG_7131.jpg) ![](IMG_7137.jpg) ![](IMG_7138.jpg) ![](IMG_7141.jpg) ![](IMG_7142.jpg) 

정말 유용한 정보들을 아낌없이 공유해 주신 발표자 분들께 다시 한번 감사드립니다. 

밋업때 참석하시는 분들께도 설문 링크를 드리는데 답변율이 높지는 않습니다. 그래도 현장에서 확인 해 면 보통 20% 정도는 항상 Elasticsearch 처음 써 보시는 분들이 오시는 것 같습니다.

![](meetup_survay.png)

여튼, 교육, 밋업 진행하느라 정신 없는 한주가 지났네요. 10월에 좀 큰 행사를 준비하고 있어서 다음 밋업은 아마 그 이후가 되지 않을까 합니다. 보통 밋업때 보면 시간이 없어 그렇기도 하지만 발표만 듣고 가시는 분들이 대부분입니다. 밋업에는 발표 듣는것도 좋지만 다들 Elasticsearch 에 관심 있어서 모인 사람들인데 같이 네트워킹도 많이 했으면 하는 바램입니다. 그래도 이제 저희 밋업 많이 참석하신 분들도 계시고, Elasticsearch 말고 다른 커뮤니티 행사 많이 다니시는 분들은 적극적으로 잘 하시는걸 많이 봅니다. 다음에는 한번 발표는 줄이고 스탠딩 파티로 밋업 준비 해 보는것도 어떨까 한번 생각해 보는 중입니다.
