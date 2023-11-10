# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목6

1. 순서가 있는 목록
2. 순서가 있는 목록
    1. 순서가 있는 목록
    2. 순서가 있는 목록


- 순서가 없는 목록
  - 대쉬(hyphen)
  + 더하기(pluss sign)
  * 별표(asterisks)
 
 ### 링크(links)
 [구글](https://www.google.com)   
 [네이버](https://naver.com)   
 [구글홈페이지]<https://google.com>   
 [네이버홈페이지]<https://www.naver.com>   
 <!-- 대괄호에는 밖에 보여질 이름 / 괄호안에는 이동 링크 -->

 ### 이미지(Images)
 ![김민재](https://search.pstatic.net/common?type=b&size=216&expire=1&refresh=true&quality=100&direct=true&src=http%3A%2F%2Fsstatic.naver.net%2Fpeople%2F75%2F201901031815151401.png)   

 [![구글](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png)](https://google.com)

 ![스타벅스로고](./asset/Starbucks_Coffee_Logo.png)


### 인라인 (inline) 코드 강조
`백틱1개`는 `인라인 코드 강조`를 의미한다.

```JAVA
   public class Exam{
        public static void main(String[] args){
         System.out.println("exam");}
    }
```
<!-- 3백틱```으로 열고 닫으면 내가 작성한 코드 그대로 인터페이스에 출력 / 3백틱 다음에 출력하는 타입을 적어주면 색깔 구분되어 출력됨-->

### 표(table)
|이름|성별|주소|
|---|---|:---:|
|홍길동|남|경기도 화성시|
|김민재|남|서울 서초구|

<!-- |로 테이블 영역 구분하여 작성 가능 / 제일 위 구분 다음 들어오는 |---|이 부분이 없으면 표 만들어지지 x / 두번째 줄인 |---|부분에 :(콜론)으로 표시하면 정렬 기능_양쪽에 기입하면 가운데 정렬-->

### 인용문(block Quote)
> 타인의 말이나 문장을 직접 똔느 간접으로 가져온다.
>> 인용문1
>>> 인용문2

### 수평선(Horizental Rule)
<!-- 3개 이상의 특수기호를 작성하면 수평으로 선이 만들어 짐 -->

---
***
___

### 줄바꿈 (line breaks)
바다 <br>
하늘<!--띄어쓰기 3번이상 하면 줄바꿈 됨 -->   
땅

----

# TIL

 

## 리눅스 명령어

 

1. ls

 

   > list(목록)

 

2. cd

   change directory (작업 경로 변경)

 

3. rm

   remove (파일 삭제)

 

4. mkdir  

   make directory(작업목록 생성)

 

5. rmdir  

   remove directory(작업목록 삭제)

 

6. touch  

   파일생성

 

7. cat

   파일의 내용 출력

 

## Git

 

1. init  

   git 생성

2. add <파일명>  

   staging area로 이동

3. commit -m <메세지>  

   Repository로 이동

4. push <원격저장소><브랜치>  

   원격(GitHub)으로 이동

5. pull <원격저장소><브랜치>  

   원격에서 로컬로 복사

6. clone <원격저장소><브랜치>  

   원격에서 로컬로 복제

 

7. status  

   Staging Area의 상태

8. log  

   repository의 상태

