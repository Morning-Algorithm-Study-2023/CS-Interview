# CS-Interview

`Since 2023-06-26`

#### ⚠️ 자료 저작권 때문에 레포 설정을 public에서 private으로 변경했습니다. private으로 유지부탁드려요.

</br>

## 📍 계획

### 1. 일정
주 2일(화, 목), 오후 9시 알고리즘 스터디 종료 후  
</br>

### 2. 방식

- 주어진 질문에 대해 학습 후 2줄 분량으로 간략하게 답변 작성
- 꼬꼬무 질문에 대한 답변 작성
- 오후 9시 알고리즘 스터디 종료 후 각자 작성한 답변 발표
  </br>

### 3. 참고 강의

[기출로 대비하는 개발자 전공면접 [CS 완전정복]](https://www.inflearn.com/course/lecture?courseSlug=%EA%B0%9C%EB%B0%9C%EC%9E%90-%EC%A0%84%EA%B3%B5%EB%A9%B4%EC%A0%91-cs-%EC%99%84%EC%A0%84%EC%A0%95%EB%B3%B5&unitId=103319&tab=curriculum)

```
[자료구조]
* Day 01. Array vs LinkedList
* Day 02. Queue vs Stack
* Day 03. Hash table vs BST

[운영체제]
* Day 04. process & Thread
* Day 05. Memory

[데이터베이스]
* Day 06. DB 구조 & 설계
* Day 07. Transaction
* Day 08. Index

[네트워크]
* Day 09. TCP/IP
* Day 10. HTTP
* Day 11. Authorization
```

</br>
</br>

## 🗂️ 질문 리스트

### Day 01. Array vs Linked List
|                                                            **질문**                                                            |
| :----------------------------------------------------------------------------------------------------------------------------: |
|                                                 Array는 어떤 자료구조 인가요?                                                  |
| [꼬꼬무1] 미리 예상한 것보다 더 많은 수의 data를 저장하느라 Array의 size를 넘어서게 됐습니다. 이때, 어떻게 해결할 수 있을까요? |
|                                             Dynamic Array는 어떤 자료구조 인가요?                                              |
|                            [꼬꼬무1] Dynamic Array를 Linked List와 비교하여 장단점을 설명해주세요.                             |
|                                              Linked List에 대해서 설명해 주세요.                                               |
|                               [꼬꼬무1] 어느 상황에 Linked List를 쓰는게 Array보다 더 나을까요?                                |
|                               [꼬꼬무2] 어느 상황에 Array를 쓰는게 Linked List보다 더 나을까요?                                |
|              [꼬꼬무3] Array와 LinkedList의 Memory allocation은 언제 일어나며, 메모리의 어느 영역을 할당 받나요?               |
|                                        Array vs Linked List를 비교해서 설명해주세요. ⭐                                        |

### Day 02. Queue vs Stack
|                          **질문**                           |
| :---------------------------------------------------------: |
|                Queue는 어떤 자료구조인가요?                 |
| [꼬꼬무1] Array-Base와 List-Base의 경우 어떤 차이가 있나요? |
|                Stack은 어떤 자료구조인가요?                 |
|        Stack 두 개를 이용하여 Queue를 구현해 보세요         |
|     [꼬꼬무1] 시간복잡도는 어떻게 되는지 설명해 주세요      |
|        Queue 두 개를 이용하여 Stack를 구현해 보세요         |
|     [꼬꼬무1] 시간복잡도는 어떻게 되는지 설명해 주세요      |
|     Queue vs Priority Queue를 비교하여 설명해 주세요 ⭐     |

### Day 03. Hash table & BST
|                                          **질문**                                          |
| :----------------------------------------------------------------------------------------: |
|                               BST에 대해 설명해 주세요 ⭐⭐                                |
|                   [꼬꼬무1] 이진트리(Binary tree)는 어떤 자료구조인가요?                   |
| [꼬꼬무2] BST의 worst case 시간복잡도는 O(n)입니다. 어떠한 경우에 worst case가 발생하나요? |
|                              [꼬꼬무3] 해결방법은 무엇인가요?                              |
|                           Hash table은 어떤 자료구조인가요? ⭐⭐                           |
|                       [꼬꼬무1] 좋은 hash function의 조건은 뭘까요?                        |
|   Hash table에서 collision이 발생하면 어떻게 되나요? 해결방법엔 뭐가 있을까요? ⭐⭐⭐⭐    |
|           [꼬꼬무1] worst case의 시간복잡도는 O(n)이라고 했는데 어떤 상황인가요?           |
|                [꼬꼬무2] 이중 해싱(double hashing)이 무엇인지 설명해주세요                 |

### Day 04. Process & Thread
|                                    **질문**                                    |
| :----------------------------------------------------------------------------: |
|                         Process를 간단히 설명해 주세요                         |
| [꼬꼬무1] process의 memory영역(code, data, stack, heap)에 대해서 설명해 주세요 |
|                 Multi process에 대해서 설명해 주세요 ⭐⭐⭐⭐                  |
|                   [꼬꼬무1] process의 context는 무엇인가요?                    |
|     [꼬꼬무2] PCB(Process Control Block)에 저장되는 것들은 무엇이 있나요?      |
|                [꼬꼬무3] Context switch에 대해서 설명해 주세요                 |
|               [꼬꼬무4] process의 state에는 어떤 것들이 있나요?                |
|                    Multi thread에 대해서 설명해 주세요 ⭐⭐                    |
|         [꼬꼬무1] thread는 왜 독립적인 stack memory 영역이 필요한가요?         |
|                 [꼬꼬무2] process와 thread를 비교설명 해주세요                 |
|             Multi process와 Multi thread를 비교설명해 주세요 ⭐⭐              |
|        [꼬꼬무1] multi thread가 multi process보다 좋은 점은 무엇인가요?        |
|    multi process 환경에서 process간에 데이터를 어떻게 주고 받을 까요? ⭐⭐     |
|                   [꼬꼬무1] IPC의 예시를 들어주실 수 있나요?                   |
|       [꼬꼬무2] 공유 메모리와 메시지 전달 모델의 장단점을 설명해 주세요        |
|       Multi process/thread 환경에서 동기화 문제를 어떻게 해결하나요? ⭐        |
|             [꼬꼬무1] mutex와 semaphore 기법을 비교 설명해 주세요              |
|                교착상태(Deadlock)에 대해서 간단히 설명해 주세요                |
|                   [꼬꼬무1] deadlock은 언제 발생하게 되나요?                   |

### Day 05. Memory
|                                        **질문**                                        |
| :------------------------------------------------------------------------------------: |
|                                   paging이란 뭔가요?                                   |
|                          segmentation에 대해서 설명해 주세요                           |
| [꼬꼬무1] segmentation의 메모리 단편화(Memory fragmentation) 문제에 대해 설명해 주세요 |
|                    [꼬꼬무2] paging과 segmentation의 차이는 뭔가요?                    |
|                 [꼬꼬무3] paged segmentation의 기법에 대해 설명하시오                  |
|                         가상 메모리에 대해서 설명해 주세요 ⭐                          |
|                 [꼬꼬무1] 요구페이징 (demand paging)이란 무엇인가요? ?                 |
|     [꼬꼬무2] 페이지 교체 알고리즘(replacement algorithm)을 아는대로 말씀해주세요      |
|                [꼬꼬무3] LRU알고리즘과 LFU알고리즘을 비교 설명해 주세요                |

### Day 06. DB구조 & 설계
|                         **질문**                         |
| :------------------------------------------------------: |
|           primary key가 무엇인지 설명해 주세요           |
| [꼬꼬무1] primary key와 foreign key에 대해 설명해 주세요 |
|        [꼬꼬무2] candidate key에 대해 설명하시오         |
|        [꼬꼬무3] alternate key에 대해 설명하시오         |
|        [꼬꼬무4] composite key에 대해 설명하시오         |
|  관계형 데이터베이스의 N:M 관계에 대해서 설명해 주세요   |
|        [꼬꼬무1] 1:N 관계에 대해서 설명해 주세요         |
|     left outer join, inner join 차이를 설명해 주세요     |
|           RDB - NoSQL를 비교 설명해 주세요 ⭐            |
|        [꼬꼬무1] Nosql은 언제 사용하면 좋을까요?         |
|         [꼬꼬무2] RDB는 언제 사용하면 좋을까요?          |

### Day 07. Transaction
|                      **질문**                       |
| :-------------------------------------------------: |
|       Transaction을 간단히 설명해 주세요 ⭐⭐       |
|   [꼬꼬무1] commit과 rollback에 대해 설명해보세요   |
| [꼬꼬무2] 원자성(일관성, 고립성, 지속성)이 뭔가요?  |
|       Deadlock이란 무엇인지 설명해 주세요 ⭐        |
| [꼬꼬무1] deadlock을 해결하려면 어떻게 해야 하나요? |

### Day 08. Index
|                                                        **질문**                                                        |
| :--------------------------------------------------------------------------------------------------------------------: |
|                                                 Index가 왜 필요한가요?                                                 |
|                              [꼬꼬무1] select의 성능을 높일 수 있는 방법은 뭐가 있을까요?                              |
|                                    [꼬꼬무2] index의 내부동작은 어떻게 동작하나요?                                     |
|                                       [꼬꼬무3] index를 많이 생성하면 안되나요?                                        |
|                                 index를 어느 column에 사용하는 것이 좋을까요? ⭐⭐⭐⭐                                 |
|               [꼬꼬무1] index를 쓰면 성능이 좋아지니까 모든 컬럼에 인덱스를 사용하면 성능이 더 좋겠네요?               |
|                      [꼬꼬무2] 우리 회사의 고객 DB에서 성별 column에 index를 걸어주는게 좋을까요?                      |
| [꼬꼬무3] true 또는 false 값을 갖는 column에서, true 1%, false 99%의 비율로 구성된 상황에서는 index를 거는게 좋을까요? |
| 데이터를 검색을 할 때 hash table의 시간복잡도는 O(1)이고 b+tree는 O(logn)으로 더 느린데 왜 index는 hash table이 아니라 b+tree로 구현되나요? ⭐ |

### Day 09. TCP/IP
|                      **질문**                      |
| :-------------------------------------------------: |
|  OSI 7계층과 TCP/IP 4계층을 비교하여 설명해 주세요  |
|       TCP vs UDP를 비교해서 설명해 주세요 ⭐        |
| 3-way handshake는 무엇이고 각 과정은 어떻게 되나요? |

### Day 10. HTTP
|                                             **질문**                                              |
| :-----------------------------------------------------------------------------------------------: |
|                                     HTTP가 뭔지 설명해 주세요                                     |
|                   HTTP request method 중 GET vs POST를 비교 설명해 주세요 ⭐⭐                    |
|                [꼬꼬무1] HTTP request method 중 put vs patch를 비교 설명해 주세요                 |
|                              HTTP Status code에 대해서 설명해 주세요                              |
| www.google.com을 주소창에 쳤을 때 화면이 나오기까지의 과정을 네트워크 관점으로 설명해 주세요 ⭐⭐ |

### Day 11. Authorization
|                           **질문**                            |
| :-----------------------------------------------------------: |
|            쿠키와 세션의 차이점을 설명해 주세요 ⭐            |
| [꼬꼬무1] 세션이 보안도 좋은데 쿠키를 사용하는 이유는 뭔가요? |
|       [꼬꼬무2] 쿠키의 사용 예를 아는대로 말씀해 주세요       |
| 쿠키와 세션을 이용한 로그인 방식을 화이트보드에 설명해 주세요 |
</br>
</br>

## 🆗 답변 업로드

- 해당 일에 주어진 질문들의 답변을 작성 후 `solve`로 링크 연결 (md 파일형식으로 올릴 시 파일 형식 : Day01/이름.md)

|   Date   |  Day   |  Subject  |   **이주희**  |  **강승우**  |   **최태승**  | 진행 여부 |
| :------: | :----: | :------: | :------: | :------: | :----: | :-------: |
| 23/06/26 | Day 01 | Array vs Linked List | <a href="/Day01/이주희.md">solve</a> | <a href ="https://seungmu.tistory.com/483">solve</a> | <a href ="/Day01/최태승.md">solve</a> | ✅ |
| 23/06/27 | Day 02 | Queue vs Stack | <a href="https://standing-begonia-7c8.notion.site/Day-02-Queue-vs-Stack-7c5f00c9a04d47a28dc16e968bd0c019?pvs=4">solve</a> | <a href ="https://seungmu.tistory.com/484">solve</a> | <a href ="/Day02/최태승.md">solve</a> | ✅ |
| 23/06/28 | Day 03 | Hash table & BST | <a href="https://standing-begonia-7c8.notion.site/Day-03-Hash-table-BST-3b94f5f4bde040698d8408169910e88b?pvs=4">solve</a> | <a href ="https://seungmu.tistory.com/486">solve</a> |  - | ✅ |
| 23/07/04 | Day 04 | process & Thread |   | <a href ="https://seungmu.tistory.com/488">solve</a> | -  |   |
| 23/07/06 | Day 05 | Memory |   | <a href="https://seungmu.tistory.com/491">solve</a>  | -  |   |
| 23/07/11 | Day 06 | DB 구조 & 설계 |   | <a href="https://seungmu.tistory.com/493">solve</a> | -  |   |
| 23/07/13 | Day 07 | Transaction |   |   | -  |   |
| 23/07/18 | Day 08 | Index |   |   | -  |   |
| 23/07/20 | Day 09 | TCP/IP |   |   | -  |   |
| 23/07/25 | Day 10 | HTTP |   |   |  - |   |
| 23/07/27 | Day 11 | Authorization |   |   | -  |   |
</br>

## Member 👨🏻‍💻

<table>
  <tr>
    <td height="20px" align="center"><a href="https://github.com/joohee56">
      <img src="https://avatars.githubusercontent.com/joohee56" width="100px"/> <br><br> 이주희 <br>(Back-End) </a> <br></td>
    <td height="20px" align="center"><a href="https://github.com/ksw13">
      <img src="https://avatars.githubusercontent.com/ksw13" width="100px"/> <br><br> 강승우 <br>(Back-End) </a> <br></td>
     <td height="20px" align="center"><a href="https://github.com/isshosng">
      <img src="https://avatars.githubusercontent.com/isshosng" width="100px"/> <br><br> 최태승 <br>(Back-End) </a> <br></td>
  </tr>
</table>
</br>
