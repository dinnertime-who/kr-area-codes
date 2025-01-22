# kr-area-codes

25년 1월 22일 마지막으로 업데이트된 법정동 데이터 정보입니다.

Nodejs + Typescript + Sqlite로 만들어진 SDK 형식의 라이브러리를 제공합니다.

## API 정리

## DB Schema

Table: codes

```
- id TEXT PRIMARY KEY # 법정동 코드
- name TEXT  # 법정동 이름
- isExist INTEGER  # 존재 여부
```
