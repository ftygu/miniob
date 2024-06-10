**比赛官网**：[Oceanbase数据库大赛-分布式数据库](https://open.oceanbase.com/competition/index)

**初赛总结**：[Summary · Issue #25 · luooofan/miniob-2022](https://github.com/luooofan/miniob-2022/issues/25)

![image](https://user-images.githubusercontent.com/46896167/209488130-621820fa-7e77-4b7d-9893-1e86a1a867cb.png)

# 介绍
miniob 是 OceanBase 与华中科技大学联合开发的、面向"零"基础同学的数据库入门实践工具。
miniob 设计的目标是让同学们快速了解数据库并深入学习数据库内核，期望通过相关训练之后，能够对数据库内核各个模块的功能及其关联有所了解，并能够在
使用数据库时，设计出高效的 SQL 。miniob 面向的对象主要是在校学生，并且诸多模块都做了简化，比如不考虑并发操作。

(注意：此代码仅供学习使用，不考虑任何安全特性。)

[GitHub 首页](https://github.com/oceanbase/miniob)

# 1. 题目说明
[miniob 题目描述](docs/miniob_topics.md) 

# 2. 开发指南
## 搭建开发环境
1. [本地配置gcc环境](docs/how_to_build.md)。
2. [使用Docker开发](docs/how-to-dev-using-docker.md)。
3. [在Windows上使用Docker](docs/how_to_dev_miniob_by_docker_on_windows.md)。

## 词法、语法解析
请参考 [miniob 词法语法解析开发与测试](docs/miniob-sql-parser.md)。

# 3. 提交测试
题目完成并通过自测后，大家可以在 [miniob 训练营](https://open.oceanbase.com/train?questionId=200001) 上提交代码进行测试。

客户端输出需要满足一定要求，如果你的测试结果不符合预期，请参考 [miniob 输出约定](docs/miniob-output-convention.md)。

# Contributing

OceanBase 社区热情欢迎每一位对数据库技术热爱的开发者，期待与您携手开启思维碰撞之旅。无论是文档格式调整或文字修正、问题修复还是增加新功能，都是参与和贡献 OceanBase 社区的方式之一。现在就开始您的首次贡献吧！更多详情，请参考 [社区贡献](CONTRIBUTING.md).

# License

MiniOB 采用 [木兰宽松许可证，第2版](https://license.coscl.org.cn/MulanPSL2), 可以自由拷贝和使用源码, 当做修改或分发时, 请遵守 [木兰宽松许可证，第2版](https://license.coscl.org.cn/MulanPSL2). 

# 社区组织

- [OceanBase 社区交流群 33254054](https://h5.dingtalk.com/circle/healthCheckin.html?corpId=dingd88359ef5e4c49ef87cda005313eea7a&1fe0ca69-72d=16c86a07-83c&cbdbhh=qwertyuiop&origin=1)
- [OceanBase 大赛官方交流群 35326455](https://qr.dingtalk.com/action/joingroup?code=v1,k1,g61jI0RwHQA8UMocuTbys2cyM7vck2c6jNE87vdxz9o=&_dt_no_comment=1&origin=11)
- [OceanBase 官方论坛](https://ask.oceanbase.com/)
