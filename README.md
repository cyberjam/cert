 정보처리기사
 ============

 준비 
 --------



pdf 다운 https://sinagong.gilbut.co.kr/download?type=PD_FILE&idx=147487

시나공IT 정보처리기사 기출문제집 핵심 요약 https://sinagong.gilbut.co.kr/it/pds#pd03


cbt 전자문제집 https://www.comcbt.com/cbt/index2.php?hack_number=29



오답 정리 
------------

# 데이터 베이스
## 관계대수와 관계해석
* 관계대수 
>- 관계형 데이터베이스에서 원하는 정보와 그 정보를 어떻게 유도하는가를 기술하는 절차적 언어
>- 릴레이션을 처리하기 위해 연산자와 연산규칙을 제공하는 언어, 피연산자(relation) 연산자 -> 결과 relatioin
>- 질의에 대한 해를 구하기 위해 수행해야할 연산의 순서
>- 순수관계연산자(select,project, join, division), 일반집합연산자(union, intersection,difference,cartisian product)

* 관계해석
>- 원하는 정보가 무엇인가라는 것을 정의하는 비절차적 언어
>- 코드가 predicate calculus 기반으로 제안한 질의로 이루어진 언어
>- 원하는 정보를 정의할 때 계산 수식 사용
>- 튜플 관계 해석, 도메인 관계해석 (or, and ..)


```
*db 처리기능, 능력 모두 동일*
```

기본 개념 : https://bjh0925.tistory.com/entry/10-%EA%B4%80%EA%B3%84-%EB%8C%80%EC%88%98%EC%99%80-%EA%B4%80%EA%B3%84-%ED%95%B4%EC%84%9D52
어떻게 생겨 먹었을까 : http://dblab.kangwon.ac.kr/wp-content/uploads/kboard_attached/3/201403/201403310758151089652.pdf


#운영체제
## 디스크 스케줄링
>* FCFS : 순서대로
>![Alt text](http://www.cs.iit.edu/~cs561/cs450/disksched/fcfs.bmp)
>* SSTF : 가까운 것부터
>![Alt text](http://www.cs.iit.edu/~cs561/cs450/disksched/sstf.bmp)
>* SCAN : 방향대로 끝에 찍고 돌아오면서 순회
>![Alt text](http://www.cs.iit.edu/~cs561/cs450/disksched/scan.bmp)
>* C-SCAN : Circular 순환. SCAN 처럼 방향대로 찍었다가 반대쪽부터 시작, 앞뒤가 연결되어 순환한다고 생각
>![Alt text](http://www.cs.iit.edu/~cs561/cs450/disksched/c-scan.bmp)


>* N-Step
>* 에션바흐(Eschenbach)
>* SLTF
>* LOOK : 간혹 나오니 알아두기!
> 이미지 : http://www.cs.iit.edu/~cs561/cs450/disksched/disksched.html
