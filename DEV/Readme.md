# DEV

## 规划

- 容量规划
  - 业务增速？极限在哪？
- 分库分表
  - “合久必分，分久必合”



## 建模

- 业务架构
- 业务逻辑、关联关系
- 数据类型
- [索引](IndexConstraint/Readme.md)

## SQL开发

- 语法标准
  - ANSI SQL-89
  - ANSI SQL-92
- 设计规范
- [审核 Audit](Audit/Readme.md)


## SQL编程 ROUTINE

- 视图 VIEW
- 函数 FUNCTION
- 存储过程 PROCEDURE
- 触发器 TRIGGER
```
触发顺序：

UPDATE:
	BEFORE INSERT
	BEFORE UPDATE
	AFTER UPDATE

INSERT:
	BEFORE INSERT
	AFTER INSERT

```