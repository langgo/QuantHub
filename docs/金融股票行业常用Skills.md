# 金融、股票等行业常用 Skills 调研

> 来源：`npx skills find finance / stock / trading / investment / portfolio / quant / fund / yahoo finance / akshare / crypto`。  
> 排序：按 skills.sh 展示的 installs 数量倒序。  
> 说明：这里的 installs 是技能生态展示的安装量，不等于质量保证；涉及交易和投资的技能只适合做研究辅助，不应直接作为投资建议。

## 通用安装与使用

### 安装到全局

```bash
npx skills add <owner/repo@skill> -g -y
```

例如：

```bash
npx skills add sugarforever/01coder-agent-skills@china-stock-analysis -g -y
```

### 安装到当前项目

```bash
npx skills add <owner/repo@skill> -y
```

### 使用方式

安装后，在对话里直接点名或描述任务即可，例如：

```text
请用 china-stock-analysis 分析 600519 贵州茅台，输出标准版估值和风险。
```

```text
请用 akshare-stock 查询 A 股市场、行业板块和资金流情况。
```

```text
请用 trading-signal 辅助分析 BTCUSDT 当前行情，只输出风险提示和观察点。
```

---

## 按安装量倒序列表

| 排名 | Skill | 安装量 | Skill 介绍 | 适合场景 | 怎么用 | 原始链接 |
|---:|---|---:|---|---|---|---|
| 1 | `china-stock-analysis` | 12.6K | 面向中国 A 股的价值投资分析技能，强调“基本面 + 估值 + 风险”三件事。它把选股、财务质量、同行比较、DCF/DDM/相对估值、异常财务信号放在同一套流程里，适合做个股初筛和深度研究框架。 | A 股基本面研究、价值投资分析、财务异常排查。 | “分析 600519，深度 standard，给出财务质量、估值、安全边际和风险。” | https://skills.sh/sugarforever/01coder-agent-skills/china-stock-analysis |
| 2 | `stock-analysis` | 11.4K | 股票分析类通用技能，适合围绕单只股票生成概览式研究，包括行情、公司信息、基本面、技术面和风险提示。安装量高，但 GitHub stars 不高，适合辅助整理，不适合直接给交易结论。 | 个股快速分析、美股/A 股概览、技术面辅助。 | “分析 AAPL / TSLA / 600519 的基本面和技术面。” | https://skills.sh/gracefullight/stock-checker/stock-analysis |
| 3 | `akshare-stock` | 10.9K | 基于 AkShare 的 A 股数据技能，覆盖市场指数、K 线、涨跌停、资金流、基本面、龙虎榜、板块轮动、基金和跨境市场。更像“数据查询 + 市场快照”工具。 | A 股行情、板块、资金流、市场日报。 | “用 akshare-stock 看今天 A 股主要指数、北向资金、热门板块。” | https://skills.sh/molezzz/openclaw-stock-skill/akshare-stock |
| 4 | `gmgn-portfolio` | 9.9K | 面向 GMGN/链上场景的加密资产组合技能，重点是钱包或链上投资组合的资产分布、持仓变化和风险集中度。 | Web3 钱包组合、链上资产追踪。 | “查看某钱包组合、主要持仓和风险集中度。” | https://skills.sh/gmgnai/gmgn-skills/gmgn-portfolio |
| 5 | `okx-wallet-portfolio` | 9.2K | OKX 钱包组合技能，偏链上钱包资产视角，可用于查看多币种资产、DeFi 持仓和风险暴露。适合已经使用 OKX Wallet 的用户。 | OKX Wallet 持仓、链上资产、DeFi 概览。 | “分析我的 OKX Wallet 组合，列出资产分布和风险点。” | https://skills.sh/okx/onchainos-skills/okx-wallet-portfolio |
| 6 | `emblem-portfolio-tracker` | 8.9K | 投资组合追踪技能，重点不是研究单个资产，而是跟踪一组资产的表现、收益贡献、回撤和集中度。 | 组合监控、收益归因、风险集中度。 | “跟踪我的投资组合表现，列出收益、回撤和集中度。” | https://skills.sh/emblemcompany/agent-skills/emblem-portfolio-tracker |
| 7 | `okx-cex-portfolio` | 8.9K | OKX 中心化交易所账户组合技能，适合查看交易所账户内现货、合约或其他资产的整体分布和风险敞口。 | OKX 交易所账户资产、持仓风险。 | “查看 OKX CEX 账户资产分布和主要风险敞口。” | https://skills.sh/okx/agent-skills/okx-cex-portfolio |
| 8 | `trading-signal` | 8.3K | Binance 官方技能集合中的交易信号技能，偏加密市场短周期行情分析。适合整理趋势、支撑阻力和风险点，不应直接替代交易系统。 | 加密货币行情、交易信号、风险提示。 | “分析 BTCUSDT 当前交易信号，给出支撑、阻力、风险。” | https://skills.sh/binance/binance-skills-hub/trading-signal |
| 9 | `crypto-market-rank` | 7.6K | Binance 官方加密市场排名技能，偏市场概览：市值、成交量、涨跌幅、热门币种排序。适合做加密市场盘前/盘后扫描。 | 加密市场排名、市值榜、异动币种。 | “列出当前加密货币市值、涨跌幅和成交量排名。” | https://skills.sh/binance/binance-skills-hub/crypto-market-rank |
| 10 | `okx-defi-portfolio` | 6.6K | OKX DeFi 组合技能，聚焦 DeFi 协议中的资产、收益和风险暴露，例如质押、借贷、LP、收益聚合等。 | DeFi 组合、协议分布、收益和风险。 | “分析我的 DeFi 组合，列出协议分布、收益和潜在风险。” | https://skills.sh/okx/onchainos-skills/okx-defi-portfolio |
| 11 | `finance-billing-ops` | 6.4K | 财务/账单运营技能，偏企业经营后台，不是证券投资技能。适合处理账单、收入、付款、对账、运营指标等财务流程问题。 | 财务运营、账单异常、收入流程。 | “梳理账单异常、收入确认或财务运营流程。” | https://skills.sh/affaan-m/ecc/finance-billing-ops |
| 12 | `llm-trading-agent-security` | 6.3K | 交易 Agent 安全技能，关注自动化交易系统里的提示注入、权限越界、资金安全、错误下单和风控缺口。适合先做安全审查再接交易 API。 | 交易机器人安全、自动化交易风控。 | “审查我的交易 agent 设计，找出越权、提示注入和资金风险。” | https://skills.sh/affaan-m/ecc/llm-trading-agent-security |
| 13 | `finance-expert` | 6.2K | 通用金融专家类 persona，适合解释宏观、股票、债券、财务和投资概念。它更像专业问答助手，不是特定数据源工具。 | 金融概念解释、市场讨论、财务分析框架。 | “用 finance-expert 解释美联储降息如何影响股票和债券。” | https://skills.sh/personamanagmentlayer/pcl/finance-expert |
| 14 | `stock-analysis` | 6K | 办公技能集合里的股票分析模板，偏报告写作和结构化表达。适合把已有资料整理成股票分析报告、投资摘要或会议材料。 | 股票研究报告、结构化文档、投研材料。 | “生成一份某公司的股票分析报告，包含业务、财务、估值、风险。” | https://skills.sh/claude-office-skills/skills/stock-analysis |
| 15 | `tushare-finance` | 5.1K | 基于 Tushare 的中国金融数据技能，适合查询 A 股行情、指数、财务指标和市场数据。更偏数据入口，需要注意 Tushare token 和接口权限。 | A 股数据、指数、财务指标、历史行情。 | “用 tushare-finance 查询 000001.SZ 最近一年行情和财务指标。” | https://skills.sh/stanleychanh/tushare-finance-skill-for-claude-code/tushare-finance |
| 16 | `yahoo-finance` | 4.5K | Yahoo Finance 数据技能，适合查询美股、ETF、指数、外汇和部分全球资产的公开市场数据。适合做全球市场快速数据抓取。 | 美股、ETF、指数、全球资产数据。 | “查询 AAPL、MSFT、SPY 的行情、估值和历史表现。” | https://skills.sh/gracefullight/stock-checker/yahoo-finance |
| 17 | `investment-memo` | 4.4K | 投资备忘录写作技能，核心价值是把研究结论组织成 memo：投资逻辑、关键假设、估值、风险、反方观点和跟踪指标。 | 投资 memo、投委会材料、研究结论整理。 | “基于以下材料生成投资 memo：投资逻辑、估值、风险、反方观点。” | https://skills.sh/claude-office-skills/skills/investment-memo |
| 18 | `backtesting-trading-strategies` | 4.2K | 交易策略回测技能，适合把交易规则变成可验证的历史测试流程，关注收益、最大回撤、胜率、换手、交易成本等指标。 | 量化回测、策略验证、交易规则评估。 | “回测均线交叉策略，输出收益、最大回撤、胜率和风险。” | https://skills.sh/jeremylongshore/claude-code-plugins-plus-skills/backtesting-trading-strategies |
| 19 | `korean-stock-search` | 4.1K | 韩国股票搜索技能，适合查询韩股公司、行情和相关信息。适合覆盖三星电子、SK 海力士等韩国市场标的。 | 韩国股票查询、韩股公司信息。 | “查询三星电子的股价、基本面和相关新闻。” | https://skills.sh/nomadamas/k-skill/korean-stock-search |
| 20 | `stock-market-pro` | 4.1K | 股票市场增强分析技能，偏市场日报和综合研究，适合同时看指数、板块、热门个股和新闻事件。 | 市场日报、指数板块、热门股票扫描。 | “做一个美股市场日报，包含指数、板块、热门个股。” | https://skills.sh/sundial-org/awesome-openclaw-skills/stock-market-pro |
| 21 | `crypto-report` | 3.8K | 加密市场报告技能，适合把 BTC、ETH、主流板块、链上或宏观事件整理成日报/周报。 | 加密市场报告、币种研究、行业概览。 | “生成今日加密市场报告，包含 BTC、ETH、板块和风险。” | https://skills.sh/claude-office-skills/skills/crypto-report |
| 22 | `longbridge-quant` | 3.2K | Longbridge 量化技能，偏量化研究和策略分析。适合有行情数据、因子或交易规则时做研究辅助。 | 量化研究、因子分析、策略验证。 | “用 longbridge-quant 分析某策略的因子表现。” | https://skills.sh/longbridge/skills/longbridge-quant |
| 23 | `trading-analysis` | 3K | 交易分析技能，偏短周期行情判断，常用于趋势、关键价位、支撑阻力、止损思路和风险提示。 | 交易计划、趋势分析、关键价位。 | “分析 ETH 当前趋势，给出关键价位和风险。” | https://skills.sh/gracefullight/stock-checker/trading-analysis |
| 24 | `longbridge-portfolio` | 3K | Longbridge 组合技能，适合查看和分析投资组合，包括行业分布、个股集中度、收益贡献和风险暴露。 | 组合分析、持仓结构、收益贡献。 | “分析我的组合行业分布、收益贡献和集中度。” | https://skills.sh/longbridge/skills/longbridge-portfolio |
| 25 | `finance-news` | 2.8K | 财经新闻技能，适合检索、总结和跟踪市场新闻。适合作为市场日报输入，但需要再结合数据验证新闻影响。 | 财经新闻、市场事件、日报素材。 | “总结今天影响美股和 A 股的主要财经新闻。” | https://skills.sh/sundial-org/awesome-openclaw-skills/finance-news |
| 26 | `longbridge-fundamentals` | 2.6K | Longbridge 基本面技能，偏公司财务、估值、盈利质量和同行对比。适合和组合或投资 memo 技能配合使用。 | 股票基本面、财务分析、估值对比。 | “分析某公司的收入、利润、估值和同行对比。” | https://skills.sh/longbridge/skills/longbridge-fundamentals |
| 27 | `yfinance-data` | 2.4K | 基于 yfinance 的数据技能，适合下载股票、ETF、指数的历史价格，再计算收益、波动、回撤和相关性。 | 历史行情、ETF/指数数据、收益风险计算。 | “获取 SPY、QQQ 最近 5 年价格并计算年化收益和回撤。” | https://skills.sh/himself65/finance-skills/yfinance-data |
| 28 | `quantitative-research` | 2.4K | 量化研究技能，适合因子研究、策略假设、回测设计和数据分析。重点是研究流程，不是直接给买卖点。 | 因子研究、策略设计、量化分析。 | “研究动量因子在标普 500 成分股上的历史表现。” | https://skills.sh/omer-metin/skills-for-antigravity/quantitative-research |
| 29 | `financekit` | 2.3K | Swift/iOS FinanceKit 相关技能，偏金融类 App 开发，而不是投研。适合做个人财务、账户聚合、资产管理等 Apple 生态功能设计。 | iOS 金融应用、个人财务 App、FinanceKit 开发。 | “帮我用 FinanceKit 设计一个记账/资产管理 iOS 功能。” | https://skills.sh/dpearson2699/swift-ios-skills/financekit |
| 30 | `finance-manager` | 2.3K | 财务管理技能，偏个人或小团队预算、收支、报表和现金流规划。更接近财务管家，而不是资本市场分析。 | 预算管理、收支整理、现金流规划。 | “帮我整理月度收支并生成预算建议。” | https://skills.sh/ailabs-393/ai-labs-claude-skills/finance-manager |
| 31 | `finance-skills` | 2.3K | 通用金融技能包，适合金融基础概念、财务分析、投资研究框架等泛金融任务。适合不知道该用哪个细分技能时先试。 | 金融知识问答、财务分析、投资框架。 | “解释久期、凸性和利率变化对债券价格的影响。” | https://skills.sh/alirezarezvani/claude-skills/finance-skills |
| 32 | `derivatives-trading-usds-futures` | 2.3K | Binance USDⓈ-M 合约技能，面向 USDT/USDC 本位永续或交割合约场景，关注保证金、仓位、强平和合约规则。 | 币本位/USDT 本位合约、保证金、强平风险。 | “解释 BTCUSDT 永续合约仓位风险和保证金要求。” | https://skills.sh/binance/binance-skills-hub/derivatives-trading-usds-futures |
| 33 | `stock-correlation` | 2.1K | 股票相关性分析技能，适合判断多只股票是不是同涨同跌，以及组合是否真正分散。 | 组合分散、相关性矩阵、风险暴露。 | “计算 AAPL、MSFT、NVDA、SPY 的相关性并解释组合风险。” | https://skills.sh/himself65/finance-skills/stock-correlation |
| 34 | `margin-trading` | 1.9K | Binance 杠杆交易技能，关注借贷、保证金、利息、维持保证金和强平机制。适合先理解规则再交易。 | 现货杠杆、保证金、借贷和强平。 | “说明现货杠杆交易的风险和保证金要求。” | https://skills.sh/binance/binance-skills-hub/margin-trading |
| 35 | `finance-based-pricing-advisor` | 1.9K | 财务视角产品定价技能，偏企业经营：基于成本、毛利率、目标利润、回本周期和单位经济模型设计价格。 | 产品定价、毛利测算、商业化策略。 | “基于成本、毛利率和目标利润设计 SaaS 定价。” | https://skills.sh/deanpeters/product-manager-skills/finance-based-pricing-advisor |
| 36 | `finance-metrics-quickref` | 1.8K | 财务指标速查技能，适合解释经营指标和财务指标，例如 ARR、MRR、毛利率、CAC、LTV、NRR 等。 | 经营指标速查、SaaS 财务指标、指标口径。 | “解释 LTV/CAC、毛利率、净收入留存的含义和计算方式。” | https://skills.sh/deanpeters/product-manager-skills/finance-metrics-quickref |
| 37 | `stock-liquidity` | 1.8K | 股票流动性分析技能，关注成交量、买卖价差、冲击成本和大额交易可行性。适合机构或较大资金量建仓前检查。 | 成交量、流动性风险、冲击成本。 | “评估某股票是否适合大额建仓，关注成交量和流动性风险。” | https://skills.sh/himself65/finance-skills/stock-liquidity |
| 38 | `stock-research-executor` | 1.8K | 股票深度研究执行技能，强调按研究步骤推进：收集资料、拆业务、看财务、看行业、做估值、列风险。 | 深度研究、投研流程、个股报告。 | “对某公司做深度研究，包含业务、财务、行业、估值、风险。” | https://skills.sh/liangdabiao/claude-code-stock-deep-research-agent/stock-research-executor |
| 39 | `fixed-income-portfolio` | 1.6K | 固收组合技能，适合分析债券组合的久期、收益率、信用风险、利率敏感性和情景损失。 | 债券组合、久期、信用风险、利率冲击。 | “分析债券组合久期、信用风险和利率上行情景损失。” | https://skills.sh/anthropics/financial-services/fixed-income-portfolio |
| 40 | `finance-sentiment` | 1.4K | 金融情绪分析技能，适合从新闻、公告、社媒或研报文本中提取正负面情绪、主题和风险事件。 | 新闻情绪、公告解读、市场舆情。 | “分析今天关于 NVDA 的新闻情绪和主要风险点。” | https://skills.sh/himself65/finance-skills/finance-sentiment |
| 41 | `tradingview-quantitative` | 1.4K | TradingView/量化技能，适合理解指标逻辑、把图表信号转成交易规则，或辅助 Pine Script/策略分析。 | TradingView 指标、量化规则、图表信号。 | “把这个 TradingView 指标逻辑解释成交易规则。” | https://skills.sh/hypier/tradingview-quantitative-skills/tradingview-quantitative |
| 42 | `stock-daily-analysis` | 1.4K | 股票每日分析技能，偏盘后/盘前日报：指数、板块、涨跌停、资金流、热点题材和风险提示。 | 市场日报、A 股日评、热点复盘。 | “生成今天 A 股市场日报，包含指数、板块、涨跌停、资金流。” | https://skills.sh/chjm-ai/stock-daily-analysis-skill/stock-daily-analysis |
| 43 | `stock-monitor` | 1.4K | 股票监控技能，适合长期跟踪自选股的价格异动、新闻公告和风险事件。更适合提醒和监控，不是深度研究。 | 自选股监控、异动提醒、公告跟踪。 | “监控我的自选股，提示异动、公告和风险事件。” | https://skills.sh/chjm-ai/stock-monitor-skill/stock-monitor |
| 44 | `alphaear-stock` | 1.2K | 股票分析/市场研究类技能，偏个股初筛和辅助研究。安装量中等，适合与更可靠数据源交叉验证。 | 个股初筛、市场研究、投资辅助。 | “对某只股票做基本面和估值初筛。” | https://skills.sh/rkiding/awesome-finance-skills/alphaear-stock |
| 45 | `stock-watcher` | 1K | 股票观察技能，适合跟踪一组股票的价格变化、新闻和基础风险信号。适合自选股列表，而非复杂投研。 | 自选股观察、行情跟踪、新闻摘要。 | “关注这些股票，汇总价格变化和重要新闻。” | https://skills.sh/agentbay-ai/agentbay-skills/stock-watcher |

---

## 选择建议

| 场景 | 优先考虑 |
|---|---|
| A 股基本面/估值 | `china-stock-analysis`、`tushare-finance`、`akshare-stock` |
| A 股行情/资金流/板块 | `akshare-stock`、`stock-daily-analysis`、`stock-monitor` |
| 美股/全球市场数据 | `yahoo-finance`、`yfinance-data`、`stock-analysis` |
| 投资报告/Memo | `investment-memo`、`stock-research-executor`、`stock-analysis` |
| 量化/回测 | `backtesting-trading-strategies`、`quantitative-research`、`longbridge-quant` |
| 组合分析 | `stock-correlation`、`stock-liquidity`、`fixed-income-portfolio`、`longbridge-portfolio` |
| 加密资产 | `trading-signal`、`crypto-market-rank`、`okx-wallet-portfolio`、`okx-defi-portfolio` |
| 财务运营/经营指标 | `finance-billing-ops`、`finance-manager`、`finance-metrics-quickref` |

## 注意事项

1. **不要把任何 skill 的输出直接当作投资建议。** 它们适合做数据整理、研究框架、初筛和报告生成。
2. **交易类 skill 风险更高。** 尤其涉及合约、杠杆、保证金、自动化交易时，要先验证数据源、权限边界和风控逻辑。
3. **优先选择安装量高、来源可信、维护活跃的 skill。** 低安装量 skill 可以试用，但不建议直接用于重要决策。
4. **数据源限制要单独确认。** AkShare、Tushare、Yahoo Finance、交易所 API 的字段、频率、权限和稳定性不同。
