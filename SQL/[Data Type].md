## [Data Type]

_Data Type 컬럼이 저장되는 데이터 유형, 문자형, 실수, 수소, 자료형 여러 데이터를 식별하는 타입_

- Oracle

문자형 데이터 타입

| 데이터 타입 | 설명                                           |
| ----------- | ---------------------------------------------- |
| VARCHAR2(n) | 가변 길이 문자 / 최대 4000byte / Default 1byte |
| CHAR(n)     | 고정 길이 문자 / 최대 2000byte / Default 1byte |
| LONG        | 최대 2GB 크기의 가변 길이 문자형               |
| CLOB        | 대용량 텍스트 데이터 타입 (최대 4Gbyte)        |

가변 길이란, 실제 입력된 데이터 길이에 따라서 크기가 변하는 것을 의미한다.



숫자형 데이터 타입

| 데이터 타입  | 설명                                                         |
| ------------ | ------------------------------------------------------------ |
| NUMBER(p, s) | 가변 숫자 / p (1 ~ 38, Default 38) / s (-84 ~ 127, Default 0) 22byte |
| FLOAT(p)     | NUMBER의 하위 타입 / p (1 ~ 128, Default 128) 이진수 기준 / 최대 22byte |

p는 소수점을 포함한 전체 자릿수를 의미하고, s는 소수점 자릿수를 의미한다.



날짜 데이터 타입

| 데이터 타입 | 설명                                                         |
| ----------- | ------------------------------------------------------------ |
| DATE        | BC 4712년 1월 1일 부터 9999년 12월 31일, 연, 월, 일, 시, 분, 초 |
| TIMESTAMP   | 연도, 월, 일, 시, 분, 초 + 밀리초까지 입력 가능              |
