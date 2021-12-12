# nearpoint
## 가장 가까운 포인트를 찾는 함수이다.
```
int nearpoint(<geometry>geometry, vector pt);
int nearpoint(<geometry>geometry, vector pt, float maxdist);
```
>### *geometry*  
>이 지오메트리의 포인트들중에서

<br/>

>### *pt*  
>이곳에 할당된 위치값과 가장 가까운 포인트 넘버를 반환한다.

<br/>

>### *maxdist*  
>추가적으로 얼마나 멀리까지 찾을지 정한다.