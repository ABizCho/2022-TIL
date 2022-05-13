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
|22.05.13|BST & AVL트리|개발: 자료구조|오늘자 DS 강의노트, [BST 코드, 참조](https://skeo131.tistory.com/163?category=420274), [BST 강의, 이재규](https://ddmix.blogspot.com/2015/01/cppalgo-15-binary-tree-search.html),|BST는 O(logn)의 효율적 탐색을 위한 이진트리 구조, AVL은 균형이진탐색 트리로 Balance Factor를 판별하여 균형 유지-> 탐색의 균일효율보장, but AVL은 생성 시 오버헤드|
|-|ML Association, Sequence Analysis 이론|머신러닝: 이론|2022 1st DA-ML, Ajou Univ.|흔히 장바구니 분석, sequence분석 으로 불림. Apriori 연관규칙에 따라 각 항목의 조건발생 빈도로 지지도 계산하여 연관규칙 추출한다. 상업적으로 매우 유용한 분석법임|
|-|BST의 중복키 문제|개발: 자료구조|[BST 왜 중복노드 안되는걸까](https://muckycode.blogspot.com/2015/01/binary-search-treebst.html), [BST 중복키 해결법, Jake Lee](https://www.youtube.com/watch?v=obPNXABwwUA)|BST의 중복노드를 가정할 때, 1.중복 존재 가능성을 배제하여 탐색한다면 필요없는 노드를 가지는 것, 2. 중복노드를 존재를 인정한다면, 언제나 중복을 고려하여 불필요한 경우에도 최하위 리프노드까지의 탐색을 이어가야 함 /=> 두 경우 모두 비효율,but 그나마 이진트리+연결리스트 로 유사 해결법 존재|
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


