# 移动社交应用

在这个选题中，你需要模仿微信，使用 Web 技术实现一个移动社交应用。

这个网站具有以下特点：

- 分享此时、此地个人活动以及心情：
  - 刷存在感，同时获知其他好友的当前状态；
  - 可以有朋友地图，看到选择的朋友在干啥；
  - 参考他人的活动心得，表达心情，释放情感，增强联系。
- 可以认为是极简版“微信”：
  - 重点是好友和朋友圈功能，也可以设置多个朋友圈；
  - 可以单发好友或者群发朋友圈，但是只发：此地、活动、心情；可以是文字或者图片。好友可以回复沟通。
- 可以根据大量的用户数据记录进行一定分析。

## 系统基本功能与流程

> **具体界面设计和功能安排可自由发挥**。~~直接抄微信就行了。~~

### 登录注册页面

- 用户能够通过用户名和密码登录和注册。注册时需要完善用户名、密码、昵称并选择头像（模仿微信登录注册页面）。

### 应用主页

- 包含以下四个 Tab （模仿微信主页）。

#### 聊天 Tab

- 聊天列表，按时间排序，点击进入聊天页面。

#### 好友 Tab

- 好友列表，按字母排序。

#### 动态 Tab

- 查看好友发布的动态。


- 支持发布图片或文字动态，动态需要支持选地点、选心情和输入内容。

#### 用户 Tab

- 用户可以查看并修改自己的基本信息。

### 聊天页面

- 用户能够查看历史聊天记录。
- 支持发送和接收图片和文字消息。

## 技术实现

### 建议

- 采用前后端分离架构。
- 建议使用 ionic 框架开发移动端 Web 应用，也可选择使用 React Native 开发原生应用（难度更大）。

## 评分细则

### 分数组成

- 基本功能分：即完成系统基本内容与流程，满分 100 分。

- 进阶任务分：此项为加分项，可选做一个或两个，能力较强的同学可全选，共 30 分。

- 个人工作分：根据小组分工及个人完成工作量得分。每组组员该项分数总和 30 分，根据贡献比例分摊。

个人最终得分 = 基本功能分 + 进阶任务分 + 个人工作分，值域为 [0, 160]。

### 评分点

| 功能项   | 得分项                    | 最高分数 |
| ----- | ---------------------- | ---- |
| 基本流程  | 注册和登录页面                | 5    |
| （30分） | 聊天 Tab                 | 5    |
|       | 好友 Tab                 | 5    |
|       | 动态 Tab                 | 5    |
|       | 用户 Tab                 | 5    |
|       | 聊天页面                   | 5    |
| 聊天    | 支持发送图片和文字消息            | 10   |
| （15分） | 能够查看历史消息记录             | 5    |
| 动态    | 能够查看好友发送的动态            | 5    |
| （25分） | 支持发送图片和文字动态            | 10   |
|       | 支持地图选点                 | 5    |
|       | 支持分组发送                 | 5    |
| 工程能力  | 文档                     | 5    |
| （30分） | 系统架构                   | 10   |
|       | 代码风格                   | 5    |
|       | 项目完整度和易用性              | 10   |
| 附加功能  | 支持更多种类的消息和动态类型（位置、语音等） | 10   |
| （30分） | 支持为好友添加标签，按已有的标签分组发布动态 | 5    |
|       | 简单的人工智能助手，自动回复消息       | 10   |
|       | 其他合理的附加功能              | 5    |

### 评分点说明

 1. 每一项的分数取决于该项功能的完成度。如“顾客与顾客的聊天功能”，若实现聊天功能可以获得基本分数，若实现了查看历史聊天记录、在聊天中分享商品等功能则分数依次递增。
 2. 项目完整度和易用性评价标准：
    - A.	最低要求为必须实现并完成规定的用户功能与操作。核心功能和技术都有实现，在应用逻辑和实际操作便捷性上可以不做考虑。
    - B.基本要求为实现并完成规定的用户功能和操作，并设计合理便捷的操作流程，系统各部分衔接过度自然，方便使用。
    - C.进阶要求为实现并完成规定的用户功能、操作和进阶加分项，形成一套完整的可发布的应用逻辑。
    - A、B、C 分别对应 0 - 3 分，4 - 6 分，7 - 10 分。
 3. 附加功能必须在文档中明确写出，概述该功能并简要描述实现。
 4. 项目设计文档需要至少包含：
    - 项目组织以及其中每个文件的说明。
    - 关键功能实现的细节。
    - 部署配置的详细介绍。
 5. 团队分工文档需要至少包含：
    - 团队成员、分工、具体完成工作，列出**每个人的贡献比例**。
    - 其他你们想说明的问题。

## 提交

1. 提交物包含以下三项：

   - **源代码**：推荐使用 Git 进行协作，提交到 GitHub 等 Git 托管平台上。
   - **可执行文件**：推荐提供项目的 Docker 镜像或部署在云平台上。
   - **文档**：推荐使用 Markdown 编写项目文档，与源代码一同提交到 Git 托管平台上。
2. 友情提示：请尽早开工，本学期只有一个 Project，临时赶工很有可能完不成。
3. 项目截止时间。