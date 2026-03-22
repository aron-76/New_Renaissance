# New Renaissance

AI Native Quant 探索项目。

## 宗旨

探索 AI（尤其是大语言模型）在量化投资中的应用可能性。

不限定具体方向，不预设技术路线。所有与 AI Native Quant 相关的研究和实验都欢迎，希望活跃参与者们逐渐收敛方向，一起创立New Renaissance😎

## 如何参与

### 第一步：Fork 本仓库

点击右上角 `Fork` 按钮，将本仓库复制到你自己的 GitHub 账号下。

### 第二步：在你的 Fork 中研究

```bash
git clone https://github.com/<你的用户名>/New_Renaissance.git
cd New_Renaissance

# 在 research/ 下建立你的研究目录
mkdir -p research/<你的用户名>
# 在里面自由探索
```

### 第三步：提交贡献

当你有了值得分享的成果，向本仓库提 Pull Request：

```bash
# 保持与上游同步
git remote add upstream https://github.com/<主仓库地址>/New_Renaissance.git
git fetch upstream
git merge upstream/main

# 提交你的工作，推送到你的 Fork
git push origin main

# 在 GitHub 上发起 Pull Request
```

### 贡献规则

- `research/<你的用户名>/` — 你的自由研究空间，直接通过 PR 合入
- `docs/` — 公共文档，PR 需要讨论后合入
- 根目录 — 项目结构变更，PR 需要讨论后合入
- 有想法随时在 Issues 或者群里讨论

## 项目结构

```
New_Renaissance/
├── docs/                       # 公共文档
├── research/                   # 参与者各自的研究空间
└── refs/                       # 参考资料
    ├── papers/                 # 参考论文
    ├── TwinMarket/             # 多 Agent 涌现行为研究
    ├── MiroFish/               # LLM 群策系统
    ├── QuantaAlpha/            # LLM + 进化策略因子挖掘
    ├── vnpy/                   # 框架
    └── backtrader/             # 框架
```

## License

AGPL-3.0
