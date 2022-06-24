# 2022 TIL Records
<img src="./src/mdHeader.jpg">

<br><br>

매일 새로이 공부하는, 또는 새로이 배우는 것들을 제각기 목적에 맞는 서로 다른 공간에 나누어 관리하는 것은 금일의 기억과 기록을 파편화 시키며 재참조의 어려움을 낳습니다. 그리고 기록과 기억의 파편화는 소실로 이어질 가능성이 큽니다.

<br>

오늘의 공부를 더 가치있게 기록하기 위해, 이렇게 구축한 작은 시스템이 향후 나에게 큰 도움을 줄 것임을 잘 알기 때문에,
지금부터라도 TIL 레포에 곳곳에서 모은 작지만 가치있는 지식의 조각들로 미래의 어려움을 밝힐 지혜의 등대를 쌓아 올리고자 합니다.
<br>

개발지식 뿐 아니라 TIL로 기록할 가치가 있는, 내 개발과 서비스 사고에 도움이 되는 다양한 것들을 남기겠습니다.


<br><br>

# 2022 매일의 기록

<!-- |D|Sub|Cat|[ref]()|rev| -->

## 5월
|날짜|배운것|분야|관련자료|한줄평|
|------|---|---|---|---|
|22.06.24|AI양재허브 웹트랙 자소서 작성, SNS분석 학부연구 기획서 작성|-|-|-| 
|22.06.21|타과목 기말고사 마감~22|-|-|-|
|22.06.17|고급 정렬까지 자료구조 기말공부~ing|개발: 자료구조|-|-|
|22.06.15|탐색부터 이진탐색트리까지 기말공부~ing|개발: 자료구조|-|-|
|22.06.11|robots.txt, 로봇 배제 표준|개발: 크롤링|[robots.txt 올바르게 사용하기](https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=http-log&logNo=221104827805)/[웹 크롤러좀 그만 만들어라](https://velog.io/@mowinckel/%EC%9B%B9-%ED%81%AC%EB%A1%A4%EB%A7%81-I)|크롤링으로 인한 잡코리아와 사람인, 여기어때와 야놀자 간 법정공방과 처벌사례가 있음을 익히 들어 알고있었는데 이로 인해 크롤링 행위 자체를 꺼려하게 되었다. 학부연구 주제가 SNS분석인데 크롤링을 합법적으로 사용하기 위해 어떤것을 고려해야하 하는지 조사하다가 로봇배제표준 이라는 규약을 알게되었고, 이를 위한 개별 사이트의 robots.txt라는 문서가 존재함을 알게 되었음.|
|22.06.10|고급정렬-셸힙정렬|개발: 자료구조|2022 1st Ajou 자료구조|수업에서 마지막장 고급정렬 중 몇가지를 배웠다. **(1)셸 정렬**은 삽입정렬이 정렬된 배열에 대해 대단히 좋은 성능을 보이지만 이웃 위치로만 이동하기 때문에 정렬을 위한 비교-이동 연산이 많은 단점을 보완한 아이디어로, 이동 제한을 GAP을 이용한 부분리스트 활용을 통해 해결하여 평균 O(n^1.5)의 시간복잡도를 만드는 정렬 알고리즘이다. **(2)힙 정렬**은 힙의 최대값 혹은 최소값의 접근이 매우 효율적이라는 점에 착안한 아이디어로 힙 정렬이 유용한 경우는 전체 데이터가 아닌 특정 수의 최대값 혹은 최소값 몇개에 대한 정렬만 필요한 경우 효율적이고 유용하다. 시간복잡도는 모든 경우에 동일하게 O(nlogn)을 보장한다.|
|22.06.08|파이썬 NLP와 감성분석, Word Cloud|py데이터분석: 실전|[Yelp NLP & Sentiment analysis ,kaggle - SACHIN SHARMA](https://www.kaggle.com/code/sachinsharma1123/sentiment-analysis)|ML PY NLP관련 과제를 진행하던 중 워드클라우드를 추가적으로 만들고 싶어서 여러 자료를 찾아보고 적용했다.|
|-|파이썬 NLP Word Tokenization|py데이터분석: 실전|[NLP Tokenization 토큰화, wikidocs](https://wikidocs.net/21698)|토큰화 방법과 라이브러리를 여러가지 찾아보았다. 토큰화 방법의 주요한 차이는 문장의 분리 기준에 달려있다. 구두점 혹은 특수문자 그것이 아니라면 띄어쓰기 기준으로 문장을 단어로 토큰화 할 것인가 등 인데, 영어는 특히 단어와 구두점의 연결성이 깊다보니 단순 구두점 기준은 여러 문제를 낳을 수 있다. 한국어의 경우 교착어의 특성 등 영어에 비해 토큰화에 특히 어려움이 있다. 이는 이전 R관련 강의들에서도 많이 공부했기에 예전 강의자료를 참고하자. 한국어 '품사태깅' 방법도 간단하게 수록되어있으니 해당 자료 참고.| 
|-|파이썬 NLP 빈도수 분석|py데이터분석: 실전|[자연어처리(NLP): 데이터의 분리/정수인코딩, 딥러닝을 이용한 자연어처리 입문](https://wikidocs.net/book/2155)|토큰화된 단어의 리스트로부터 빈도수를 카운트하기 위해 nltk에선 FreqDist라는 자체 클래스를 제공한다. 케라스 등 다른 생태계마다 빈도수 측정 및 특징과 한계점이 다르므로 주어진 상황을 종합적으로 고려해서 선택한다.|
|-|최단경로 알고리즘: 다익스트라, 플로이드|개발: 자료구조|2022 1st Ajou 자료구조|저번 시간에 이어 최단경로 알고리즘의 자세한 구현 및 시간복잡도 비교를 배웠음. \ **(1)다익스트라**는 한 정점으로부터 다른 모든 정점까지의 최단경로를 구하며 한번의 step에 하나의 경로를 탐색하며 이를 n개의 노드에 대해 실시하므로 전체 시간복잡도는 O(n^2). 단계마다 방문하지 않은 노드 중 최단거리가 가장 짧은 노드를 선ㄴ택하기 위해 힙 자료구조를 이용할 경우 O(ElogN)이 걸림. \ **(2)플로이드**는 모든 정점 사이의, 즉, 모든 정점 쌍의 최단경로 거리를 구한다. 각 단계마다 O(n^2)의 연산으로 현재 스텝의 노드를 거치는 모든 경로를 고려하며, 이를 모든 정점 n에 대해 실시할 경우, 총 시간복잡도는 O(n^2 x n)이므로 총 O(n^3)만큼의 시간복잡도. 대부분의 실전상황에서 플로이드는 낮은 효율성으로 적용하지 않으며 직관적 구현의 장점으로 최단경로 원리학습에 주로 사용된다.|
|22.06.06|자료구조 탐색, 이진트리 복습|자료구조: 복습|[내노트: 작성요망]()|기말대비 탐색과 이진트리를 복습했다.|
|22.06.05|파이썬 회귀의 다중공선성 해결|데이터분석: 실전|[파이썬 스케일링 실전](https://datascienceschool.net/03%20machine%20learning/04.03%20%EC%8A%A4%EC%BC%80%EC%9D%BC%EB%A7%81.html) / [[Python] 데이터 사이언스 스쿨 - 5.3 다중공선성과 변수선택](https://romg2.github.io/dss/04_%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%82%AC%EC%9D%B4%EC%96%B8%EC%8A%A4-%EC%8A%A4%EC%BF%A8-5.3-%EB%8B%A4%EC%A4%91%EA%B3%B5%EC%84%A0%EC%84%B1%EA%B3%BC-%EB%B3%80%EC%88%98%EC%84%A0%ED%83%9D/)/ [다중공선성(Multicollinearity)과 VIF(Variance Inflation Factors)](https://bkshin.tistory.com/entry/DATA-20-%EB%8B%A4%EC%A4%91%EA%B3%B5%EC%84%A0%EC%84%B1%EA%B3%BC-VIF) / [Python 다중공선성 해결, YSY^](https://ysyblog.tistory.com/122)|해당 참고자료에 (1)정규화, (2)변수선택법 (3)PCA 를 이용한 해결법 수록|
|-|다중공선성 해결법:파이썬 Scaler 종류,특징|데이터분석: 이론|[[Python/sklearn] Scaler 별 특징 / 사용법 / 차이 / 예시](https://mingtory.tistory.com/m/140)|Standard scaler, Normalizer, MinMaxScaler, Robust Sclaer 등 정규화를 위한 python 스케일러들의 특징과 사용례 등을 정리한 노트|
|-|파이썬 오차의 정규성 등 오차 고려사항 진단 방법들|PY데이터분석: 실전|[모형의 진단과 수정,데싸스쿨](https://romg2.github.io/dss/01_%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%82%AC%EC%9D%B4%EC%96%B8%EC%8A%A4-%EC%8A%A4%EC%BF%A8-4.9-%EB%AA%A8%ED%98%95%EC%9D%98-%EC%A7%84%EB%8B%A8%EA%B3%BC-%EC%88%98%EC%A0%95/)|-|
|-|파이썬 종속변수의 로그변환 - 잔차의 정규화|PY데이터분석: 실전|[파이썬 회귀- 종속변수 로그 변환,머신러닝 완벽가이드](https://romg2.github.io/mlguide/10_%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D-%EC%99%84%EB%B2%BD%EA%B0%80%EC%9D%B4%EB%93%9C-05.-%ED%9A%8C%EA%B7%80-%EC%8B%A4%EC%8A%B5/)|ML팀플 adr 다중선형분석 중 잔차의 정규성 위반을 문의했는데, 팀원 유선님이 종속변수 로그화를 통해 해결할 수 있는 가능성이 있다고 관련자료를 보내주셨다. R기반 자료라 파이썬 방법을 탐색했고 몇가지 노트를 발견하여 적용해보고자 한다.|
|22.06.04|DA 다중회귀분석의 고려, 검토사항|데이터분석: 이론|[다중회귀분석 시 검토사항, specialscene](https://specialscene.tistory.com/94)|**1) 모형의 통계적 유의성**: F-통계량 : 유의수준 5%하에서 F-통계량의 P-값이 0.05보다 작으면 추정된 회귀식은 통계적으로 유의함 : F통계량이 크면 P-val이 0.05보다 작아짐->대립가설 채택 / **2) 회귀계수의 유의성** : t-통계량 : t-통계량으로 회귀계수의 유의성이 검증된 계수들을 가지고 이를 조합하여 모형을 구성 : 통계적 유의성은 회귀계수에 대한 t-통계량 and 회귀식에 대한 F-통계량을 통해서 판단 / **3) 모형의 설명력** : 결정계수(R^2) or 수정된 결정계수(Adjusted R^2) 확인, 0~1 사이 값이며 1에 가까울수록 설명력 높음 : 결정계수가 낮으면 회귀식의 설명력이 낮은 것,결정계수가 낮다고 통계적으로 유의미하지 않은 것은 아님 / **4) 모형의 적합성** : 잔차와 종속변수 산점도로 확인 / **5) 데이터가 회귀분석의 가정을 만족시키는가?** : 선형성, 독립성, 등분산성, 비상관성, 정상성 / **6) 다중공선성** : **6-1)** 분산팽창요인(VIF) 4보다 크면 다중공선성이 존재한다고 판단, 10보다 크면 심각한 문제가 있는 것으로 해석 :: **6-2)** 상태지수: 10이상이면 문제, 30보다 크면 심각한 문제 -> **6-해결방안** - 다중공선성의 문제가 발생하면 문제가 있는*(1) 변수를 제거 /(2)주성분회귀 적용/ (3)능형회귀 모형 적용* 을 통해 해결 +보통 결정계수값이 매우 높으나 각 독립변수들의 계수가 유의하지 않은 경우 다중공선성을 의심해 볼 수 있음|
|-|DA Python의 다중회귀분석 고려사항 검정법|py데이터분석: 실전|[파이썬 단순 및 다중선형회귀의 유의성 등 검정법](https://ordo.tistory.com/103)| 
|22.06.03|자료구조 DS PJ 관련 피드백|자료구조: 프로젝트|2022 1st Ajou 자료구조, 우현제|자료구조 프로젝트 1차 리포트 제출분에 관련하여 교수님께 피드백을 부탁드림. 주식 트레이딩 시스템을 구현하기 위해 BST와 연결리스트기반 큐 를 사용했는데, 이는 BST를 사용할 때 가격을 탐색키로 줬을 때 발생할 중복 문제를 피하고자 의도했던 부분이었음. 노드 하나의 키를 가격으로 사용하고 담길 DATA를 QUEUE로 구성한 것인데, 기존의 데이터에는 주문자,수량을 삽입하였으나 이경우 중복되는 가격의 특정 주문을 취소하고자 할때 ID가 없어 주문을 특정할 수 없기에 특정 주문값에 ID를 삽입할 것을 권고하셨음. 다만 특정 BST탐색으로 중복가격노드에 도달했을 때, ID기반 큐 탐색으로 방법을 전환하기 위해 어떤 방법을 사용해야 효율적일 지 고민됨.|
|-|가중치 그래프, MST 알고리즘|자료구조: 가중치그래프: MST|2022 1st Ajou 자료구조, 우현제|가중치 그래프의 MST(최소신장트리)를 구하는 알고리즘 배움. 먼저 MST 알고리즘은 크루스칼,프림 이 있으며 둘 다 그리디이지만 접근법이 다름. /**[1.1 MST-K]** 크루스칼은 오름차순 정렬을 전제로 하며 현재정점의 인접정점 중 최소 가중치를 선택해나가는 방법이며 union-find로 사이클존재여부를 검사하여 배제하는 방법이며.크루스칼 구현을 위해 파이썬에선 인접행렬의 요소값으로 edge 정보를 (vertex1,vertex2,가중치) 모습의 튜플로 저장함 / **[1 MST 비교]** Kruskal의 시간복잡도는 정렬하는 시간에 가장 많이 소요하며 그에 성능이 좌우됨 : O(e log e) : Sparse 그래프(엣지가 적은)에 적용하는 것이 적절 <-> Prim은 한스텝의 O(n)을 약 n번 반복하므로 O(n^2)의 시간복잡도이며 dense그래프(엣지많은)에 적용이 적절. 둘의 적용을 고려할 때 가지고 있는 정보가 인접정점이냐 모든 정점정보냐에 따라 선택함. |
|-|가중치 그래프, 최단경로 알고리즘|자료구조: 가중치그래프: 최단경로|2022 1st Ajou 자료구조, 우현제 / [다익스트라, 나동빈](https://m.blog.naver.com/ndb796/221234424646)|가중치 그래프의 최단경로를 구하는 Dijkstra, Floyd 알고리즘 배움. / 다익스트라는 다이나믹 프로그래밍을 활용한 방법이며 GPS SW등에 많이 사용. 하나의 Vertex로부터 다른 모든 Vertex로 가는 최단경로를 알려줌. 음의 간선은 포함X. 최단거리는 여러개의 최단거리로 이어져있다는 아이디어에서 하나의 최단거리를 구할 때, 그 이전까지 구했던 최단거리 정보를 그대로 사용하는 방법 사용하며 이것이 다이나믹 프로그래밍 개념과 부합. / 플로이드는 한 정점으로부터의 다른 정점으로 향하는 모든 최단경로였던 다익스트라와 달리, 모든 vertex 사이의 최단경로를 찾는 개념. 2차원 배열 A를 이용해 3중반복을 하는 루프를 구성하며, 배열 A의 초기 값은 인접행렬의 가중치로 설정하는 방법 선택. 자세한 내용은 추가 공부 필요| 
|-|ML특강- crypto tempo 대표: 블록체인 이론|IT트렌드: 블록체인&디파이|2022 1st Ajou DA-ML 외부초청특강/ [Ripple의 블록체인 생성 시각화 사이트](livenet.xrpl.org)|ML 특강으로 초청된 박미쁨 대표님의 강의를 들었음. 블록체인의 탄생 배경(계약의 역사)과 기본 개념, 그리고 그 응용인 디파이에 대한 내용. 블록체인은 기본적으로 '기록','위변조 방지','사본(증인)'이라는 세가지 계약의 조건을 충족시키는 기술이라고. 블록체인에 대해 어렴풋이 탈 중앙화 라고만 알고 있었고 복사본간의 비교라는 개념만 알고있어서 해시와 비슷한 개념이겠구나 라고 생각했었는데, 실제로 해시함수를 사용한 32byte 블록 생성-> 수많은 사본 생성 -> 사본 간의 해시값 비교를 통한 위변조 감지 원리라고 함. 그래서 최근에 해시를 배웠기에 32byte 해시값이라면 분명 충돌이 발생할 수 있다고 생각하였고, 이 경우 원본문서를 어떻게 식별할 것인지 궁금하여 질문을 드렸는데 원본문서는 원본문서대로 함께 비교기준으로 사용되며 원본문서와 해시값 등의 모든 조건이 동일하여 식별에 문제가 생길 가능성은 실제 계산 상 태양과 행성의 충돌 가능성 수준이기에 사실상의 가능성이 없으나 결국 그 가능성이 존재하므로 기술적으로 완전무결한 것은 아니라 답해주셨음.|
|-|ML특강- Smart Contract & Defi|IT트렌드: 블록체인&디파이|2022 1st Ajou DA-ML 외부초청특강|[블록체인: Non-cutodial, Permissionless] ->[교집합: Transparency, Interoperability] <- [Smart Contract: Programmability] / 블록체인이 중간 매개자 역할을 하여, 송금계약 상 전통적 중간매개 보증주체가 필요 없어짐. 내 돈은 내가 가지고 있다가 블록체인 기술에 의해 직접 보내지는 것이며 이것이 그리 많이 들었던 '블록체인의 탈 중앙화' 개념의 핵심인 것, 다만 기성의 중앙시스템이 아닌 코인 거래소에 중앙화되어 내돈이 내돈이 아닌 아이러니한 상황이 생기며 거래소의 신뢰도와 보안신뢰도가 중요해짐. / Defi는 Money Legos라고 표현할 수 있음. 스마트 컨트랙을 잘 기획-구현해낸다면 은행, 채권, 거래소 역할을 할 수 있을 것 이라는 가능성으로 여러가지 블록체인 서비스가 개발되었으며 'Interoperability'속성 덕분에 하나하나의 서비스가 상호연동하며 커다란 금융시장을 형성했고 이것이 Defi 개념임. *EX) 스태블코인(USDT:1달러에 페어를 이루도록 설계된 특수..등), DEX(Uniswap등),Lending platform(AAVE등),Asset management(Yearn Finanace등),Derivatives(dYdX등),Insurance(Nexus Mutual 등)*, 특히 중요한 것은 stable코인 서비스인데, 이로 인해 달러가치 등 실물화폐와 연동하여 다른 서비스들에 사용될 화폐시스템 안정기반을 마련했기 때문. 현재로서는 그 생태계가 많이 확장-발전하여 단순 거래 뿐 아니라 복잡한 금융생태 - 예를들어 대출, 파생상품 거래등이 정착하고있음. / DEFI생태에 의한 새로운 탈중앙화 수평 조직구조인 DAO(Decentralized Autonomous Organizations도 주목해 볼 만.|
|-|실시간 데이터분석 방법, 스트리밍 분석|데이터분석: 실시간 분석|[실시간 빅데이터 분석, 네이버D2]/ [스트리밍 분석: 현대적 데이터 결정 솔루션, Google]/[실시간 분석,TIBCO](https://www.tibco.com/ko/reference-center/what-is-real-time-analytics)|항상 서비스지향적으로 데이터 분석을 꿈꿔왔는데 서비스를 위한 실시간 분석기술을 아직 배우지 못해서 지금부터 혼자서라도 학습하고 적용해보고자 함. 현대 데이터 수집의 스트리밍 분석이란 '이벤트 스트리밍-움직이는 데이터 흐름'을 말함. 이 스트림은 동작 결과로 발생하는 모든 이벤트로 구성&모든 시간대 포함함. 스트리밍 분석 이용 시 이벤트 스트림 생성 즉시 자동 분석동작 수행 가능. 실시간 분석을 위해선 이런 스트리밍 처리 혹은 실시간 분산 쿼리 기법 등을 사용하는데 이는 실시간 처리가 어려운 하둡의 배치방식 맵리듀스의 한계 등을 극복하는 기법들. 아파치 스파크 등 그 밖의 다양한 방법들이 네이버D2에 잘 기재돼있으니 필요시 글을 다시 참고. 해당 글의 마지막 멘트의 예상처럼 빅데이터 처리를 위한 분산기술 종합 플랫폼 제공 기업들이 현재 매우 활성화됨 AWS,아파치,네이버,카카오 등에서 제공하는 솔루션들도 공부해볼 필요|
|22.05.30|연관분석 - 유통업계의 Segmenting CTA|머신러닝: 이론|[연관성 분석 이해하기 & CTA, 뷰저블](https://www.beusable.net/blog/?p=2481)|pyML 그룹 프로젝트의 연관분석의 결과를 받아보고 이를 어떻게 해석할 것인지 방법을 고민하며 여러 자료를 탐색하던 중, Segmenting CTA에 대해 발견했다. 평소에 궁금증이 크게 있었는데 관련된 용어를 모르다보니 자세히 찾아보지 못했는데 해당 글에서 장바구니 페이지의 실사용예를 기준으로 설명해주어 흥미롭게 보았다. 시간이 나면 추가적으로 알아봐야겠다.|
|22.05.28|객체지향의 사실과 오해#1 ~28p|개발: OOP|[객체지향의 사실과 오해, 조영호](https://github.com/horizontal-library/The-Essence-of-Object-Orientation)|객체지향을 제대로 배워봐야겠다는 생각으로 조영호 저자의 오브젝트를 읽고자 했으나 해당 책을 읽기위한 배경지식이 부족하지 않나라는 생각이 들어 여러가지 선행도서를 찾아보았다. 감사하게도 조영호 저자가 이미 나같은 중생을 위한 책을 출간하셔서 바로 구매했고 horizontal-library에 등록하여 첫 학습을 진행했다.|
|22.05.27|가중치 그래프와 크루스칼 알고리즘|개발: 자료구조|2022 1st Ajou 자료구조|신장트리S 로부터 최소신장트리(MST)를 찾는 것은 최소비용의 경로를 구할 때 사용됨. DAG:비사이클방향그래프 를 대상으로 적용. 이를 위한 MST알고리즘은 프림 & 크루스칼 알고리즘이 존재하며 둘 다 그리디 알고리즘. 크루스칼 알고리즘의 경우 UNION-FIND함수를 응용하여 사이클 형성여부를 판별. 크루스칼 순서: 1) Edges를 가중치를 기준으로 오름차순 정렬 2) 가중치가 작은 edge부터 선택하여 사이클 형성여부 판별 3) 비사이클 시 UNION수행 (2-3반복)|
|-|Association Rules(연관규칙)의 measures 해석과 적용|머신러닝: 이론|[연관분석 해석,LIB](https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=gkenq&logNo=10188110816)/[PyDA:연관분석 음식메뉴 분석 및 결과해석, 망망낭낭](https://tjansry354.tistory.com/10)/[추천을 위한 연관규칙의 measures 해석, ](https://needjarvis.tistory.com/59)|연관분석은 UnsupervisedML의 대표적 기법 중 하나로 추천시스템에 주로 활용. 연관규칙을 생성하여 분석함. MEASURES로 support,confidence,lift가 나오는데 이들을 적절히 고려하여 유의미한 규칙 발견 가능함. 이에 대한 자세한 해석은 노트 참고.|
|22.05.26|AI포비아에 관한 토론|머신러닝: AI트렌드|2022 1st Ajou 인공지능의 이해|AI의 등장으로 인한 일자리 대체등의 두려움이 인공지능 포비아를 낳고 있음. 오늘 인공지능 포비아와 파생되는 주제들에 대해 강의 토론팀 내에서 토론을 진행해보았다. 토론을 준비하며 개발분야의 AI위협 근황을 조사해봤는데, 바로 엊그제 22년5월24일자로 MS가 Github Copilot의 일반출시가 임박했음을 발표했다고 한다. 2시간짜리 코드를 2분만에라고 기사제목은 다소 과장을 섞어놓았으나, 경향과 발전속도의 지수증가성을 생각해 보았을 때 일반 컴포넌트 수준의 기능구현을 AI가 완전히 대체하는 일 정도는 그리 멀지 않은 미래에 찾아올 것임이 느껴진다. 당장은 효율과 구조보다 기능에 집중된 퍼포먼스이지만 로우코드,노코드가 일반화된다면 개발자가 경쟁력을 가지고 배양해야할 소양은 무엇일까, 보다 기초적이고 핵심적인 가치들을 추구해야 한다고 생각한다. 전산학과 컴퓨터에 대한 이해, 자료구조와 알고리즘, 디자인 패턴등 더욱 잘 이해하고, 체계적인 구조화 능력을 가진 아키텍터의 소양에 더불어 비즈니스 관점에서 유의미하고 창의적인 아이디어를 제안할 수 있는 비즈니스 인사이트 또한 더욱 주목받게 될 것이라고 생각한다. 그리고 권위자들의 주장에 따른 특이점의 시기는 그리 멀지 않았는데 정치권에서 AI의 생산성 향상과 일자리 상실로 인한 소득분배 정책에 대해 더 적극적으로 논의하지 않는 점이 의아하다고 생각한다. 하루빨리 이에 대한 논의가 시작되어 AI와 동반자가 될 수 있도록 사회적 공감대와 제도적 장치를 마련해야 할 것이다.| 
|22.05.25|그래프 자료구조 - DFS, BFS, 신장 트리(ST), 최소 신장 트리(MST), 위상정렬(TS)|개발: 자료구조|2022 1st Ajou 자료구조/[신장트리와 최소비용 신장트리, 킹포도](https://kingpodo.tistory.com/49)/[위상 정렬, 동빈나](https://m.blog.naver.com/ndb796/221236874984)|그래프 자료구조를 이용한 탐색인 DFS,BFS 그리고 ST,MST,위상정렬을 배움. 1) 그래프를 이용할 때 DFS,BFS의 선택에 따른 성능차이는 거의 존재하지 않고 그래프 구현에 있어 인접행렬/인접리스트 중 상황에 따라 어느것을 선택하느냐에 따라 성능차이가 주요하게 발생함. 2) 신장트리는 BFS/DFS를 활용해 만들 수  있는 연결그래프의 부분 집합 그래포이며 그래프에 사이클이 존재하면 안됨. 3) MST는 무방향 가중치 그래프에 대해 VERTEX들의 가중치 합이 최소가 되는 신장 트리임. 프림,크루스칼(둘다 그리디) 알고리즘으로 구현 가능 4) 위상정렬은 순서가 정해진 작업을 차례로 수행할 때 순서를 결정해주기 위해 사용하는 알고리즘. 위상정렬은 여러개의 답이 존재할 수. DAG(Directed Acyclic Graph:사이클이 없는 방향 그래프)에만 적용 가능-> 사이클이 있으면 위상정렬 수행 불가. 스택과 큐를 이용한 구현 가능. O(V+E)의 시간복잡도|
|-|Python 텍스트 마이닝 이론|머신러닝: 이론|2022 1st Ajou DA-ML/[내 깃허브 정리: py_machineLearning](https://github.com/ABizCho/py_machineLearning/tree/main/ML_PRAC)|텍스트 마이닝은 Unstructured & semi-structured하게 구성된 Textual Data에 대해 Data Mining, information retrieval, NLP등의 방법론을 사용하여 텍스트 데이터를 분석하는 기법이다. 데이터 표현은 복잡한 편이며, 수만 이상의 공간복잡도를 가질 수 있으며 관련 시장은 매우 크다. 법해석, 연구, 재무보고, 약학, 생물학, 마케팅 등의 도메인에 큰 실효성을 가짐. 스팸필터, 메일분류, 자동응답 등의 상세분야에 대표적으로 사용. 정보추출, 문서검색, sentiment mining/opinion mining and classification 상세과업이 존재 / Tokenization, stemming, stop-words,N-grams의 전처리 & vector-space model,Bag of words, weighting with TF-IDF등의 모델링, Cosine similarity의 유사도 측정 이 텍스트마이닝을 위한 중요 개념이다.|
|22.05.23|인공지능 딥 러닝 이론|머신러닝: 이론|2022 1st Ajou 인공지능 이해/[Google Neural Network Playground](http://playground.tensorflow.org)|인공신경망 개념에서 다양한 활성화 함수를 적용시켜 기울기 소실 문제를 해결하고 과적합문제를 해결하기 위한 드롭아웃 학습방법을 도입한 ML방법으로 CNN,RNN등이 존재, Google Neural Newtwork Playground라는 인공신경망 동작 서비스로 딥러닝 실습해봄. 딥러닝의 활성화 함수 적용은 선형 데이터에 선형함수를 적용함으로써 망이 깊어질 수 없는, 즉, hidden layer(은닉층)이 1 이상으로 증가할 수 없는 문제로 뉴런에 해당하는 노드가 아무리 늘어나도 성능이 나아지지 않는 문제를 해결해줌.|
|-|딥러닝 활성화 함수|머신러닝: 이론|[[Deep learning] Activation Function(활성화 함수) 개념](https://han-py.tistory.com/211)/[활성화 함수(activation function)을 사용하는 이유](https://ganghee-lee.tistory.com/30)/[활성화 함수](https://velog.io/@hyunsuki/Activation-Function%ED%99%9C%EC%84%B1%ED%99%94-%ED%95%A8%EC%88%98)|딥러닝에서 활성화 함수를 사용하는 이유와 그 기능에 대해 더 정확히 알아보기 위해 찾아보았다. 보통의 ML 선형 문제에 대해서는 선형함수를 사용하는 학습모델을 적용하는데 이는 선형모델의 특성 상 뉴런(노드)의 수를 아무리 늘려도 은닉층은 하나밖에 만들 수 없기 때문에 XOR, Circle 등의 비선형 문제에 효과적인 접근이 불가능 하다. 딥 러닝에서는 대표적으로 RELU,탄젠트,시그모이드 등의 활성화 함수를 적용하여 비선형으로 문제를 풀어낼 수 있게 해주며 이에 따라, 은닉층의 깊이를 깊게 만들어 문제를 효과적으로 처리할 수 있다. Spiral(나선) 데이터는 비선형 중에서도 특히 까다로운 문제인데, 활성화 함수를 사용하고 은닉층 수와 노드 수를 적절히 늘림으로써 해결할 수 있다.|
|22.05.22|개발에서의 두뇌 시뮬레이션 능력|개발: 마인드셋|[일잘알과 시뮬레이션, 포프](https://youtu.be/0oMv9xR2f8o)|비즈니스관점의 문제해결을 위한 공감능력의 중요성을 여러곳에서 들어본 적이 있다. 개발자에게 있어서도 시뮬레이션 능력은 발전을 판가름하는 매우 중요한 요소라고 한다. 기능에 대한 시뮬레이션, 논리적 디버깅 시뮬레이션, 비즈니스적 시뮬레이션 사고 등. 두뇌로 사고하도록 노력하자.
|22.05.20|그래프 자료구조 학습|개발: 자료구조|2022 1st Ajou DS Lect|그래프는 Vertex와 Edge로 구성된 자료구조이다. 오일러 문제, 오일러 정리로부터 그래프 이론이 탄생했고 이로부터 유래했다. 선형자료구조, 트리를 포함하는 개념의 자료구조이며 그 세부 특성에 따라 네트워크 등으로 파생되기도 한다. 복잡한 관계의 표현에 적합하다. 인접행렬과 인접리스트로 표현 가능하며, Vertex 수와 Edge 수의 상대적 비에 따라 장단점이 극명하기에 상황에 따라 적절히 구현 한다.|
|-|AVL트리 재균형 회전 원리|개발: 자료구조|[AVL트리 개념, 코드라떼](https://www.youtube.com/watch?v=9BiHgy40NNE)/[기술사-알고리즘-AVL, 그리타](https://www.youtube.com/watch?v=mKxUQgx0a_Q&t=206s)|AVL트리의 재균형은 균형의 좌우 편향에 따라 결정되며, 양수일 경우 좌편향 음수일 경우 우편향으로 판단하고 그 파생에 따라 LL,LR,RR,RL의 네가지 타입의 리밸런싱 경우가 존재한다. LL타입의 회전은 시계방향, RR타입의 회전은 반시계방향으로 수행한다.|
|-|이진탐색, BST, AVL 복습 및 정리|개발: 자료구조|[내 노트: [DS] 탐색트리 : 이진탐색 to 이진탐색트리(BST) to 균형이진탐색트리(AVL)](https://velog.io/@he1256/%EC%9E%91%EC%84%B1%EC%9A%94%EB%A7%9D-DS-%ED%83%90%EC%83%89%ED%8A%B8%EB%A6%AC-%EC%9D%B4%EC%A7%84%ED%83%90%EC%83%89%ED%8A%B8%EB%A6%AC-AVL%ED%8A%B8%EB%A6%AC)|이진탐색과 이진탐색트리의 장단점 그리고 균형이진탐색트리와 그 원리를 복습하여 정리했다|
|22.05.19|검증하는 프로그래머|개발: 마인드셋|[프로그래머는 검증한다, 포프](https://youtu.be/hWwJF-fU2Lg)|참조 기계가 되지 말고 근본적인 문제해결 능력을 배양하자.|
|-|OOP와 부주의한 개발자|개발: OOP|[OOP는 허접한 개발자 때문에 발전했다?, 포프](https://youtu.be/oHaGgLRZy3Y)|부주의한 개발자로 인한 더티코드를 방지하기 위해 문맥마다 클래스를 만드는 등 OOP는 예방적 관점에서 사용된다. 시스템적으로 문제를 예방하는 사고가 필요하다.|
|22.05.18|디자인패턴 S 단일책임원칙|개발: 디자인패턴|[단일책임원칙](https://youtu.be/Tit-bJJm9iw)/[OOP 단일책임, 알파카](http://naver.me/xsUb2j5I)|객체지향 설계를 위한 SOLID 원칙 중 S에 해당하는 단일책임 원칙. 하나의 객체는 하나만의 동작을 갖는다. 객체의 책임범위를 줄임으로써 수정으로 인한 cascading 부작용을 줄이며 무분별한 접근을 방지한다.|
|-|디자인패턴 O 개방폐쇄원칙|개발: 디자인패턴|[Open-Closed](https://youtu.be/EmnIdUvTRfk)/[OOP 개방폐쇄, 알파카](https://blog.itcode.dev/posts/2021/08/14/open-closed-principle)|개방폐쇄원칙은 Extension에 대해선 Open하고 Modification에 대해선 Closed해야 한다는 원칙이다. 객체의 확장에 제한이 없어야하고 따라서 확장으로 인한 객체 수정이 없어야 한다. 모듈화, 정보 은닉, 객체간 의존성 최소화 지향. 인터페이스 활용|
|-|ML Association Practice|개발: 데이터분석PY|[Association with Python, 2022 Ajou LN](https://github.com/ABizCho/py_machineLearning/blob/main/ML_PRAC/prac10_Association.py/ML10_0_Association-Python.ipynb)|pandas, seaborn, numpy, {mlxtend.preprocessing - TransactionEncoder,  mlxtend.frequent.frequent_patterns - apriori, association rules} 사용. 평가지표 : Support, Confidence, Lift|
|-|리액트 구글캘린더 클론코딩 REF|개발: PJ탐색|[구글 캘린더 리액트 클론코딩 REPO, 정미량](https://github.com/MiryangJung/google-calendar-weekly-clone)|뚜잇 프로젝트에 도움을 줄 수 있는 구글 캘린더 PJ 레포를 발견함 : 달력 위젯 등 구현방법 참고|
|-|=|=|[연관규칙분석 with Python, 꽁냥이 - Nice ref](https://zephyrus1111.tistory.com/119)/[장바구니 분석(apriori 알고리즘) 사용 및 해석, demonic](https://lemontia.tistory.com/903)|연관분석을 위한 Apriori의 방법과 원리 절차에 대해 더 자세히 알아보기 위한 참고자료들을 찾아보았다|
|22.05.16|Py Matplotlib 서브플롯 레이아웃|개발: 데이터분석PY|[서브플롯 간의 간격 조절, DataPlstachio](https://steadiness-193.tistory.com/174)|subplots_adjust, tight_layout(), constrained_layout 등의 메서드를 사용하여 레이아웃 조절 가능|
|-|Py matplotlib y축 뒤집은 차트|개발: 데이터분석PY|[Reverse Y-Axis in PyPlot](https://stackoverflow.com/questions/2051744/reverse-y-axis-in-pyplot)|가장 간단하게 ylim을 뒤집어 설정함으로써 해결 가능|
|-|Py jupyter노트북 nbextensions 기능 적용|개발: 데이터분석PY|[확장 기능! Nbextensions](https://bio-info.tistory.com/14)|nbextensions를 통해 코드폴딩, html&pdf 변환 등의 기능을 주피터에서 수행 가능|
|22.05.14|멀티스레드 환경의 OOP vs FP|개발: 프로그래밍 패러다임|[함수형 프로그래밍, 포프](https://youtu.be/XoH9jzblxKQ)|C 등의 OOP기반 플밍 시 멀티스레드 환경에선 레이스컨디션이 발생-이를 막기위해 락 or 아토믹 등을 사용하면 성능저하.But 이를 사용하지 않을 시 C가 훨씬 빠름. 함수형은 immutable한 특성으로 멀티스레드의 레이스컨디션 영향X, 그게 다임. 어제 엘리님영상에선 FP의 장점만을 봤는데 현실적인 면도 볼수 있었음|
|22.05.13|BST & AVL트리|개발: 자료구조|오늘자 DS 강의노트, [BST 코드, 참조](https://skeo131.tistory.com/163?category=420274), [BST 강의, 이재규](https://ddmix.blogspot.com/2015/01/cppalgo-15-binary-tree-search.html),|BST는 O(logn)의 효율적 탐색을 위한 이진트리 구조, AVL은 균형이진탐색 트리로 Balance Factor를 판별하여 균형 유지-> 탐색의 균일효율보장, but AVL은 생성 시 오버헤드|
|-|ML Association, Sequence Analysis 이론|머신러닝: 이론|2022 1st DA-ML, Ajou Univ.|연관분석은 비지도 학습의 대표적 방법. 과거 소비행동데이터로부터 패턴을 찾도록 도와줌. 장바구니 분석, sequence분석 으로도 불림. Apriori 연관규칙에 따라 각 항목의 조건부 발생 빈도로 지지도 계산하여 연관규칙 추출한다. 상업적으로 매우 유용한 분석법임|
|-|BST의 중복키 문제|개발: 자료구조|[BST 왜 중복노드 안되는걸까](https://muckycode.blogspot.com/2015/01/binary-search-treebst.html), [BST 중복키 해결법, Jake Lee](https://www.youtube.com/watch?v=obPNXABwwUA)|BST의 중복노드를 가정할 때, 1.중복 존재 가능성을 배제하여 탐색한다면 필요없는 노드를 가지는 것, 2. 중복노드를 존재를 인정한다면, 언제나 중복을 고려하여 불필요한 경우에도 최하위 리프노드까지의 탐색을 이어가야 함 /=> 두 경우 모두 비효율,but 그나마 이진트리+연결리스트 로 유사 해결법 존재|
|-|프라이빗 클라우드 VDI전환 케이스|개발: 기업사례|[SK C&C 프라이빗 클라우드 VDI 전환, IDG](https://acrobat.adobe.com/link/review?uri=urn:aaid:scds:US:3b14a39a-c24e-34e3-865f-a4d0b0f7379b)|HPE 그린레이크-심플리비티 솔루션을 활용한 기업의 VDI로의 성공적인 전환사례를 다룬 케이스스터디 보고서를 읽었다,클라우드에 대한 지식이 거의 전무하여 개념,용어를 찾아가며 읽어야 했지만 큰 규모의 서비스 전환은 어떤 방법으로 이뤄지는지 미약하게나마 엿볼 수 있었다.|
|-|함수형 프로그래밍 개념|개발: 프로그래밍 패러다임|[함수형 프로그래밍이 대세다?,드림코딩](https://youtu.be/4ezXhCuT2mw)|빅데이터 등 데이터처리 요구의 증가로, 병렬적 데이터 처리의 안정적,효율적 처리가 부각받기 시작 -> 함수형 프로그래밍 주목 / 특징으로는 1.순수함수, 2.비상태, 불변성 유지 3.if,for 등을 사용하지 않는 expression only 특징 4.First class함수: 함수를 변수로 사용하는 등, higher-order functions:함수를 인자로 전달,반환 /+(Monad, semigroup 등의 특징을 이해할 필요)|
|-|2022 AWS summit korea|개발: AWS 클라우드|[2022 AWS summit korea 기조연설,신한투자,당근마켓 케이스 등](https://summits-korea.virtual.awsevents.com/media/Day%201%20%EA%B8%B0%EC%A1%B0%EC%97%B0%EC%84%A4/1_14g8gbrb)|하교길에 AWS서밋에 등록했던 알림이 와서 봤다, 막연했던 클라우드의 개념을 기조연설과 다양한 최신 국내 파트너사의 현업 도입사례를 통해 얕게나마 구체화시킬 수 있었음, 특히 온프레미스와 클라우드의 장단점을 대조한 설명이 많았다. 기조연설에서 CEO는 머신러닝 등 자사의 Saas를 더욱 강조하는 듯 했는데, 오늘 ML강의의 타 조의 케이스스터디 발표가 네이버의 신세대 Aiaas 클로바를 주제로하였기에 더욱 인상적이었음. IT기업의 saas에 대한 요구와 이목이 집중되는걸 체감|
|22.05.12|파이어베이스 기초지식|개발: DB지식|[파이어베이스란 무엇인가? 1~3, 위시켓](https://blog.wishket.com/%ED%8C%8C%EC%9D%B4%EC%96%B4%EB%B2%A0%EC%9D%B4%EC%8A%A4firebase%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80-%ED%8C%8C%EC%9D%B4%EC%96%B4%EB%B2%A0%EC%9D%B4%EC%8A%A4-%EC%8B%AC%EC%B8%B5-%ED%83%90/)|포트폴리오 페이지에 사용할 기술 후보 탐색 중 가볍게 알아봄|
|-|VS코드 저장시 자동포맷 파일 지정|개발: 에디터|[Visual Studio code에서 저장시 자동 포맷](https://gyuha.tistory.com/500)|-|
|-|개발자 마인드셋|개발:마인드|[코딩실력보다 중요한 것](https://youtu.be/0uRj72i-7gg)|프로젝트로부터 배우는 것을 모래성처럼 사라지게 두지 말라, 가장 중요한 것은 성실|
|-|영국의 개발문화가 요구하는 전문가|개발: 자기개발|[백발의 개발자가 되기 위한 커리어 패스, 박경훈](https://zdnet.co.kr/view/?no=20141106211852)|영국의 개발업계는 개인의 생산성보다도 동료의 삽질을 사전에 막을 수 있는 능력을 더 높은 수준으로 평가한다. 순응하지 말고 발전하기 위해 끊임없이 노력하자.|
|-|Dreyfus Model in Dev|개발: 자기개발|[Management, Software Development / 글쓴이 josephjang](http://blog.lastmind.io/archives/593)|Dreyfus 모델에서 난 Novice에 해당하는 것 같다. 드라이퍼스 모델은 경험과 직관을 매우 중요한 요소로 여김, 모델 상 중상급 이상 수준은 20% 이하, 시간이 모든걸 해결하지 않는다는 사실 내포|
|22.05.11|A* vs JPS|개발: 알고리즘:길찾기|[[길찾기 알고리즘] A*냐 JPS냐 ... 그것이 문제로다!](https://www.youtube.com/watch?v=rfOgaPXCADQ)|전략게임에서의 길찾기는 JPS!, 현업에서의 고민과 해답을 찾아가는 접근 방법 또한 인상적으로 배움|
|-|허프만 코드(힙)|개발: 자료구조|[내 노트 : [DS] 허프만 코드 : 힙의 응용](https://velog.io/@he1256/%ED%97%88%ED%94%84%EB%A7%8C-%EC%BD%94%EB%93%9C-%ED%9E%99%EC%9D%98-%EC%9D%91%EC%9A%A9)|오늘의 자료구조 수업에선 허프만 코드 등을 배우고 이를 노트에 정리했다, 압축의 원리에 대해 배워서 내가 써왔던 ZIP툴은 어떤 알고리즘을 응용한 것인지 궁금했는데 서칭해보니 허프만 코드를 이용한다고|
|-|해시 테이블 개념복습|개발: 자료구조|[해쉬테이블에 대해 알아보고 구현하기](https://www.youtube.com/watch?v=Vi0hauJemxA)|자구 수업에서 배운 해시테이블을 복습하기 위해 하교길에 본 간단한 영상, 설명 정말 깔끔하심!|
|-|AR 디바이스 동향 및 생태계 예측|개발: XR트렌드|[내 노트 : Trend of AR Device and New Paradigm to be derived, May 2022](https://velog.io/@he1256/%EB%AF%B8%EC%99%84%EC%84%B1-AR-%EB%94%94%EB%B0%94%EC%9D%B4%EC%8A%A4-%EB%8F%99%ED%96%A5%EA%B3%BC-%ED%8C%8C%EC%83%9D%EB%90%A0-%EC%83%9D%ED%83%9C%EA%B3%84%EC%97%90-%EB%8C%80%ED%95%9C-%EC%8A%A4%ED%84%B0%EB%94%94-%EB%B0%8F-%EC%A0%9C%EC%95%88-Trend-of-AR-Device-and-New-Paradigm-to-be-derived-May-2022)|Apple의 AR Glasses 출시를 앞두고 미래의 생태계를 예측하여 대비하고 싶어서 보고서를 작성하기 시작했다.|
|-|=|=|[개화기에 들어선 XR 시장: 시장현황과 각 기업들의 전략](https://www.youtube.com/watch?v=6APbk7Kx84I&t=30s)|=|
|-|인상적인 퀄리티의 개발자란?|개발: 자기개발|[해외 CTO 가 말한 really impressed with the quality](https://thingsthis.tistory.com/123)|코드 퀄리티를 중요시 여기는 개발자가 되자, Competent 수준의 개발자를 어떻게든 찾아내고 그의 코드를 많이 참고하고 배워 내 것으로 소화할 것.|


