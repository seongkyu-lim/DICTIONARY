# Invariant

![Backend](../../2TAT1C/Label_Backend.png)

<a href="https://www.google.com/search?sxsrf=ALeKk003d-pO5eb1jgpaV7hBqnNczTFzxQ%3A1604565042893&ei=MrijX82FNor_wAPnro74Cw&q=binary+search+tree+Invariant&oq=binary+search+tree+Invariant&gs_lcp=CgZwc3ktYWIQAzICCAAyBggAEAUQHjoECAAQRzoKCAAQkQIQRhD5AToGCAAQBxAeOgUIABDLAVCTP1jyQ2C4RWgAcAN4AIABqwGIAZEEkgEDMC40mAEAoAEBoAECqgEHZ3dzLXdpesgBCMABAQ&sclient=psy-ab&ved=0ahUKEwjN5pnL_ursAhWKP3AKHWeXA78Q4dUDCA0&uact=5">#이진 탐색트리</a>

---

일반적으로 불변이라는 의미를 가집니다.

invariant는 variable(변수) 보다 좀 더 개념적(conceptual)입니다. 일반적으로, 이것은 <span style="color:#FFBF00; font-weight:bold;">항상 true인 프로그램 상태의 속성</span>입니다. 불변함을 보장하는 위한 함수 혹은 메소드는 invariant를 유지한다고 합니다.

예를 들어 binary search tree(이진 탐색트리)에는 모든 노드에 대해 노드의 왼쪽 자식 키가 노드 자신의 키보다 작은 것이 invariant를 가질 수도 있습니다.

예를 들어, 이진 검색 트리는 모든 노드에 대해 불변성(invariant)을 가질수 있는데 노드의 왼쪽 자식 키가 노드의 자체 키보다 작은 것이 그러합니다. (이진 탐색트리의 왼쪽 자식은 그 부모보다 항상 작은 값을 가진다.)

여러분이 알 수 있듯, <span style="color:#00FFCC; font-weight:bold;">당신의 변수에 저장할 수 있는 종류의 것은 아닙니다.</span> (개념적이다):


이것은 프로그램에 대한 더 자세한 설명입니다. 프로그램이 어떤 종류의 불변성을 유지해야 하는지 파악한 다음 실제로 불변성을 유지해야하는지 확실히 검토함으로써, 여러분은 코드에서 논리적 오류를 피할 수 있습니다.

<a href="https://stackoverflow.com/questions/112064/what-is-an-invariant/">참고-스택오버플로우</a>

