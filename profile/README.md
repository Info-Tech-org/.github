<div align="center">

<!-- Logo & 品牌主视觉 -->
<a href="https://infotech-launch.vercel.app/">
  <img src="https://raw.githubusercontent.com/Info-Tech-org/.github/main/assert/1NF0TECH_LOGO.svg" alt="1NF0TECH · 语镜" width="320" />
</a>

<br/>

<img src="https://raw.githubusercontent.com/Info-Tech-org/.github/main/assert/brand-assets/00-brand-title.png" alt="语镜 INFOTECH — 家庭对话的语义安全层" width="520" />

---

### 在伤害成型之前，把对话接住

> 家庭关系，常被「爱」所困：关心孩子，却不知如何好好说话；情绪上来时话已出口，事后才后悔。  
> 研究指出，家庭日常沟通中的**无意识言语伤害**是青少年心理问题的重要导因（王晓丽，2018）。我们相信：每一句没说出口的后悔，都可以少一点。

*Backed by 深圳科创学院 · [INFO-TECH LAB](https://infotech-launch.vercel.app/)*

<br/>

[![官网 Website](https://img.shields.io/badge/官网-infotech--launch-2563eb?style=for-the-badge&logo=vercel)](https://infotech-launch.vercel.app/)
[![Dialog 主仓](https://img.shields.io/badge/Dialog-主仓库-111827?style=for-the-badge&logo=github)](https://github.com/Info-Tech-org/Dialog)
[![宣言 Manifesto](https://img.shields.io/badge/宣言-Manifesto-6b7280?style=for-the-badge)](../manifesto.md)
[![品牌素材 Brand](https://img.shields.io/badge/品牌素材-PPT与海报-7c3aed?style=for-the-badge)](../assert/brand-assets/)

---

## 我们在做什么

**语镜** —— 一个「**事后有复盘、当下可提醒**」的辅助系统。  
不是监控，也不是裁判：用实时语义识别与边缘推理，在情绪过线前轻轻提醒，在冲突过后陪你复盘。  
主要用于**家庭日常沟通**，尤其是情绪容易升级的亲子或家庭成员对话里 —— **帮助家长觉察沟通风险、调整行为**，而不是直接干预或代替你说话。  
目标很简单：**让家长看见自己，让孩子少一点沉默。**

---

## 用户痛点 → 我们怎么接住

| 场景 | 难处 | 语镜做什么 |
| :--- | :--- | :--- |
| ① 情绪上头 | 伤害言语难自察 | 语音识别 + 关键词/敏感句分析，实时看见风险 |
| ② 冲突升级 | 缓和矛盾力不足 | 实时音频 + 振动提醒，及时干预、降温 |
| ③ 事后自责 | 修复关系无方法 | AI 分析录音、生成总结与建议，一起复盘 |

从**情绪黑洞**到**理性对待** —— 不是事后追悔，而是在伤害成型前接住。

---

## 我们信什么

| 人先于系统 | 赋能，不裁判 | 数据不出家门，推理在边缘跑 |
| :--------- | :----------- | :--------------------------- |

更完整的信念、产品定义与研究背景 → [ORG_PRINCIPLES.md](../ORG_PRINCIPLES.md) · 叙事与视觉 → [manifesto.md](../manifesto.md) · 品牌素材索引 → [assert-README.md](../assert-README.md)

---

## 链接

| 官网与产品 | 主仓库 | 一起搞事情 |
| :--------- | :----- | :--------- |
| [**语镜 — Dialog Safety Infra**](https://infotech-launch.vercel.app/) | [**Dialog**](https://github.com/Info-Tech-org/Dialog) — ASR → 语义管线 → 实时提醒 & 复盘 | [加入等待列表](https://infotech-launch.vercel.app/) · [贡献指南](../CONTRIBUTING.md) |

---

## 技术栈与研究

`Python` `FastAPI` `React` `WebSocket` `Tencent ASR` `Edge Inference` `ESP32`  
**管线**：关键词 → 语义向量（含 Emotion2Vec 等）→ LLM 筛一层，&lt;200ms 触达。  
我们在 RAVDESS、IEMOCAP 等数据上验证 BiLSTM / BaseModel / Transformer；小模型边缘部署、大模型提准确率，开源可插拔、可接你的设备。

---

*愿孩子的记忆里，少一道不该有的疤。*

</div>
