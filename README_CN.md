# CleanStmt — AI 驱动的财务文档转换工具

> **秒级将银行对账单、发票、收据转换为干净的 Excel、CSV 和会计软件格式**

[![官网](https://img.shields.io/badge/官网-cleanstmt.com-blue)](https://www.cleanstmt.com)
[![免费版本](https://img.shields.io/badge/定价-免费版可用-green)](https://www.cleanstmt.com)
[![AI 驱动](https://img.shields.io/badge/AI-Claude%20Vision-purple)](https://www.cleanstmt.com)

---

## 🎯 CleanStmt 是什么?

CleanStmt 是一款 **AI 驱动的财务文档转换工具**，专为会计师、记账员、财务团队和小企业主打造，帮助他们摆脱从 PDF 对账单手动重新输入交易数据的困境。

与通用 PDF 转换器产生的乱七八糟的电子表格（合并单元格、列错位）不同，CleanStmt 使用 **Claude AI Vision OCR** 理解财务文档的结构，**逐位数字**提取交易数据，绝不猜测。

🌐 **立即试用：** [www.cleanstmt.com](https://www.cleanstmt.com)

---

## 🚀 核心功能

### ✨ AI 智能 OCR
- **逐位数字提取** — 准确读取交易表格，不猜测不确定的值
- 处理多行描述、换行文本和复杂的对账单布局
- 支持 **原生 PDF** 和 **扫描图片**

### 📊 干净的结构化输出
- **无合并单元格** — 每笔交易保持单行
- 日期格式为 Excel 日期（而非文本字符串）
- 金额为数字（而非带货币符号的文本）
- 立即可用于 **数据透视表、VLOOKUP 和对账**

### 🏦 广泛的银行支持
- 已优化支持 **38+ 主流银行**，包括：
  - Chase、美国银行、富国银行、花旗、Capital One
  - US Bank、PNC、TD Bank、Truist、BMO Harris
  - HSBC、巴克莱、高盛 Marcus、Discover、美国运通

### 💾 多种导出格式
一次上传，导出为：
- **Excel** (.xlsx)
- **CSV** (.csv)
- **QuickBooks** (.qbo, .iif)
- **Quicken** (.qif)
- **OFX** (.ofx)
- **Xero CSV**、**Sage CSV**、**Tally ERP**

### ⚡ 快速且隐私保护
- 拖放上传，**30 秒内获得结果**
- 批量处理多个对账单
- 内存处理，**1 小时后自动删除** — 不长期保留数据

---

## 🆓 定价

### 免费版
- ✅ **无需信用卡**
- ✅ 有使用限制
- ✅ 包含所有核心功能
- ✅ 适合偶尔使用

### Pro 订阅 ($19/月)
- ✅ **每月 500 次转换**（每月重置，不累计）
- ✅ 优先处理
- ✅ 高级导出格式（Xero、Sage、QBO）
- ✅ 批量处理
- ✅ API 访问 *（即将推出）*

👉 **免费开始：** [cleanstmt.com](https://www.cleanstmt.com)

---

## 🎬 工作原理

1. **上传** — 拖放你的银行对账单 PDF 或图片
2. **提取** — AI 读取并结构化你的交易数据
3. **导出** — 下载干净的 Excel、CSV 或会计格式文件
4. **导入** — 可直接用于 QuickBooks、Xero 或任何电子表格工具

---

## 🧑‍💼 谁在使用 CleanStmt？

### 会计师 & 记账员
- 对账客户银行账户
- 将历史交易导入 QuickBooks 或 Xero
- 高效转换来自多家银行的对账单

### 小企业主
- 从 PDF 对账单分析现金流
- 准备税务记录
- 跨多个账户跟踪费用

### 财务团队
- 处理费用报告和供应商发票
- 整合多银行交易数据
- 自动化财务报告工作流

### 税务专业人士
- 为客户整理年度财务记录
- 批量转换多年的 PDF 对账单
- 准备符合审计要求的交易日志

---

## 🔥 为什么选择 CleanStmt？

| 功能 | 通用 PDF 转换器 | CleanStmt |
|---------|----------------------|-----------|
| **合并单元格** | ❌ 破坏公式 | ✅ 单行交易 |
| **AI OCR 精度** | ❌ 猜测数值 | ✅ 逐位数字提取 |
| **多格式导出** | ❌ 仅 Excel | ✅ Excel、CSV、QBO、QIF、OFX、IIF |
| **银行优化** | ❌ 通用解析 | ✅ 38+ 银行优化 |
| **会计集成** | ❌ 需手动重新格式化 | ✅ QuickBooks 即用输出 |
| **数据隐私** | ⚠️ 无限期存储 | ✅ 1 小时后自动删除 |

---

## 🛠️ 技术栈

- **前端：** Next.js 14、React、TailwindCSS
- **AI 引擎：** Claude Vision API (Anthropic)
- **导出库：** `xlsx-js-style`、`docx`、自定义序列化器
- **托管：** Vercel（边缘函数）
- **数据库：** Supabase（用户管理、订阅跟踪）

---

## 📖 使用场景

### 1. 银行对账单转换
上传 Chase、富国银行或美国银行 PDF → 获得包含日期、描述、金额列的干净 Excel。

### 2. 信用卡对账单处理
转换美国运通、花旗或 Capital One 对账单 → 导出为 QuickBooks 或 Xero CSV。

### 3. 发票 & 收据提取
从供应商发票中提取明细项 → 用于费用跟踪的结构化数据。

### 4. 多银行对账
处理来自 5+ 家银行的对账单 → 统一 CSV 用于现金流分析。

### 5. 税务准备
转换多年的 PDF 对账单 → 几分钟内生成符合审计要求的交易日志。

---

## 🌐 支持的格式

### 输入格式
- PDF（原生和扫描）
- PNG、JPG、JPEG（图片）
- 多页文档

### 输出格式
- **Excel** (.xlsx) — 带标题格式化，无合并单元格
- **CSV** — UTF-8 编码，标准分隔符
- **QuickBooks** (.qbo, .iif) — 可直接导入
- **Quicken** (.qif) — OFX 兼容
- **Xero CSV** — 匹配 Xero 交易导入格式
- **Sage 50 UK CSV** — 银行对账格式
- **Tally ERP** — 会计分类账格式

---

## 🔒 隐私 & 安全

- ✅ **不长期存储数据** — 文件 1 小时后自动删除
- ✅ **内存处理** — 数据不写入持久存储
- ✅ **HTTPS 加密** — 所有上传在传输中加密
- ✅ **不与第三方共享** — 你的文档绝不出售或共享
- ✅ **符合财务数据法规**

---

## 🚧 路线图

- [ ] 开发者 API 访问
- [ ] 批量处理仪表板
- [ ] 自定义导出模板
- [ ] 集成 Zapier & Make
- [ ] 移动应用（iOS & Android）
- [ ] 多语言支持

---

## 🙋 常见问题

### CleanStmt 是免费的吗？
是的，我们提供 **有使用限制的免费版本**。无需信用卡即可开始。升级到 Pro（$19/月）可无限次转换。

### 你们支持哪些银行？
我们支持 38+ 主流银行，包括 Chase、美国银行、富国银行、花旗、Capital One、US Bank、PNC、TD Bank、Truist 等。完整列表见 [cleanstmt.com/banks](https://www.cleanstmt.com)。

### 可以转换扫描的对账单吗？
可以！我们的 AI OCR 支持原生 PDF 和扫描图片。

### 你们会存储我的数据吗？
不会。文件在内存中处理，**1 小时后自动删除**。我们不保留你的财务文档。

### 可以将结果导入 QuickBooks 吗？
可以！直接导出为 **QBO** 或 **IIF** 格式，无缝导入 QuickBooks。

### 提取的准确度如何？
我们的 AI **逐位数字**读取交易数据，不猜测不确定的值。为获得最佳效果，请使用清晰的高分辨率 PDF。

---

## 📧 联系 & 支持

- **官网：** [cleanstmt.com](https://www.cleanstmt.com)
- **邮箱：** support@cleanstmt.com
- **GitHub：** [github.com/dis625406542/cleanstmt_pro](https://github.com/dis625406542/cleanstmt_pro)

---

## 📜 许可证

本项目为专有软件。此仓库中的代码仅用于演示和文档目的。

---

## 🌟 给这个仓库点个 Star

如果你觉得 CleanStmt 有用，请 **给这个仓库点 Star** 帮助更多人发现它！

[![GitHub stars](https://img.shields.io/github/stars/dis625406542/cleanstmt_pro?style=social)](https://github.com/dis625406542/cleanstmt_pro)

---

**由独立开发者打造。被全球会计专业人士使用。**

🚀 **免费试用 CleanStmt：** [www.cleanstmt.com](https://www.cleanstmt.com)
