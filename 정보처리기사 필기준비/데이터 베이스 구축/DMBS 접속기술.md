1) 웹  응용 시스템 의 구조
- 사용자 <-> 웹서버 <-> WAS<->DBMS

2) DBMS 접속기술
JDBC(Java Database Connectivity)
- 접속하려는 DBMS에 대한 드라이버가 필요

ODBS(Open Database Connectivity)
3) 정적SQL vs 동적SQL
 

|        | 정적 SQL                    | 동적SQL                         |
| ------ | ------------------------- | ----------------------------- |
| SQL 구성 | 커서를 통한 정적처리               | 문자열 변수에 담아 동적처리               |
| 개발 패턴  | 커서의 범위 안에서 반복문을 활용해 SQL작성 | NVL함수를 사용할 필요 없이로직을 통해 SQL 작성 |
| 실행 속도  | 빠름                        | 느림                            |
| 사전검    | 가                         | 불가능 -> SQL변형위험                |
