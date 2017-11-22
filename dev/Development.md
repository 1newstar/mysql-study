# Development
开发设计


## Plan and Design
规划

- 容量规划
  - 业务增速？极限在哪？
- 分库分表
  - “合久必分，分久必合”

## Model
建模

- 业务架构
- 业务逻辑、关联关系
- [数据类型 Data Types](model/DataTypes.md)
- [索引约束](model/IndexConstraint.md)

## SQL开发

- [SQL语言(Structured Query Language)](../sql_scripts/sql_dev/sql_demo.sql)
- 语法标准
  - ANSI SQL-89
  - ANSI SQL-92
- 范式  
- 设计规范
- [审核 Audit](audit/Audit.md)
  - [audit log](../mgmt/Maintenance/Log/audit_log.md)

## Transactions and Locking
事务和锁

- [Transactions](transactions/Transaction.md)
- [Locking](locking/Locking.md)

## Programming Inside MySQL

- Stored Routines
  - [Stored Procedure](../sql_scripts/sql_program/ex_procedure.sql)
  - [Stored Function](../sql_scripts/sql_program/ex_function.sql)
- [EVENT](../sql_scripts/sql_program/ex_event.sql)
- [TRIGGER](../sql_scripts/sql_program/ex_trigger.sql)
- VIEW
- [Privileges](../sql_scripts/sql_program/ex_privilege.sql)
- [EXAMINE](../sql_scripts/sql_program/examine.sql)

## Reference

- [condition-handling](https://dev.mysql.com/doc/refman/5.6/en/condition-handling.html)
- [example database](https://dev.mysql.com/doc/index-other.html)
- [test-db](https://launchpad.net/test-db/)