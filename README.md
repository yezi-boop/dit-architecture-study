# DiT 扩散 Transformer 架构研读

基于 DiT 原论文及官方 PyTorch 实现，梳理扩散 Transformer 的数据流、条件注入方式和架构设计取舍，并对照 PixArt-α、Open-Sora 讨论图像与视频生成的结构问题。

## 阅读报告

- [在线阅读 Markdown 报告](./DiT扩散Transformer架构研究_技术报告.md)
- [下载 Word 报告](./DiT扩散Transformer架构研究_技术报告.docx)

## 主要内容

- 潜变量如何转换为 Transformer token
- 时间步与类别条件如何进入 DiT block
- patch 大小、token 数与计算成本的关系
- 原论文实验结果与官方源码的对应关系

## 参考资料

- [DiT 原论文](https://arxiv.org/abs/2212.09748)
- [DiT 官方实现](https://github.com/facebookresearch/DiT)
