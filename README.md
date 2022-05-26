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
|22.05.26|AI포비아에 관한 토론|머신러닝: AI트렌드|2022 1st 인공지능의 이해|AI의 등장으로 인한 일자리 대체등의 두려움이 인공지능 포비아를 낳고 있음. 오늘 인공지능 포비아와 파생되는 주제들에 대해 강의 토론팀 내에서 토론을 진행해보았다. 토론을 준비하며 개발분야의 AI위협 근황을 조사해봤는데, 바로 엊그제 22년5월24일자로 MS가 Github Copilot의 일반출시가 임박했음을 발표했다고 한다. 2시간짜리 코드를 2분만에라고 기사제목은 다소 과장을 섞어놓았으나, 경향과 발전속도의 지수증가성을 생각해 보았을 때 일반 컴포넌트 수준의 기능구현을 AI가 완전히 대체하는 일 정도는 그리 멀지 않은 미래에 찾아올 것임이 느껴진다. 당장은 효율과 구조보다 기능에 집중된 퍼포먼스이지만 로우코드,노코드가 일반화된다면 개발자가 경쟁력을 가지고 배양해야할 소양은 무엇일까, 보다 기초적이고 핵심적인 가치들을 추구해야 한다고 생각한다. 전산학과 컴퓨터에 대한 이해, 자료구조와 알고리즘, 디자인 패턴등 더욱 잘 이해하고, 체계적인 구조화 능력을 가진 아키텍터의 소양에 더불어 비즈니스 관점에서 유의미하고 창의적인 아이디어를 제안할 수 있는 비즈니스 인사이트 또한 더욱 주목받게 될 것이라고 생각한다. 그리고 권위자들의 주장에 따른 특이점의 시기는 그리 멀지 않았는데 정치권에서 AI의 생산성 향상과 일자리 상실로 인한 소득분배 정책에 대해 더 적극적으로 논의하지 않는 점이 의아하다고 생각한다. 하루빨리 이에 대한 논의가 시작되어 AI와 동반자가 될 수 있도록 사회적 공감대와 제도적 장치를 마련해야 할 것이다.| 
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


