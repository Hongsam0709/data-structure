# 목적
  자료구조 공부를 하고 차후에 알고리즘 공부를 하기 위함

# 자료구조 목록
  1.  Simple Linked List (연결 리스트)
  2.  Circular Linked List (원형 연결 리스트)
  3.  Stack (스택)
  4.  Queue (큐)
  5.  Deque (덱)
  6.  Tree  (트리)
  7.  Binary Tree (이진트리)
  8.  Priority Queue (우선순위 큐)
  9.  Heap  (힙)
  10.  Sorting (정렬)
  11.  Search (탐색)
  12. Table (테이블)
  13. Hash  (해쉬)
  14. Graph (그래프)

# 참여방법
 ## 아래 순서와 같이 진행하세요
  1.  레파지토리를 fork 합니다.
  2.  clone을 합니다.
    * `git clone [your repoistory]`

## 저장소를 항상 최신상태로 유지하기 원하면 아래와 같이 더 진행하세요.
  1. upstream에 이 레파지토리를 추가합니다.
    * `git remote add upstream https://github.com/HacksDepper/data-structure.git`
  2. 추가된 원격 레파지토리를 확인합니다.
    * `git remote -v`
  3.  fetch를 upstream으로 진행합니다.
    * `git fetch upstream`
  4. upstream/master 브런치에서 master 브런치로 변경합니다.
    * `git checkout master`
  5. 브런치를 병합(merge)합니다.
    * `git merge upstream/merge`

# 커밋 룰
아토믹 커밋을 지향합니다.<br>
(커밋당 1개의 수정 또는 풀이 또는 작업)
  1.  작성한 코딩을 마스터브랜치에 커밋합니다.
    * `git commit -m "메시지"` **커밋 메시지는 아래를 참조합니다.**
  2.  fork한 레파지토리에 반영합니다.
    * `git push origin master`
  3.  PR을 보냅니다.
    * fork한 레파지토리에서 Pull Requests에서 new Pull Request를 발행합니다.
    * Pull Request에 내용을 적습니다. <br>
      ```ex: @yourname stack Java Solution```
    * 내용을 작성한 후 PR을 보냅니다.

##  커밋 메시지룰
한줄로 간단하게 요약하여 작성합니다.<br>
아래 예제를 참조하며 작성합니다.

```
ex: 001 @yourname Java Solution
```

## 파일 이름 규칙
**파일 이름은 반드시 문제_유저이름 으로 만들어주세요. <br>
파일은 반드시 해당 문제의 디렉토리에 넣어주세요.** <br>
아래 예제를 참조하세요.
```
ex1: Dongyeon_Stack.java
ex2: dongyeon-stack.js
ex3: dongyeon_stack.py
```

# 슬랙
슬랙을 사용하여 레파지토리에 대한 정보를 받고 있습니다.<br>
슬랙에 초대를 받고 싶으시면 **Issue**를 보내주세요. <br>
라벨은 slack 으로 해주세요. <br>
```
ex:
  제목 : 슬랙 추가 요청
  내용 : @dongyeonlee 슬랙 추가 해주세요 your@email.com
```

# 자료구조의 추가
추가하고 싶은 자료구조가 있으시면 Issue를 보내주세요. <br>
Issue는 간단하게 보내주시면 됩니다. <br>
라벨은 new로 해주세요. <br>
```
ex:
  제목 : 자료구조 추가요청
  내용 : @dongyeonlee 자료구조 LinkedList 추가해주세요
```

# 참조
1.  윤성우의 열혈 자료구조
