# sql-syain
```sql
CREATE TABLE `社員マスタ` (
  `社員コード` varchar(4) NOT NULL,
  `氏名` varchar(50) DEFAULT NULL,
  `フリガナ` varchar(50) DEFAULT NULL,
  `所属` varchar(4) DEFAULT NULL,
  `性別` int(11) DEFAULT NULL,
  `作成日` datetime DEFAULT NULL,
  `更新日` datetime DEFAULT NULL,
  `給与` int(11) DEFAULT NULL,
  `手当` int(11) DEFAULT NULL,
  `管理者` varchar(4) DEFAULT NULL,
  `生年月日` datetime DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;
```
