# Tokenomics 代币经济

> 这是加密用户最关心的章节。先看核心数据，再看分配，最后看争议点。

---

## 核心参数

| 项目 | 数值 |
|------|------|
| **代币符号** | BAI |
| **总供应** | 300,000,000（3 亿）|
| **主链** | Solana（SPL Token）|
| **结算/锚定链** | Ethereum |
| **代币性质** | Utility Token（生态访问 + 治理）|
| **是否有派息** | ❌ 无 |
| **是否有回购销毁** | ⚠️ 有机制，但需治理批准 |

---

## 代币分配

```
                    BAI 代币分配（300,000,000）

   45% Treasury Reserve  ████████████████████ 135,000,000
   30% Market Circulation █████████████      90,000,000
    8% Marketing           ████              24,000,000
    7% Team & Advisors      ███              21,000,000
    5% Liquidity Pool        ██              15,000,000
    5% Ecosystem Incentives   ██             15,000,000
```

| 类别 | 比例 | 数量 | 说明与解锁规则 |
|------|------|------|----------------|
| **Treasury Reserve（金库储备）** | 45% | 135M | 由基金会联合管理，用于长期运营、新资产扩张、AI 基础设施合作 |
| **Market Circulation（市场流通）** | 30% | 90M | 合规分配 + 全球社区平台访问，**具体释放计划待披露** |
| **Marketing Operations（市场运营）** | 8% | 24M | 品牌、产业合作、学术活动、社区。季度预算审批与披露 |
| **Team & Advisors（团队与顾问）** | 7% | 21M | **12 个月 Cliff + 24 个月线性释放** |
| **Liquidity Pool（流动性池）** | 5% | 15M | Raydium / Jupiter 等 DEX 流动性 |
| **Ecosystem Incentives（生态激励）** | 5% | 15M | 社区贡献者、开发者、生态任务参与 |

---

## ⚠️ 加密用户必须知道的几个争议点

### 1. Treasury 占比过高（45%）

- 业内常见 Treasury 占比 20-35%，**45% 显著高于行业中位数**
- 需要披露：
  - Treasury 多签地址（公开链上可查）
  - 多签签名人构成（几个？背景？）
  - 提款 / 动用规则（是否有时间锁？是否需要治理通过？）

### 2. Team & Advisors 占比过低（7%）

- 通常项目方为团队预留 15-20%
- 7% 可能意味着：(a) 团队主要权益在股权层面 (b) 实际有未公开的"项目方钱包"在 Treasury 内
- **建议项目方明确说明**

### 3. Market Circulation 30% 缺乏细节

白皮书原文：*"Compliance distribution and platform usage access for global communities will follow specific implementation timelines determined by legal opinions, whitelist mechanisms, and market conditions."*

翻译过来：还没决定怎么发。

加密用户应该追问：

- 是否有 Token Sale？价格？
- 是否做地理围栏（Reg S 禁止美国买）？
- IDO / IEO / 私募阶段如何划分？
- 早期参与者的解锁曲线？

### 4. 流动性池仅 5%

- 5% 的初始 LP 在多链架构（Solana + Ethereum）下可能偏紧
- 历史上 RWA 类项目 LP 不足容易引起开盘剧烈波动

### 5. Reg D + Reg S + Utility Token 三件套的法律张力

白皮书一边说"按照 Reg D 和 Reg S 豁免发行"（这是**证券发行**的豁免条款），一边说代币是"utility token 不构成证券"。

**这是矛盾的**：

- 如果是 utility token，不需要走 Reg D / Reg S
- 如果走 Reg D / Reg S，就是承认是 security token

在 SEC 2026 年 1 月新指引下，**有 Buyback、价值捕获、治理权的代币几乎一定被认为是证券**。

> 项目方需要选边站。否则在美国监管路径上两边都走不通。

---

## 价值传导路径

BAI 不是收益型代币，价值传导不是"分红"，而是：

```
1. 项目运营 → 收入 → Treasury 储备增加
                         ↓
2. （治理批准）→ 二级市场回购 → 销毁或入库
                         ↓
3. 生态扩张 → BAI 使用场景增多 → 持有/锁定需求增加
                         ↓
4. 流通量减少 + 需求增加 → 长期效用价值
```

**关键假设**：
- 步骤 2 的回购实际发生（治理通过）
- 步骤 3 的"使用场景增多"真的能产生硬需求（不是软性的"会员权益"）

加密用户应该跟踪的硬指标（待项目方上线 KPI Dashboard 后可查）：

- Treasury 余额（链上可查）
- 累计回购销毁数量
- 主动持仓地址数与分布基尼系数
- DAO 治理提案参与率

---

## 与同类 RWA 项目的对照

| 项目 | 总供应 | Treasury 比例 | 主要价值捕获 |
|------|--------|---------------|-------------|
| BAI | 3 亿 | 45% | 间接通过回购 |
| **同业项目 A** | 待补 | 待补 | 待补 |
| **同业项目 B** | 待补 | 待补 | 待补 |

> 此对照表将在后续版本补充，建议项目方主动披露。

---

## 待披露 / TBD

- [ ] Token Sale 详细条款（价格、阶段、地理围栏）
- [ ] Treasury 多签地址与签名人
- [ ] 流通量解锁时间表（除 Team 外其他类别）
- [ ] 智能合约地址与审计报告
- [ ] 初始市值（MC）与全稀释市值（FDV）
