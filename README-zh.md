[Switch to EN](https://github.com/fox-one/bugs-hunter/blob/master/README.md)

# Fox.ONE 赏金猎人

## 什么是赏金猎人计划

Fox.ONE 赏金计划为 Bug、Patch 的提交者提供 FOX 积分以及价值币 BOX 作为奖励。参与赏金计划的社区成员称之为“Fox.ONE 赏金猎人”，可以获得额外的奖励和回报。

## 规则与赏金

阅读以下规则，开始狩猎之旅：

- 每一个 BUG 提交称为一个 Issue。
- 提交已经被其它用户提交过的 Issue，或者是 Fox.ONE 团队确认/正在修复/修复了的 Bug，不能获取赏金
- 直接公开严重 Bug 信息无法获得赏金
- Fox.ONE 开发团队成员无法获得赏金
- 计划的最终解释权归 Fox.ONE 团队所有

### 赏金项目范围

1. Fox.ONE 移动客户端（包括 iOS 和 Android 客户端）
2. Fox.ONE 旗下的 Mixin 机器人，包括：
   1. 氢定投
   2. 闪电交易
   3. BOX ATM
   4. 小钱包

### Bug 类型和赏金

Bug 根据其重要程度，依据 [OWASP](https://www.owasp.org/index.php/OWASP_Risk_Rating_Methodology) 风险模型进行定价：

| 影响/出现频率 | 低概率 | 中概率 | 高概率 |
| ------------- | ------ | ------ | ------ |
| 较小影响      | 低   | 中     | 高     |
| 中等影响      | 中     | 高     | 严重     |
| 较大影响      | 高     | 严重     | 非常严重   |

如上分类的奖励如下：

- **非常严重**: 2000+ FC 和 1000+ BOX
- **严重**: 200 - 2000 FC 和 100 - 1000 BOX
- **高**: 50 - 200 FC 和 20 - 100 BOX
- **中**: 10 - 50 FC 和 5 - 20 BOX
- **低**: 1 - 10 FC 和 1 - 5 BOX

### 提交要求

提交的 BUG 需严格按照 Issue 模版的内容填写，包括并不限于：

- **Bug 出现的环境**. 包括 Fox.ONE 版本、平台、机型等信息
- **Bug 描述质量**. 表述有逻辑、清晰的 Issue 提交会获得更多的赏金。
- **Bug 重现步骤**. 请在描述中包含能够重现问题的详细的操作步骤。

### 提交方式

1. 非隐私、安全类 Bug 通过官方 Issues 列表提交 https://github.com/fox-one/bugs-hunter/issues
2. 提交的 Bug 涉及安全问题或者隐私信息，通过 Email [bug@fox.one](mailto:bug@fox.one) 提交

## 免责声明

赏金计划是一个社区实验性项目，它的目的是鼓励社区成员为 Fox.ONE 贡献自己的能力，不断改善 Fox.ONE，而非一个竞赛。作为一个实验项目，Fox.ONE 团队保留最终解释权和随时修改、取消项目规则的权力。最后，请参与者自行根据所在国家地区申报赏金税款，并确保参与行为遵循当地法律法规。

## 常见问题

### 赏金计划有期限吗？

目前没有最终期限。

### 怎么支付赏金？

一旦 Issue 得到 Fox.ONE 团队确认，赏金会在 7 个工作日内通过 Fox.ONE 支付。为了接受赏金，你需要向我们提供你的 Referral Code（在“钱包 - 邀请朋友”中查看）

### 我可以选择将我的赏金捐献给开源组织吗？

可以。如果你这样做，你需要提供捐献的开源组织名称（请参阅“附表：开源组织”）。Fox.ONE 会向该组织捐赠两倍赏金，并在 Donate Leadboard 中添加你的名字、捐献的开源组织和捐赠量。

备注：开源组织存在最低捐款额，或会限制捐款渠道。对此 Fox.ONE 会在达到要求前，暂时持有这一部分捐赠，直到满足捐款条件。

### 我提交了 Issue，但是没收到回应

开发团队非常繁忙，但是我们会尽快回复所有的提交，如果你没有收到回应，请等候五个工作日给我们发 Email。

### 我希望能匿名提交

如果你愿意把奖励捐赠给开源组织，那么可以匿名。否则，匿名提交 Issue 无法获得赏金。

### 我有其它问题

请加入 Fox.ONE 官方 Mixin 群咨询：

- 中文群：7000100217
- 英文群：7000101947

## 开源组织

### OpenSSL

网站：https://www.openssl.org

OpenSSL是用于传输层安全（TLS）和安全套接字层（SSL）协议的强大的商业级功能齐全的工具包。 它也是一个通用的密码学库。Fox.ONE 在网络协议层大量使用 OpenSSL 来保护用户的安全。

### Numpy

网站：http://www.numpy.org

NumPy 是用Python进行科学计算的基础软件包。 Fox.ONE 使用 NumPy 实现定价模型，进行模型验证和回测。

### Vue

网站：https://vuejs.org

Vue 是一个现代化 Web 开发框架和开发套件。Fox.ONE 使用 Vue 来搭建网站和程序。

### webpack

网站：https://webpack.js.org

Webpack 是一套用于构建 Javascript App 的套件。Fox.ONE 使用 Webpack 构建网站和程序。
