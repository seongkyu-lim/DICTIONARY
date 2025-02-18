# Namespace

![Backend](../../2TAT1C/Label_Backend.png)

<a href="https://www.google.com/search?sxsrf=ALeKk00bjd1DBUcuiASDbuAASniQHKhTcg%3A1604567636589&ei=VMKjX-TCI5v1hwOHz4uABw&q=xml+namespace&oq=XML+Nap&gs_lcp=CgZwc3ktYWIQAxgAMgsIABDJAxAWEAoQHjIGCAAQFhAeMgYIABAWEB4yBggAEBYQHjIGCAAQFhAeMgYIABAWEB4yBggAEBYQHjIICAAQFhAKEB4yBggAEBYQHjIGCAAQFhAeOgcIABDJAxBDOgQIABBDOgUIABDLAToCCAA6BQghEKABUPAXWLwlYKUraANwAXgAgAGBDYgByBSSAQcwLjYuOC0xmAEAoAEBqgEHZ3dzLXdpesABAQ&sclient=psy-ab">#XML</a>
<a href="https://www.google.com/search?sxsrf=ALeKk00dgp9sOmEUsq7VeSXltPv6N0rIJQ%3A1604567645396&ei=XcKjX8bpF5vv-QbtuY_ABQ&q=ip+address+namespace&oq=IP+Address+name&gs_lcp=CgZwc3ktYWIQAxgBMgUIABDJAzIHCAAQFBCHAjICCAAyAggAMgIIADIHCAAQFBCHAjICCAAyAggAMgYIABAWEB4yBggAEBYQHjoECAAQRzoHCAAQyQMQQzoFCAAQywE6CAgAEMkDEMsBOgQIABBDOgoIABDJAxAUEIcCUNRSWJVeYKdpaABwA3gAgAHpAYgB9AeSAQUwLjUuMZgBAKABAqABAaoBB2d3cy13aXrIAQjAAQE&sclient=psy-ab">#IP Address</a>

---

컴퓨팅에서 NameSpace는 다양한 종류의 객체를 식별하고 참조하는 데 사용되는 일련의 기호 (이름)입니다. NameSpace는 주어진 모든 개체 집합이 <span style="color:#FFBF00; font-weight:bold;">고유한 이름을 가지므로</span> 쉽게 식별 할 수 있습니다.


프로그래밍 언어에서 Namespace
```c++
#include <iostream>

// This is how one brings a name into the current scope.  In this case, it's
// bringing them into global scope.
using std::cout;
using std::endl;

namespace box1 {
    int box_side = 4;
}

namespace box2 {
    int box_side = 12;
}

int main() {
    int box_side = 42;
    cout << box1::box_side << endl;  // Outputs 4.
    cout << box2::box_side << endl;  // Outputs 12.
    cout << box_side << endl;  // Outputs 42.
}
```

이름 공간(namespace)은 그 안에서 선언된 기호(변수, 클래스, 함수 등)들을 유일한 범위에 두게하는 선언영역(declarative region)이다. 선언된 심벌을 namespace와 연관시킴으로써, 그렇지 않으면 발생할지도 모르는 <span style="color:#FFBF00; font-weight:bold;">이름 충돌(naming conflict)을 피할 수</span> 있다. 
<a href="https://en.wikipedia.org/wiki/Namespace">위키 백과</a>
