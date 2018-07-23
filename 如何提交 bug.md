## 如何提交 bug

PRESS.one 使用 Github issues 作为主要的 bug 反馈渠道，为了保障 bug 的及时处理与后续的奖励发放，请按如下标准创建一条 issue。

**提交原则**

- 确保每个 issue 为一个独立的 bug
- 根据创建 issue 时的模板完善必要信息：如标题、描述、截图、Mixin ID 等

### 创建 issue

一条完整的 issue 包含如下信息：

- 标题：[平台-bug 级别] bug 简要描述

  平台：Android、iOS、Web

  bug 级别：参考末尾

  > 示例：[Android-Minor] 登录失败提示不友好

- 内容：必要信息

    参考创建 issue 的默认模板

    > 示例：
    >
    > Bug 描述：登录失败提示「keystore 不存在」，用户难以理解。
    >
    > 截图：（插入图片）
    >
    > Mixin ID: 000000

[点击这里创建一条 issue](https://github.com/Press-One/issues/issues/new?title=[平台-bug+级别]+bug+简要描述)

### Bug 分级

- Vital 
  - 程序崩溃，无法使用该功能或者继续下一个流程
  - 程序不响应 (ANR)
  - 安全性问题
- Urgent
  - 经济系统相关异常表现（赞赏、交易记录）
  - 数据丢失或错乱
  - 功能实现与需求严重不符
  - 功能没有完全实现
- Normal (功能存在缺陷但不会影响使用)
  - 触发条件极端 (容错性方面存在不足)
  - 违背用户直觉的表现
  - 程序接口错误
- Minor (功能存在瑕疵但不会影响使用)
  - 样式问题
  - 消息、提示错误或者不合理
- Advice:
  - 设计不合理且有更好实现方式的建议或者意见
