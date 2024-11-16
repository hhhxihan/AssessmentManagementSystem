# AssessmentManagementSystem





数据库设计：

账号密码表：

| 字段名称 | 类型   | 描述           | 约束     |
| -------- | ------ | -------------- | -------- |
| UsrID    | UUID   | 用户唯一标识符 | 自增主键 |
| user     | Int    | 账号           | 唯一索引 |
| Pwd      | String | 密码           |          |

个人信息表：

| 字段名称        | 类型                     | 描述         | 约束 |
| --------------- | ------------------------ | ------------ | ---- |
| id              | INT                      | 用户唯一标识 | 主键 |
| name            | VARCHAR                  | 姓名         | N    |
| gender          | ENUM('男'，'女'，'保密') | 性别         |      |
| date_of_birth   | date                     | 生日         |      |
| email           | VARCHAR(255)             | 邮箱         |      |
| nationality     | VARCHAR(255)             | 国家/地区    |      |
| highest_degree  | ENUM                     | 最高学历     |      |
| contact_phone   | VARCHAR(255)             | 联系方式     |      |
| document_type   | ENUM                     | 证件类型     |      |
| document_number | VARCHAR(255)             | 证件号码     |      |

