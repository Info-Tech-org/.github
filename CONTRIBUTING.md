# 贡献指南（组织默认）

谢谢你对 **Info-Tech-org（1NF0TECH）** 有兴趣。  
无论是修一个 typo、报一个 Bug，还是提一版实现思路，我们都欢迎。

---

## 组织与仓库

- **主仓库**：[Dialog](https://github.com/Info-Tech-org/Dialog) — 家庭对话语义安全（后端、前端、设备端、扩展）
- **官网**：[语镜 — Dialog Safety Infra](https://infotech-launch.vercel.app/)
- **我们信什么**：[ORG_PRINCIPLES.md](ORG_PRINCIPLES.md)

建议先在**具体仓库**里动手；各仓的 README 和（若有）仓库内 CONTRIBUTING 会写得更细。下面是组织级的共通约定。

---

## 怎么贡献

### 报 Bug

1. 到对应仓库的 [Issues](https://github.com/Info-Tech-org/Dialog/issues) 看看有没有人报过。
2. 没有的话，开一个：说清楚**现象、复现步骤、你期望 vs 实际**，能贴环境信息和日志更好。

### 提想法 / 新功能

1. 在对应仓库开 Issue，打上 `enhancement` 之类标签。
2. 写清楚**场景和为什么需要**；有实现思路或接口设想也欢迎一起写。

### 提代码（PR）

1. Fork 目标仓库，开一条分支（如 `feature/xxx`、`fix/xxx`）。
2. 跟仓库现有风格和测试方式保持一致，该改的文档一起改。
3. 提交信息用 [Conventional Commits](https://www.conventionalcommits.org/)：`feat:`、`fix:`、`docs:` 等。
4. 推上去开 PR，说清改了什么、为什么，能关联 Issue 最好。

---

## 约定

- **代码**：Python 跟 PEP 8；JS/TS 跟各仓既有风格。我们偏好可读、可维护。
- **安全**：别把真密钥、敏感配置交上来；安全问题走 [SECURITY.md](SECURITY.md)，私下说。
- **相处**：遵守 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)，对事不对人，建设性讨论。

---

## 卡住了？

- 各仓 README 和 `docs/` 里有结构和快速开始。
- 组织在做什么、信什么，见 [ORG_PRINCIPLES.md](ORG_PRINCIPLES.md)。

再次感谢。你的每一笔贡献，都是在帮「少一句后悔」多一点点可能。
