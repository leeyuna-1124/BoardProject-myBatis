# BoardProject
게시판
Java
MyBatis+Mysql+SpringBoot+Maven

-board 테이블

스키마
[example_board.zip](https://github.com/leeyuna-1124/BoardProject/files/7032624/example_board.zip)

| Column Name  | DataType    | Condition               |
|--------------|-------------|-------------------------|
| boardIdx(pk) | int         | NOT NULL AUTO_INCREMENT |
| title        | varchar(45) | DEFAULT NULL            |
| content      | varchar(45) | DEFAULT NULL            |
| regDate      | date        | DEFAULT NULL            |

