## 学生成绩查询系统V1.0

### 功能描述

使用HTML，Bootstrap，Javascript实现一个学生成绩管理系统（Web版），具有以下功能：

* 添加一条学生成绩信息
* 查询多个学生成绩信息
* 修改一条学生成绩信息
* 删除一条学生成绩信息

#### 第一阶段

实现一个静态页面展示学生成绩信息。

要求：

* 使用Bootstrap table样式
* 允许将学生信息直接写在静态页面里

#### 第二阶段

实现“添加一条学生成绩信息”功能。

要求：

* 以form表单的形式接收用户提交的学生成绩
* 使用Javascript监听表单onSubmit事件
* 提交时进行输入校验，输入必须满足格式：姓名, 学号, 民族, 班级, 学科: 成绩, …，否则提示请按正确的格式输入（格式：姓名, 学号, 学科: 成绩, ...）
* 提交格式正确则将学生成绩存入浏览器的localStorage

#### 第三阶段

在第一阶段实现的静态页面基础上，实现“查询多个学生成绩信息”功能。

要求：

* 允许用户一次查询多个学生的成绩

* 提交时进行输入校验，输入必须满足格式：学号, 学号,...，否则提示请按正确的格式输入要打印的学生的学号（格式： 学号, 学号,…）

* 输入格式正确则将所查询学生的成绩显示出来，并显示他们的总分平均分和总分中位数

#### 第四阶段

在第三阶段实现的查询成绩单页面基础上，实现“修改一条学生成绩信息”功能。

要求：

* 允许用户在查询出学生成绩后进行修改
* 修改提交时进行输入校验，输入必须满足格式：姓名, 学号, 民族, 班级, 学科: 成绩, …，否则提示请按正确的格式输入（格式：姓名, 学号, 学科: 成绩, ...）
* 修改提交格式正确则修改该学生成绩

#### 第五阶段

在第三阶段实现的查询成绩单页面基础上，实现“删除一条学生成绩信息”功能。

要求：

* 允许用户在查询出学生成绩后进行删除
* 删除时弹窗确认确定删除”姓名+学号“的成绩？

### 要求

画 Tasking 图
尽量采用 TDD 开发方式

