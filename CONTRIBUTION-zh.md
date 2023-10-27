# Contribution (Draft)

Awesome Satori 是用于展示 Satori protocol 社区中各种有趣主题的资源列表，旨在收集和分享与 Satori 相关优秀资源，包括协议实现、SDK、Framework、教程、工具等，帮助其他人学习、发现和使用 Satori。
为了保证质量和一致性，本篇文档将详细描述您应该如何贡献作品。

## 准备工作

在贡献您的作品前，我们需要一点准备工作：

- 拥有一个 GitHub 账号，并 Fork 本仓库
- 对 Satori 有一定了解或者兴趣，并且愿意为社区提供有价值的信息和帮助
- 保证您添加的内容是与 Satori 相关的，并且是高质量的、有用的、有趣的或创新的
- 尊重原创作者的版权和知识产权，并且避免添加任何侵权或违法的内容

## 添加内容

本项目欢迎您添加任何与 Satori 相关的优秀资源，包括但不限于以下类型：

- Satori protocol 实现
- SDK: 基于 Satori 协议的开发工具
- Framework: 使用 Satori 协议进行通信的框架、应用程序
- 教程：如何使用 Satori 及 Satori 协议实现 SDK/Framework 进行开发、部署、测试、调试等操作的指导性文章或视频。
- 工具：帮助你提高 Satori 开发效率或者体验的软件、库、框架、插件等。
- 文章：介绍 Satori 的原理、特性、优势、应用场景等方面的深入性或者广泛性的文章。

### 实现、SDK 与 Framework

在添加 `implementation/SDK/Framework` 贡献内容时，我们将做出如下要求：

- 实现、SDK 与 Framework 将分别放在表格中，有如下字段：
   - `Name`: 您的项目名称，按照英文首字母 A-Z 排序（如果未做单独区分，官方项目将置顶）
   - `Author`: 作者名称，也就是您（应当使用 name，而不是 username。因为 name 在 GitHub 中是唯一的）
   - `Language`: 编写该项目的语言，请注意，**此处仅表示您编写该项目所用语言**
- 请确保 `Name`、`Author` 均有一个地址指向相应主页
- 如果您派生了多个项目（比如 implementation -> SDK），这些项目应当在同一个单元格中，并用 `w/` 表示从属关系
   - 例子：
      | Name | Author | Language |
      | ---  | ---    | ---      |
      | [SPPS](https://github.com/im-patory/spps) w/ [Patory](https://github.com/im-patory/patory) | [Lipraty](https://github.com/Lipraty) | PHP |
- 同作者同语言下如果编写了多个项目，但它们均是同级关系，应当使用 `<br>` 来在一个单元格中放入多个项目
   - 例子：
      | Name | Author | Language |     |
      | ---  | ---    | ---      | --- |
      | [Yutori-QQ](https://github.com/Nyayurn/Yutori-QQ) <br>[Yutori-QQ-SpringBootStarter](https://github.com/Nyayurn/Yutori-QQ-SpringBootStarter) | [@Nyayurn](https://github.com/Nyayurn) | Java | Java **QQ** bot framework SDK based on Satori Protocol |

### 工具集

TODO.

### 教程与文章

TODO.

## 贡献流程

如果您想要为本项目添加内容，请按照以下流程进行操作：

- 将 fork 后的仓库 clone 到本地
- 在本地创建一个新的分支，并在 readme.md 文件中添加您想要贡献的内容
- 在添加内容时，请遵循 Markdown 的语法和格式规范，使用正确的缩进、空格、标点符号等
- 为每个添加的内容提供一个简短的描述，说明它是什么
- 检查您添加的内容是否有重复、失效或错误的链接，并及时修正或删除
- 提交您的更改，并 push 到您的 fork 仓库
- 在 GitHub 上创建一个 pull request，请求将您的分支合并到 awesome-satori 主分支
   - 请保证 PR 标题格式：`Update: [project name]`
- 在 pull request 的正文中简要说明您添加了什么内容，为什么认为它是 awesome 的，以及您是否遵循了以上的指南
- 等待 awesome-satori 的维护者审核和回复您的 pull request，如果有必要，请根据反馈进行修改或补充

## 贡献审核

当您提交了 pull request 后，awesome-satori 的维护者会尽快对您的贡献进行审核，并给出相应的反馈和建议。请注意以下几点：

- 您的 pull request 可能会被接受、拒绝、修改或合并，这取决于您添加的内容是否符合本项目的主题和质量标准，以及是否遵循了本指南的要求
- 您可能会收到来自维护者或者其他贡献者的评论或问题，请尽量友好和礼貌地回复，并提供必要的解释或证据
- 如果您收到了修改或补充的建议，请尽快按照建议进行调整，并更新您的 pull request。如果您对建议有异议，请尽量理性和客观地表达，并提供合理的理由或证据
- 如果您的 pull request 被接受并合并了，请不要删除您的 fork 仓库或分支，以便于后续的更新和维护

最后，十分感谢您对 satori 社区生态做出的努力！我们希望您能享受贡献的过程，并从中获得知识、乐趣和成就感。如果您有任何问题或反馈，请随时发起 issue 与我们交流。
