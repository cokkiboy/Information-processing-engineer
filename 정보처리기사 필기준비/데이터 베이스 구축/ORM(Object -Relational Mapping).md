1) ORM의 개요
- 객체 와 관계형데이터베이스 의 데이터를 연결 하는 기술
- ORM으로 생성된 가상의 객체지향 데이터베이스는 프로그래밍 코드 또는 데이터베이스와 독립적이므로 재사용 및 유지보수 용이
- 직관적이고 간단하게 데이터 조작가능

2) ORM 프레임워크

| 언어     | 프레임워크                                            |
| ------ | ------------------------------------------------ |
| JAVA   | JPA,Hibernate ,Eclipse Link, Data Nucleus, Ebean |
| c++    | ODB,QxOrm                                        |
| Python | Django,SQL Alchemy,Storm                         |
| iOS    | Core DatemDatabase Objects                       |
| .NET   | NHibernate,Database Objects,Dapper               |
| PHP    | Doctrine,Propel,RedBean                          |


3) ORM의 한계
 - 프레임워크가 자동으로 SQL을 작성하기 떄문에 의도대로 작성되었지 확인해야함
 - 객체지향적인 사용 고려와 프로젝트가 크고 복잡해질수록 적용하기 어려워짐
 - 기존의 기업들을 ORM을 고려하지않은 데이터베이스를 사용하고 있기때문에,ORM에 적합하게 변환하려면 많은 시간과 노력필요
 