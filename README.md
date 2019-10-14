# Todo 个人待办事项

简介
------
- 实现个人待办事项的记录和管理
- 支持待办事项的添加、删除、一键标记和切换已完成和未完成待办事项功能
- 使用 MySQL 进行数据存储，使用 Django ORM，实现注册、登录和 Session 管理

项目结构
-------
./todo_django 项目的配置
./todo todo 和登陆和注册代码

如何运行
--------
- 使用 pip 安装`pip install django mysql-connector-python`
- 手动在 MySQL 中创建数据库并在 `settings.py` 中修改数据库配置
- 终端下执行 `python manage.py migrate`
