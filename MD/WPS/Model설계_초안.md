##회원관리

data |
--- |
username |
nickname |
password |
email |
profile_img |
follower |
mobile-phone-number|

> 핸드폰 번호는 연동가입에서 얻어올 수도 있음

##장소 등록

data |
--- |
placename|
latitude |
logitude |
address |
phonenumber |

장소에 대한 추가 정보(유저테이블과 장소 테이블의 중간자모델이 될 것임) |
--- |
author ID |
place ID |
comment |
photo |
visited_time |


> 방문 시간 데이터가 많이 축적되면 중복값이 높아진다. 시간 테이블을 따로 만들어 참조하게 하는 것으로 해결할 수 있나?


##위치 및 장소 검색
검색 히스토리
검색 자동완성

-
google / naver / daum 지도 세가지 api를 모두 사용. 우선순위를 코드에서 지정하거나, 앱 초기 사용시 사용자의 선택으로 본인에게 익숙한 지도를 우선검색할 수 있게 한다. 


장소의 카테고리 관리는 어떻게 할 것인가?