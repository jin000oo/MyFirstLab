# [Linux] top, ps, jobs, kill 명령어

## 1. top
- Linux에서 현재 실행되고 있는 프로세스에 관한 시스템 프로세스/메모리 사용 현황을 5초 간격으로 출력하는 명령어  
- 출력 기본값은 현재시간, 시스템 업데이트 시간, 시스템에 로그인한 사용자 수, 지난 1분, 지난 5분, 지난 15분 시스템 평균 부하  
- Microsoft Windows의 작업 관리자와 같은 개념  
  
> ### top [옵션]

   
|옵션|설명|
|-----|-----|
|-b|배치모드로 정보 출력|
|-d delay|지정한 시간의 간격으로 정보 출력|
|-n num|지정한 시간만큼 정보 출력|
|-p pid|지정한 프로세스 ID(pid)의 정보만 출력|
|-q|시간의 간격 없이 정보 출력|
|-s|시큐어 모드|
|-S|누적된 정보 출력|  

  
#### top 단축키 명령어
|명령어|설명|
|-----|-----|
|space|정보 업데이트|
|^L|스크린 초기화|
|F(f)|필드 추가 및 제거|
|O(o)|출력하는 필드의 정렬 순서 변경|
|h(?)|사용 가능한 명령어 출력
|k|프로세스 종료|
|n(#)|출력할 프로세스의 개수 지정|
|s|출력할 정보의 업데이트 시간 지정|
|q|top 종료|

## 2. ps
프로세스의 현재 상태를 출력하는 명령어

ps [옵션]
-A
-N
-a
-d
-e

## 3. jobs


## 4. kill
