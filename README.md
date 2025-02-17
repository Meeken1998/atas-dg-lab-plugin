<h1 align="center">
  ⚡ DG-LAB ATAS 风控插件
</h1>

<p align="center">
  <i>「让“亏麻了”从玩笑变成现实」</i>
</div>

<p align="center">
  <a href="https://github.com/Meeken1998/dg-lab-atas/releases">
    下载客户端
  </a>
  <span>&nbsp&nbsp</span>
  <a href="https://meeken1998.github.io/dg-lab-atas">
    网页小组件
  </a>
</p>

> [!NOTE]
> 🤗  [网页小组件](https://meeken1998.github.io/dg-lab-atas) 已发布！
> 注意：网页小组件需配合软件使用，否则是连不上电击器的，详情请看 [使用方法](#使用方法)


## 真实反馈

> *“开到 15 之后我现在手自己在抖。”* —— Deltapex 创始人 Alex
>
> *“我草！”* —— Deltapex 六期学员佳俊
> 
> *“为了节目效果，我愿意贡献 10 度电。”* —— 某 GC 交易员
> 
> *“deep♂delta♂petas”* —— Deltapex 一期学员 Hermite
> 
> *“不是我真的来园区了？”* —— 某 GC 交易员

## 简介

> [!WARNING]
> 免责声明：
> 请认真阅读并严格执行 DG-LAB App 的安全指南，不要将配件用在胸部、头部等重要部位，否则可能造成伤害！
> 
> 这是一个娱乐项目，代码仅个人使用！任何使用本插件进行交易的行为均由使用者自行承担风险，作者不承担任何责任！

本项目使用 DG-LAB 🐺 郊狼情趣电击来执行 ATAS 期货交易风控。

`DG-LAB` 是一个国内知名的 BDSM 玩具公司，项目主要使用他们的“郊狼 3.0 电击器”来执行风控惩罚。

`ATAS` 是一款知名的订单流交易软件，能交易很多外盘期货品种。

## 插件功能

### 😡 扛单风控

订单动态浮亏时，放电进行风控，令交易员在扛单时不“心疼”也会“肉疼”。

### 🔒 连损风控

订单连续止损时，放电进行风控，并支持设置强制休息时间。

### ⚡ 灵活设置电流强度

既可设置固定值，也支持通过浮亏金额动态计算。

### 🎥 直播友好

提供网页小组件，可内嵌到 OBS 中，保证直播间节目效果爆炸。

## 使用方法

1. 确保你有一台“郊狼 3.0 情趣电击器”，并已 [下载 App](https://www.dungeon-lab.com/app-download.php)
2. [下载最新版客户端](https://github.com/Meeken1998/dg-lab-atas/releases) ，或拉下代码自行构建
3. 将 `DgLabAtasIndicator.dll` 放到 `ATAS\Indicators` 目录下，通常在“文档”目录中能找到
4. 右击任一图表 - 指标 - 搜索 `DgLabIndicator`，双击添加
5. 启动 `DgLabAtas.exe` 客户端，如果一切正常，你会看到一个二维码
6. 打开手机上的 DG-LAB App，进入 SOCKET 控制模式，扫码连接
7. （可选）如需在本地使用网页小组件，启动 `WebPage.exe`，推荐使用 [🤗 直播网页小组件](https://meeken1998.github.io/dg-lab-atas/index.html)

## FAQs

### 我会受伤吗？

如果严格按照 DG-LAB App 的安全提示来使用配件，答案是：不会。

郊狼的本质是成人用品，原本的使用部位通常更敏感，贴在手臂或腿部完全没问题。

同时他们的产品认证也是齐的，如 CE，FCC，RoHS 等，这是我选择它作为惩罚道具的原因。

电流强度也是可控的。即便强度开到上限（200），也不会导致触电。同时官方的 App 提供了非常多功能保障安全，比如强度上限，修改映射值等待，推荐进行设置。

当然，凡事无绝对，请务必阅读 App 的安全指南进行操作，并在感到不适时立即关闭设备与客户端程序，切记量力而行！

### 为什么需要这个插件？

因为个人感觉，期货交易要想稳定盈利，技术与心态一半一半，空有技术，心态不行也会导致亏损。几乎所有老交易员都爆过仓。

此外，订单流交易非常强调一致性，但订单流这门技术本身又是最容易打破一致性的，因为节奏更快，持仓时间更短，波动更大，像我这样的菜鸡交易员是很难管住手的。

浮亏通常是扛单、逆向加仓、撤止损单等不良习惯导致的。浮亏的感觉很让人懊恼，会想着要是有外力能阻止我就好了，遂开发了这个插件。

### 我可以如何使用这个开源项目？

你可以在遵循 MIT 协议的前提下任意使用。

另外，由于开发时间很短，代码难免有 bug，欢迎进行测试与贡献功能。

### 启动了服务和网页小组件，但没有数据？

请检查 ATAS 是否是以管理员模式启动的，由于程序需要向 `C:\trade.txt` 写入交易日志，所以需要管理员权限。

## 关于

作者：[猫有点大@bilibili](https://space.bilibili.com/39903717)

致谢：[PyDGLab-WS](https://github.com/Ljzd-PRO/PyDGLab-WS)，极大地降低了开发成本，比官网的示例好用多了（
